# RealTimeAnalyticsExamples-StructuredStreaming
---
**Required**
- Python (installed on the machine running the `sender.py`
- Azure Event Hub Namespace
- Azure Event Hub
- Azure Databricks Workspace
---
## Steps
1. Clone this directory to your local machine
2. Provision an Azure Event Hub Namespace in your Azure Subscription  
*Record the **Name of your namespace** and a **Access Key** at the namespace level*
3. Create an Event Hub within that namespace  
*Record the name of the Event Hub*
4. Input the **Name of the Namespace**, **Access Key**, **Hub Name** in the correct places in the `sender.py`  
5. Navigate to the location of your git repository using Command Prompt and run `python sender.py`
6. Now import the two IPYNB files into your Azure Databricks workspace and follow the directions in the notebooks
