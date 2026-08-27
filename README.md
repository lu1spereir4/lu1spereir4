# ¡Hola! Soy Luis Pereira 👨‍💻
### Data Engineer | ELT/ETL • Lakehouse • Dimensional Modeling • Automation

Ingeniero Civil Informático (Universidad del Bío-Bío / UPV España). Me enfoco en construir **pipelines reproducibles**, **modelos analíticos (Star Schema)** y **arquitecturas de datos eficientes**.  
He trabajado con volúmenes grandes (ej. **50M+ filas**) y con sistemas **offline-first** (IoT) donde la confiabilidad y sincronización importan.

📍 Concepción, Chile · 🌎 Abierto a remoto 
📫 [luispereira502@gmail.com](mailto:luispereira502@gmail.com) · [LinkedIn](https://www.linkedin.com/in/luis-pereira-24216124b/)

---

## 🎯 Rol que busco
**Data Engineer / Analytics Engineer**. 
Me interesa: **ELT/ETL**, **SQL avanzado**, **modelado dimensional**, **calidad de datos**, **performance**, **Docker/CI**, y cloud (AWS).

---

## ✅ Proof of Work
- **Lakehouse Medallion** (Raw → Silver → Gold) con **50.5M** registros (Parquet/DuckDB) + modelo estrella para analítica.
- **Data Warehouse** (OLTP → OLAP) con **Star Schema** + queries de negocio (CTEs, window functions, KPIs).
- **Offline-first POS (IoT)** con sincronización asíncrona cuando vuelve la conectividad.
- Práctica de ingeniería: **scripts reproducibles**, estructura clara, documentación y decisiones técnicas.

---

## ⭐ Proyectos Destacados (Pinned) — qué mirar primero

### 1) 📊 Data Lakehouse: Movilidad Pública Santiago (DTPM) — **Flagship**
**Qué demuestra:** Big data real + arquitectura + performance + analítica.  
- Medallion architecture (Raw/Silver/Gold) + Parquet
- SQL Server (Star Schema, índices/particiones) para consumo BI
- Ingesta/transformaciones con DuckDB/Python

🔗 Repo: *(https://github.com/lu1spereir4/Data_Lakehouse_Movilidad_Publica_Santiago)*  
📐 Diagrama: *(link a /docs/architecture.png)*  
🧪 Bench/Resultados: *(link a /benchmarks o sección de métricas)*

---

### 2) 📈 Data Warehouse Pagila: OLTP → OLAP (Star Schema)
**Qué demuestra:** criterio de modelado + SQL analítico.  
- Grano, dims/facts, dim_date, métricas
- Queries: revenue, cohortes, retención, top customers, tendencias

🔗 Dentro de: **ProyectosDataEngineer** → `./pagila_dw/` *(https://github.com/lu1spereir4/ProyectosDataEngineer/tree/main/pagila_to_starModel)*  
📐 Modelo: *(https://github.com/lu1spereir4/ProyectosDataEngineer/blob/main/pagila_to_starModel/star_model.png)*  
🧾 Queries: *(link a analytics.sql / carpeta queries)*

---

### 3) 💳 Fraud / Credit Card Transactions (DW + Analytics)
**Qué demuestra:** data quality + joins correctos + KPIs.  
- Dims (customer/merchant/date) + facts
- Checks de duplicidad/llaves, integridad referencial
- Métricas y segmentación (fraude por merchant/estado/tiempo)

🔗 Dentro de: **ProyectosDataEngineer** → `./creditcard_fraud_dw/` *(https://github.com/lu1spereir4/ProyectosDataEngineer/tree/main/fintech)*  
📐 Modelo: *(https://github.com/lu1spereir4/ProyectosDataEngineer/blob/main/fintech/models/star_model_fintech.png)*  
✅ Quality checks: *(link a quality_checks.sql)*

---

### 4) ⚙️ Offline-first POS IoT (Raspberry Pi + Sync)
**Qué demuestra:** ingeniería en condiciones reales (sin internet).  
- Captura local + persistencia + sync asíncrono
- Arquitectura pensada para fallos y reintentos

🔗 Repo: *(https://github.com/lu1spereir4/GestionInventario)*  
🌐 Sistema al que se sincroniza: *(www.wesrugby.site)*

---

## 🧰 Tech Stack
**Data:** Python, SQL, DuckDB, Pandas, PostgreSQL, SQL Server  
**Infra/DevOps:** Docker, Git, Linux, AWS  
**Apps/IoT:** Node.js, Flutter, Raspberry Pi, MongoDB

---

## 🏅 Extra 
- 🏆 Campeón Nacional de Robótica (BRC 2025) — optimización HW/SW.

---

## 🤝 Contacto
Si estás contratando para **Data Engineering** en modalidad 100% Remoto y te interesa alguien que:
- modele bien (grano, facts/dims),
- escriba SQL fuerte,
- piense en performance y calidad,
- y deje todo reproducible (Docker + docs),

hablemos:  
📫 [luispereira502@gmail.com](mailto:luispereira502@gmail.com) · [LinkedIn](https://www.linkedin.com/in/luis-pereira-24216124b/)

> “Los datos sin un buen diseño de arquitectura son solo ruido.”
