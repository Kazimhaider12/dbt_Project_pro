# 🚀 My Journey into dbt (Data Build Tool)

<img width="1918" height="988" alt="image 2" src="https://github.com/user-attachments/assets/544add69-8cc9-4411-8623-9124135ccde1" />

Search Engine link here:
(bronze -> source) create to all csv: https://docs.getdbt.com/docs/build/sources?version=1.12
(macro -> change echema) default to bronze: https://docs.getdbt.com/docs/build/custom-schemas?version=1.12
Generic Test documentary: https://docs.getdbt.com/docs/build/data-tests?version=1.12
(snapshot -> source) SCD: https://docs.getdbt.com/docs/build/snapshots?version=1.12#add-a-snapshot-to-your-project

use databricks:
<img width="1909" height="758" alt="databricks for dbt" src="https://github.com/user-attachments/assets/55bdca71-1b5e-47e4-9dd1-ee83f3cb448f" />
Data Engineering Learning Update**

I’ve recently been working hands-on with **dbt (Data Build Tool)** as part of my Data Engineering learning journey, and it has completely changed the way I think about data transformation.

---

💡 **What I Learned in dbt:**

📌 **Layered Architecture (Medallion Model)**

* Bronze → Raw data ingestion
* Silver → Cleaned & transformed data
* Gold → Business-ready analytics tables

📌 **SQL-Based Transformations**

* Writing modular SQL models
* Using `ref()` for dependency management

📌 **Jinja Templating**

* Dynamic SQL generation
* Loops, conditions, and variables

📌 **Macros in dbt**

* Reusable SQL logic (like functions)
* Helps reduce duplication and improve scalability

📌 **dbt Tests**

* Data quality checks (unique, not null, accepted values)
* Ensuring reliable analytics datasets

📌 **Incremental Models & Snapshots**

* Efficient data processing (only new/changed data)
* Tracking historical changes (SCD Type 2 concept)

---

⚙️ **Key Tools I Practiced With:**

* dbt Core
* Git & GitHub (version control)
* SQL (advanced transformations)

---

🔥 **What I Realized:**
dbt is not just a tool — it brings Data engineering principles into data transformation, making pipelines:

* Modular
* Scalable
* Maintainable
* Production-ready
