When creating the client application:

 - Open Nougat Package Manager Console and execute this command:
 (Go to TOOLS > NuGet Package Manager and Select Package Manager Console) 

					Install-Package Microsoft.AspNet.WebApi.Client

					
 - If you encounter an error with JSON file format, Execute this:

					uninstall-package newtonsoft.json -force
					install-package newtonsoft.json


