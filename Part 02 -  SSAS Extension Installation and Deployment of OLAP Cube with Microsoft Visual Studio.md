# Microsoft SQL Server Analysis Services (SSAS) Extension Installation   

**Step 1:** Click "Create a New Project"   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/8081aa43-f965-475c-b60a-a03b05536950)   

**Step 2:** Select "Blank Solution > Click "Next"   
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/4a2f4537-4544-4d8c-8c1f-6dd38f9be0dc)   

**Step 3:** Click "Create"      
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/370d4dfa-58bf-4867-a840-140f524f6fa2)   

**Step 4:** Click "Manage Extensions" > Select "Microsoft Analysis Services Project" > Click "Download"      
![Slide4](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/1df6c60c-f806-47eb-ac39-33280cb7bded)   

**Step 5:** Click "Close"  
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/acfc48d6-7af7-4019-a18d-ad10d01ce55b)   

**Step 6:** Click "Modify"   
![Slide6](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/0621e6ce-4bed-4720-936c-73c944a2b6cf)   

**Step 7:** SSAS Extension Installation Completed    
![Slide7](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/6e6e1d49-def0-4b6d-a1e6-0a14cef01cb8)   


# Deployment of Online Analytical Processing (OLAP) Cube with Microsoft Visual Studio
**Step 1:** Click "Create a New Project"   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/4c9e8a85-3b04-4c08-b005-d62f12717832)    

**Step 2:** Select "Analysis Services Multidimensional and Data Mining Project" >  Click "Next"   
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/5d83e1f0-396c-43fd-9e2a-8164a6385436)    

**Step 3:** Click "Create"   
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/9c867a58-c65f-4cc5-ad9d-b3c4e5621527)   

<ins>Data Source</ins>: To connect Microsoft SQL Server Management Studio's Giant Bicycles Data Warehouse    
**Step 4:** Right Click "Data Source" > Click "New Data Source" > Click "Next"   
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/14707af7-3f3f-4cfc-92a5-cae99548d782)   

**Step 5:** Select "Create a data source based on an existing or new connection" > Click "New" > Insert Server name > "Insert database name > Click "OK"   
![Slide6](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/344d6b41-f8b0-4fb8-81e0-fdf00e91cedf)   

**Step 6:** Select "MSI Giant Bikes DataWarehouse" > Click "Next"   
![Slide7](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/52d33f8a-35b0-44cd-b44e-ed37a94e6929)   

**Step 7:** Select "Use the service account" > Click "Next"   
![Slide8](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/29ffb7e6-d7e0-4f90-af11-9eb6246db4ae)   

**Step 8:** Click "Finish" > Giant Bicycles Data Warehouse completed   
![Slide9](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/b2a4ed68-ee26-4475-a38e-2dca07cd7f9c)   

<ins>Data Source View</ins>: To select 12 relevant tables    
**Step 9:** Right Click "Data Source View" > Click "New Data Source View" > Click "Next"   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/d03e2548-7f27-4700-9f63-486753a22fce)   

**Step 10:** Select "Giant Bikes Data Warehouse" > Click "Next"    
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/1f1eb0ff-af97-4e66-bc98-9ccef2d2c7bd)   

**Step 11:** Select 12 relevant tables   
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/88c282b9-b834-458e-97dc-03c21a610046)   

**Step 12:** Click "Finish"   
![Slide4](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/c60ee75c-50dc-415c-84d3-26e847762f69)   

**Step 13:** Selection of relevant dimensions and facts tables completed   
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/8436e058-7bd4-4b80-98b0-953554c6308b)   

<ins>Cubes</ins>: To distinguish the 12 tables into dimension tables and measure tables   
**Step 14:** Right Click "Cubes" > Click "New Cube" > Click "Next"   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/1241256d-d067-4759-bee3-fcac7bcb2f7b)   

**Step 15:** Select "Use existing tables" > Click "Next"   
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/973d4a50-3848-419c-91e7-d2d12d86c0c4)   

**Step 16:** Select "FactInternet Sales" and "FactReseller Sales" > Click "Next"   
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/dcd6eb33-3aeb-456a-b82e-a7c2824d320f)   

**Step 17:** Click "Next"   
![Slide4](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/73f51173-434d-448f-a218-66ebb67bc8ee)   

**Step 18:** Unselect "Fact Internet Sales" and "Fact Reseller Sales" > Click "Next"   
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/c5ffae81-6196-4a1e-a122-5143a3f6af8f)   

**Step 19:** Click "Finish" > Distinguish of dimensions and facts tables completed   
![Slide6](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/66dd041f-178a-4eb7-a33d-82324a689860)   

<ins>Dimensions</ins>: To select relevant attributes from the 10 dimensions tables   
**Step 20:** Select relevant attributes of Dim Date dimension table   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/da53a891-4090-4586-a771-afca2e7a73bd)   

**Step 21:** Select relevant attributes of Dim Product dimension table   
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/6acaba3a-f1a7-410d-88ed-847fef6a689f)   

**Step 22:** Select relevant attributes of Dim Customer dimension table   
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/0e6a799e-49b5-4b9e-a54c-abe5d853b548)   

**Step 23:** Select relevant attributes of Dim Sales Territory dimension table    
![Slide4](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/03a7dbb7-6a3d-4d35-ac4b-96d0b3f84c83)   

**Step 24:** Select relevant attributes of Dim Promotion Territory dimension table    
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/40361276-1973-4762-b4b1-d04117bd5976)   

**Step 25:** Select relevant attributes of Dim Employee Territory dimension table   
![Slide6](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/dc3ed748-086c-4b31-ac77-b401ef709204)   

**Step 26:** Select relevant attributes of Dim Reseller Territory dimension table   
![Slide7](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/0aed0139-9400-43e5-80a5-f204391e71da)   

**Step 27:** Right Click "Giant Bikes - Demonstration" > Click "Build" > Click "Deploy" > Deployment of OLAP cube completed   
![23124](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/3029b4c9-312f-4bda-aa8e-faf5af2a25c2)   


# Multidimensional Expressions (MDX) Calculation   
**Step 1:** Select "Trek Bikes Datahouse.cube" > Click "Calculations"   
![Slide1](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/636c2a4d-f50c-4755-b0f0-745ce876ec21)   

<ins>Reseller Gross Profit Margin</ins>:   
![Slide2](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/eddc212d-2880-4789-92a8-81f97f92bbfa)   

<ins>Reseller Net Profit</ins>:   
![Slide3](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/b450ac0a-6820-4939-b61e-d9d461970b8a)   

<ins>Total Sales Quantity</ins>:   
![Slide4](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/b304d95c-39c0-449a-908e-46c08129aceb)   

<ins>Total Sales Amount</ins>:   
![Slide5](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/99db0350-6708-49d2-aa65-09719a82f918)   

<ins>Average Freight Cost</ins>:   
![Slide6](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/38774e29-b58f-4bb0-9915-9ea8917dd93c)   

<ins>Average Tax Amount</ins>:   
![Slide7](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/dd6dc37c-a235-41a9-b65c-4accbaaf796d)   

<ins>Internet Gross Profit Margin</ins>:   
![Slide8](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/2e13960b-abf9-4ce9-90f4-dc169eb786c9)   

<ins>Internet Net Profit</ins>:   
![Slide9](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/7adfaa8e-4ea2-4bea-abd8-000532d24212)   

<ins>Total Internet Expenses</ins>:   
![Slide10](https://github.com/LiewJunYen-DataAnalyst/Business-Intelligence-BI-Giant-Bicycles-Organization-Academic/assets/130137513/f035cfdc-44f1-4709-b445-26cbb511b9c1)
