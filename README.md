## **AI-Powered PD Note Field Extraction & Risk Intelligence System**

### Simple Project Description

This project uses **LLM + Databricks + SQL/Python** to extract important information from **unstructured PD Notes/customer summaries**.

In the existing system, some required fields are **not available as separate structured fields**, but the information is available inside the PD Note. The LLM reads the PD Note, understands the context, and extracts fields such as **FOIR, income, obligations, BT status, BT bank, salary mode, occupation, and property details**.

The extracted information is converted from:

**Unstructured PD Note → LLM → Field Extraction → Business Rules → JSON → Structured Table → Risk/Business Analysis**

**Main benefit:** Instead of manually reading every PD Note to find specific information, the process automatically converts the unstructured information into **structured, usable data** for analysis and reporting.
