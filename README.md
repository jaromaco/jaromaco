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
