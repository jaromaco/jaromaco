<h1 align="center">Hi, I'm Javier Roma 👋</h1>
<h3 align="center">Geospatial Data Engineer · FME Expert · PostGIS & Python · AWS</h3>
<p align="center">Madrid, Spain · Remote · In GIS since 2010</p>

<p align="center">
  <a href="https://www.linkedin.com/in/javier-roma-geospatial-engineer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://oikosgis.com"><img src="https://img.shields.io/badge/Website-oikosgis.com-2E7D32?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
</p>

---

### 🧭 About me
I build **reliable pipelines for spatial data**. After 15+ years turning maps into decisions, I now focus on the work behind them: loading, converting, validating and publishing geospatial data, from desktop GIS to PostGIS and the cloud.

- 🔁 Automating manual GIS workflows with **FME** and **Python**
- 🗄️ Designing and loading **PostGIS** databases with quality control
- ☁️ Moving spatial data to **AWS** in cloud-native formats (GeoParquet)
- 📱 Connecting field data (**QField**, Survey123) to central databases

---

### 🚀 Featured project: [spain-flood-exposure](https://github.com/jaromaco/spain-flood-exposure)
Pipeline that measures building and population exposure to floods in Valencia using open data.

```mermaid
flowchart LR
  A[Catastro & INE<br/>open data] -->|AWS Lambda| B[(S3 raw)]
  B -->|Python| C[(S3 silver<br/>GeoParquet)]
  C --> D[Flood exposure<br/>analysis]
```

✅ Built: Lambda ingestion · S3 data lake · GeoParquet conversion · pytest · least-privilege IAM  
🛠️ Next: Glue + PySpark/Sedona · dbt on Athena · Airflow · PostGIS

---

### 🛠️ Tech stack
**Data & ETL**  
![FME](https://img.shields.io/badge/FME-E35205?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=pandas&logoColor=white)

**Cloud**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)

**GIS**  
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS_Pro_|_Server_|_Portal-2C7AC3?style=flat-square&logo=arcgis&logoColor=white)
![QField](https://img.shields.io/badge/QField-6FB33F?style=flat-square&logoColor=white)

---

### 🌱 Currently learning
`AWS Certified Data Engineer` · `PySpark` · `Apache Airflow` · `dbt`

### 🎓 Credentials
- Master's in GIS, **UNIGIS**
- Experto en Desarrollo GIS, **Esri España**

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaromaco&layout=compact&hide_border=true" alt="Top languages" height="150"/>
</p>
