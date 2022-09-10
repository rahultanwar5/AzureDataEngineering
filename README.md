<h1 align="center">Azure Data Engineering Project</h1>
<h2 align="left">Business Use case: </h2>
<h3 align="left">We have data coming to azure blob storage in json format and we need to create pipeline which will be able to convert this file into csv format and store in output folder. we will mount our databricks to output container and need to do data cleaning operations there and convert into proper reporting formats and finally we will derive business metrics with the help of tableau.</h3>

<h2 align="left">High Level Steps:</h2>
<h3 align="left">

**1. Create blob storage in azure**

**2. Create data pipeline in azure data factory**

**3. Mount blob storage to databricks and perform cleaning using pyspark and spark sql**

**4. Tableau for visualization for business metrics**
</h3>

<h2 align="left">Prerequisite</h2>
<h3 align="left">

**- Azure account with active subscription**

**- Databricks community edition account**

**- Tableau public account**

**- Knowledge about storage account, dataframe, azure data factory, sql stc.**
</h3>

<h2 align="left">Complete Steps:</h2>
<h3 align="left">

**1. Input JSON file records format**

![](Images/JSON_Input_data.JPG)

**2. Open Azure portal and Create one Blob Storage Account**

![](Images/Storage_account.JPG)

**3. Create two new containers : raw & target**

![](Images/Container.JPG)

**4. Open raw container and upload Input JSON file in raw container.**

![](Images/raw_container.JPG)

**5. Create Azure data factory and Open it to create new pipeline.**

![](Images/data_factory.JPG)

**6. Create data factory pipeline so that we can convert our JSON input file to CSV file format. Also we have to add columns data for future purpose**

![](Images/data_factory_process.JPG)

**7.**

![]()

**8.**

![]()

**9.**

![]()

**10.**

![]()

**11.**

![]()

**12.**

![]()

**13.**

![]()

**14.**

![]()






