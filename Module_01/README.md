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

![Data Architectural Solution for Interior Design Company](https://github.com/DanyaSmi/DE-101/blob/d15bea72d941b2dea306aabad95315757ccdcdaf/Module_01/DL%20M1%20HW%20Architecture.jpg)

---

## 2. Data Analytics (MS Excel)

**Materials.**<br/>
[Build Steps DashBord](https://github.com/Data-Learn/data-engineering/blob/master/DE-101%20Modules/Module01/DE%20-%20101%20Lab%201.1/build_steps_dashboard.md)<br/>
[Andrew Abela](https://drive.google.com/file/d/1dQcaaIjvLxycUxz8_R5diD4JQ26x4tO0/view)<br/>
[Ganna Ponomaryeva](https://drive.google.com/file/d/1iuFfN0DZ5shLzm-BzukJY4XlpiqZmlsZ/view)<br/>
[Building Pivot Table](https://support.microsoft.com/ru-ru/office/%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D1%81%D0%B2%D0%BE%D0%B4%D0%BD%D0%BE%D0%B9-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D1%8B-%D0%B4%D0%BB%D1%8F-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D0%BB%D0%B8%D1%81%D1%82%D0%B0-a9a84538-bfe9-40a9-a8e9-f99134456576?ui=ru-ru&rs=ru-ru&ad=ru)<br/>

__The reports and its visualization methods__<br/>
1. `Income & Prifit Dynamics` Line Chart
2. `Goods Categories (Compare)` Stacked Column Chart
3. `Regional Managers (Compare)` Bar Chart
4. `Segments (Compare)` Bar Chart
5. `Segments Dynamics` Line Chart
6. `Key Indicators` 
7. `By States` Map Chart
8. `By Regions (Compare)` Doughnut Pie
9. `By Returns, %` Pie Chart

[The Link to my SuperStore Dashoard.pdf](https://github.com/DanyaSmi/DE-101/blob/1ffc8c6201f160b9a74737abcc3e0b20b912d775/Module_01/DL%20M1%20HW%20SuperStore%20Dashboard.pdf)

![The SuperStore DashBoard](https://github.com/DanyaSmi/DE-101/blob/e5276a2d4dac82c1edf64dddfbc16b0107fa087c/Module_01/DL%20M1%20HW%20SuperStore%20Dashboard.jpg)


