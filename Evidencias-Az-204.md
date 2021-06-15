## Alumno: Lizbeth Gómes Monserratte

## Ejercicios y Labs para dejar evidencia del AZ-204

| Demo/Ejercicios |      | Descripcion                                                  | Labs |
| --------------- | ---- | ------------------------------------------------------------ | ---- |
| Mod 01          | 1    | /docs/mod01_01_Creating a web app by using the Azure portal |      |
| Mod 01          | 2    | docs/mod01_02_Create a static HTML web app by using      |      |
| Mod 01          | 3    | docs/mod01_03_Create a Web App with a local Git  deployment source |      |
| Mod 02          | 1    | docs/mod02_01_Create an HTTP trigger function by using  the Azure portal |      |
| Mod 03          | 1    | docs/mod03_01_Create a block blob storage account        |      |
| Mod 03          | 2    | docs/mod03_02_Add a policy to Azure Blob storage         |      |
| Mod 03          | 3    | docs/mod03_03_Using the Azure Blob storage client  library for .NET v11 |      |
| Mod 04          | 1    | docs/mod04_01_Create Azure Cosmos DB resources by using  the Azure Portal |      |
| Mod 04          | 2    | docs/mod04_02_Working with Azure Cosmos DB by using  .NET |      |
| Mod 05          | 1    | docs/mod05_01_Creating an Azure VM by using the Azure  portal |      |
| Mod 05          | 2    | docs/mod05_02_Creating an Azure VM by using  PowerShell  |      |
| Mod 05          | 3    | docs/mod05_03_Create ARM templates by using the Azure  Portal |      |
| Mod 05          | 4    | docs/mod05_04_Create ARM templates by using Visual  Studio Code |      |
| Mod 05          | 5    | docs/mod05_05_Retrieve and deploy existing Docker image  locally |      |
| Mod 05          | 6    | docs/mod05_06_Create a container image by using  Docker  |      |
| Mod 05          | 7    | docs/mod05_07_Deploy an image to ACR by using Azure  CLI |      |
| Mod 05          | 8    | docs/mod05_08_Run Azure Container Instances by using the  Cloud Shell |      |
| Mod 06          | 1    | docs/mod06_01_Register an app with the Microsoft  Identity platform |      |
| Mod 06          | 2    | docs/mod06_02_Interactive authentication by using  MSAL.NET |      |
| Mod 06          | 3    | docs/mod06_03_Retrieving profile information by using  the Microsoft Graph SDK |      |
| Mod 07          | 1    | docs/mod07_01_Set and retrieve a secret from Azure Key  Vault by using Azure CLI |      |
| Mod 08          | 1    | docs/mod08_01_Create an APIM instance by using Azure  CLI |      |
| Mod 08          | 2    | docs/mod08_02_Import an API by using the Azure  Portal   |      |
| Mod 08          | 3    | docs/mod08_03_Create and publish a product               |      |
| Mod 08          | 4    | docs/mod08_04_Transform your API by using policies       |      |
| Mod 09          | 1    | docs/mod09_01_Create a Logic App using the Azure  Portal |      |
| Mod 10:         | 1    | docs/mod10_01_Route custom events to web endpoint by  using the Azure CLI commands and Event Grid |      |
| Mod 11:         | 1    | docs/mod11_01_Use .NET Core to send and receive messages  from a Service Bus queue |      |
| Mod 12:         | 1    | docs/mod12_01_Instrument an ASP.NET Core app for  monitoring in Application Insights |      |
| Mod 13:         | 1    | docs/mod13_01_Connect an app to Azure Cache for Redis by  using .NET Core |      |

# Modulo 1 Creating a web app by using the Azure portal    

### Build a back-end API by using Azure Storage and the Web Apps feature of Azure App Service

![M1-Exer1a](ZZ-lab/M1-Exer1a.PNG)



## Build a front-end web application by using Azure Web Apps

imgstorlgm 

#### Access keys
6OXbgVeXctaLAs/Bqr7txqtEG92KxWJg1l12Di112KRHyr/aEy0ydhDsofZBf2Eypg+RLXGZNgtP3EXHKE8yNA==

#### Connection string

DefaultEndpointsProtocol=https;AccountName=imgstorlgm;AccountKey=6OXbgVeXctaLAs/Bqr7txqtEG92KxWJg1l12Di112KRHyr/aEy0ydhDsofZBf2Eypg+RLXGZNgtP3EXHKE8yNA==;EndpointSuffix=core.windows.net

#### URL

https://imgapilgm.azurewebsites.net

![M1-Exer2a](ZZ-lab/M1-Exer2a.PNG)

![M1-Exer2b](ZZ-lab/M1-Exer2b.PNG)

![M1-Exer2c](ZZ-lab/M1-Exer2c.PNG)

az webapp deployment source config-zip --resource-group ManagedPlatform --src api.zip --name imgapilgm

az webapp deployment source config-zip --resource-group ManagedPlatform --src web.zip --name imgwebLgm

![M1-Exer2d](ZZ-lab/M1-Exer2d.PNG)



# Modulo 2 - Create an HTTP trigger function by using  the Azure portal

###  Implement Azure Functions

![M2-1a](ZZ-lab/M2-1a.PNG)

### Storage account name

​	funstorlgm

### Conection String

DefaultEndpointsProtocol=https;AccountName=funcstorlgm;AccountKey=Mq473aEXFvjm5hqTeROm23JAPgNGzAOoqbuXDBPMcG9QN2QKKxUN8wZrjMoOJfJe2IL7is0w5OCfOKRNPhs/gA==;EndpointSuffix=core.windows.net;



![M2-1b](ZZ-lab/M2-1b.PNG)

### Exercise 2 - Configure a local Azure Functions project



![M2-1c](ZZ-lab/M2-1c.PNG)

![M2-1d](ZZ-lab/M2-1d.PNG)

### Exercise 3: Create a function that's triggered by an HTTP request



![M2-Exer3-1a](ZZ-lab/M2-Exer3-1a.PNG)

![M2-Exer3-2a](ZZ-lab/M2-Exer3-2a.PNG)

![M2-Exer3-3a](ZZ-lab/M2-Exer3-3a.PNG)

![M2-Exer3-3b](ZZ-lab/M2-Exer3-3b.PNG)

### Http Functions:

        Echo: [POST] http://localhost:7071/api/Echo

![M2-Exer4-1a](ZZ-lab/M2-Exer4-1a.PNG)

![M2-Exer4-2a](ZZ-lab/M2-Exer4-2a.PNG)

![M2-Exer4-3a](ZZ-lab/M2-Exer4-3a.PNG)

![M2-Exer4-3b](ZZ-lab/M2-Exer4-3b.PNG)

![M2-Exer4-4a](ZZ-lab/M2-Exer4-4a.PNG)

![M2-Exer4-5a](ZZ-lab/M2-Exer4-5a.PNG)

![M2-Exer5-1a](ZZ-lab/M2-Exer5-1a.PNG)

![M2-Exer5-2a](ZZ-lab/M2-Exer5-2a.PNG)

![M2-Exer5-3a](ZZ-lab/M2-Exer5-3a.PNG)

![M2-Exer5-4a](ZZ-lab/M2-Exer5-4a.PNG)

![M2-Exer5-4b](ZZ-lab/M2-Exer5-4b.PNG)



### Exer6-1a-DeployLocalFunctionProjectToAzureFunctionsCoreTools

![M2-Exer6-1a](ZZ-lab/M2-Exer6-1a.PNG)

![M2-Exer6-2a](ZZ-lab/M2-Exer6-2a.PNG)

![M2-Exer6-2b](ZZ-lab/M2-Exer6-2b.PNG)

![M2-Exer6-2c](ZZ-lab/M2-Exer6-2c.PNG)

### Exer7-1a-Clean up your subscriptions

![M2-Exer7-1a](ZZ-lab/M2-Exer7-1a.PNG)

![M2-Exer7-2a](ZZ-lab/M2-Exer7-2a.PNG)

# Modulo 3 - Develop solutions that use blob storage

# Create a block blob storage accountMod 

####  Exercise 1: Create Azure resources

**Task 2:** Create a Storage account

![M3-Exer1-T2a](ZZ-lab/M3-Exer1-T2a.PNG)

![M3-Exer1-T2b](ZZ-lab/M3-Exer1-T2b.PNG)



![M3-Exer1-T2c](ZZ-lab/M3-Exer1-T2c.PNG)

#### Exercise 2: Upload a blob into a container

**Task 1:** *Create storage account containers*

**Primary endpoint:  Blob service** : https://mediastorlgm.blob.core.windows.net/

**Key: **

V8t7LYbTEojWvANU9ygBEdEm/3D/nCXdBku5VGKg0RHQ0PAOTTA8SlepG/kj8MFsNDYKtdg5cw5N8343exV0kg==

![M3-Exer2-T1a](ZZ-lab/M3-Exer2-T1a.PNG)

**Task 2:** *Upload a storage account blob*

![M3-Exer2-T2a](ZZ-lab/M3-Exer2-T2a.PNG)

#### Exercise 3: Access containers by using the .NET SDK

**Task 1:** *Create .NET project*

![M3-Exer3-T1a](ZZ-lab/M3-Exer3-T1a.PNG)

**Task 2:** Modify the Program class to access Storage

‌‌![M3-Exer3-T2a](ZZ-lab/M3-Exer3-T2a.PNG)

**Task 3:** Connect to the Azure Storage blob service endpoint

![M3-Exer3-T3a](ZZ-lab/M3-Exer3-T3a.PNG)

![M3-Exer3-T3b](ZZ-lab/M3-Exer3-T3b.PNG)

**Task 4:** *Enumerate the existing containers*

![M3-Exer3-T4a](ZZ-lab/M3-Exer3-T4a.PNG)

#### Exercise 4: Retrieve blob Uniform Resource Identifiers (URIs) by using the .NET SDK

**Task 1:** Enumerate the blobs in an existing container by using the SDK

![M3-Exer4-T1a](ZZ-lab/M3-Exer4-T1a.PNG)

**Task 2:** *Create a new container by using the SDK*

![M3-Exer4-T2a](ZZ-lab/M3-Exer4-T2a.PNG)

**Task 3:** *Upload a new blob by using the portal*

![M3-Exer4-T3a](ZZ-lab/M3-Exer4-T3a.PNG)

**Task 4:** *Access blob URI by using the SDK*

![M3-Exer4-T4a](ZZ-lab/M3-Exer4-T4a.PNG)

**Task 5:** *Test the URI by using a browser*

[mediastorlgm.blob.core.windows.net](https://mediastorlgm.blob.core.windows.net/vector-graphics/graph.svg)



![M3-Exer4-T5a](ZZ-lab/M3-Exer4-T5a.PNG)

#### Exercise 5: Clean up your subscription

**Task 1:** Open Azure Cloud Shell and list resource groups

![M3-Exer5-T1a](ZZ-lab/M3-Exer5-T1a.PNG)

**Task 2:** *Delete a resource group*

![M3-Exer5-T2a](ZZ-lab/M3-Exer5-T2a.PNG)

![M3-Exer5-T2b](ZZ-lab/M3-Exer5-T2b.PNG)



# 

