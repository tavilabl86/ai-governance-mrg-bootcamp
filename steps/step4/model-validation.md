# 🧑‍🔬 Model Validator – Agentic RAG Performance & Quality Validation

> ⚠️ **Note:** Log in with the **Model Validator** role before accessing validation tools.

---

## 🔑 Accessing watsonx.governance ModelManagement Validation Tools

1. Log in to IBM Cloud.
2. From the **Hamburger Menu (☰)**, navigate to **Resource list**.
3. Type **gov** in the filter by name search bar 
4. Select **gov-xxxxxxxxxxxxx**.
   ![image](https://github.ibm.com/user-attachments/assets/f8209714-7cb9-409f-9404-c308ffc13d89)

5. Select **Launch in Watson Openscale**
   ![image](https://github.ibm.com/user-attachments/assets/bcbe0902-fb04-4ae4-b0c1-2d75127d5fe1)

7.  In the IBM Watson OpenScale dashboard, click on the filter at the right of **Machine learning provider** to select your project
   ![image](https://github.ibm.com/user-attachments/assets/40713198-707d-467c-8b6e-a05e3763e4a5)

  then select your detached prompt template, **Agentic RAG Testing**
  ![image](https://github.ibm.com/user-attachments/assets/e622d185-92f2-40b4-9b2f-e13ab121a1c3)



---

## 🎯 Validation Responsibilities

As a Model Validator, your primary role is to ensure **Agentic RAG** meet performance, fairness, and quality standards, focusing on:

* **Fairness**
  Monitor and validate fairness metrics to detect bias against sensitive groups.

* **Alerts and Violations**
  Review alerts triggered by the system to investigate potential issues.

* **Quality Metrics**
  Assess overall **detached RAG prompt quality**, including precision, recall, and other key indicators.

* **Drift Detection**
  Track data, output, and prediction drift to ensure **detached RAG prompt stability** over time.

* **Global Explanation**
  Understand feature importance to validate **detached RAG prompt decision rationale**.

* **detached RAG prompt Performance Evaluation**
  Upload test datasets to evaluate **prompt outputs** against ground truth.

---

## 🔍 Validation Areas

### Fairness Validation

* Evaluate alerts related to fairness metrics (e.g., Disparate Impact, Statistical Parity Difference).
* Check alerts for sensitive groups (e.g., gender-based fairness).
* Investigate any violations flagged.

### Quality and Alerts

* Review alerts on quality metrics such as Precision, Recall, Accuracy, F1-Measure.
* Identify and address violations affecting **detached RAG prompt performance**.

### Drift Monitoring

* Observe drift alerts indicating changes in input data or **detached RAG prompt outputs**.
* Take action if drift impacts reliability.

### Generative AI Quality – Retrieval Augmented Generation (RAG)

* Assess alerts on answer quality and retrieval accuracy.
* Monitor content analysis metrics and data safety concerns.
* Investigate alerts indicating quality or safety issues in generated responses.
  
## First Task:(In Validation Phase) Platform : [Openscale](https://aiopenscale.cloud.ibm.com/)



### Detached RAG prompt Performance Evaluation Using Test Data

1. In the OpenScale dashboard, click **Actions** > **Evaluate Now**.

   
<img width="800" alt="image" src="./assets/Valid.png">


2. Upload this [dataset](./assets/hr_queries_with_ground_truth.csv) that includes input features and expected output (ground truth).

   * Including **Agentic RAG sample outputs**.
   * File constraints: Max size 8 MB, min 10 records, max 1000 records.

  
<img width="800" alt="image" src="./assets/Valid1.png"> 


3. Map all required fields from your uploaded csv.Click **Upload and Evaluate**.


. <img width="800" alt="image" src="./assets/Valid2.png"> 


4. Wait for evaluation to complete and review the results for accuracy and other metrics.

   
<img width="800" alt="image" src="./assets/Valid_all_green.png"> 

---

## ✅ Summary

Your validation work helps ensure that **Agentic RAG prompts**:

* Operate fairly without bias.
* Maintain high-quality performance.
* Adapt safely to changing data distributions.
* Generate reliable and compliant outputs.
* Meet expected performance benchmarks via test dataset evaluation.

---

## 🎉 Great Job!

By performing thorough validation, including test data evaluation, you support trustworthy, transparent, and ethical AI deployments!

---

[← Back to main guide](./model-validator-tasks.md.md)

