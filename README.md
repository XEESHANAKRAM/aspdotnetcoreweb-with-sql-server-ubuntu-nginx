First open a terminal on the server and run the commands to install the runtime:

**sudo apt-get update**
**sudo apt-get install -y dotnet-sdk-8.0  **#https://learn.microsoft.com/en-gb/dotnet/core/install/linux-ubuntu-2204

**dotnet --info **

#checking successfully install or not , if the result is like this then good to go

dotnet --info
.NET SDK:
 Version:           8.0.102
 Commit:            b7800db369
 Workload version:  8.0.100-manifests.03fa9662

Runtime Environment:
 OS Name:     ubuntu
 OS Version:  22.04
 OS Platform: Linux
 RID:         ubuntu.22.04-x64
 Base Path:   /usr/lib/dotnet/sdk/8.0.102/

.NET workloads installed:
 Workload version: 8.0.100-manifests.03fa9662
There are no installed workloads to display.

Host:
  Version:      8.0.2
  Architecture: x64
  Commit:       1381d5ebd2

.NET SDKs installed:
  8.0.102 [/usr/lib/dotnet/sdk]

.NET runtimes installed:
  Microsoft.AspNetCore.App 8.0.2 [/usr/lib/dotnet/shared/Microsoft.AspNetCore.App]
  Microsoft.NETCore.App 8.0.2 [/usr/lib/dotnet/shared/Microsoft.NETCore.App]

Other architectures found:
  None

Environment variables:
  Not set

global.json file:
  Not found

Learn more:
  https://aka.ms/dotnet/info

Download .NET:
  https://aka.ms/dotnet/download

**Deploy the ASP.NET Core Web App to Linux
**
Push the code github repo once the code is pushed 

Now install nginx in ubuntu
**sudo apt install nginx
systemctl status nginx #server running successfuly 
cd /var/www
mkdir app
cd app
git clone https://github.com/XEESHANAKRAM/aspdotnetcoreweb
**






  
