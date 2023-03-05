# Module1 - Role and responsibility of Data Analytics

[DataLearn DE-101 Module 01](https://github.com/Data-Learn/data-engineering/blob/master/DE-101%20Modules/Module01)

`draw.io` `MS Excel`

## 1. Architecture of Data Analytics solution

I developed the Architecture Solution y using [draw.io](https://app.diagrams.net/).

**1. Source Layer.**<br/>
The source of systems with Raw Data (OLTP - Online Transaction Pocessing).
 - processing transactions;
 - the systems quickly work for Data adding to DataBases but don't good for analysis responds;
 - business processes makes Data;
 - all Raw Data goes to a storage.

**2. Storage Layer.**<br/>
Storage of Data for further analysis (DataWarehouses, DataLake, DataPlatform).
 - should have 2 layers for Data:
   * Staging - a copy og all Data from Source Layer;
   * BL - a Data model.

**3. Business Layer.**<br/>
Business users have an access to all Data by using I Business Intelligence tools (Tableau, Power BI, SAP BO, Excel, QlikView) or SQL. There is connection to the systems for the generating of reports.

There can be one more layer - Processing/ Computer Layer - for data transormation before loading to a storage.

[The Link to my Architecture Solution](https://github.com/DanyaSmi/DE-101/blob/199e5a36a7c38a3d2dae527651e90f20ffe6ccb9/Module_01/DL%20M1%20HW%20Architecture.drawio)
