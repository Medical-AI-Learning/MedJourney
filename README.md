# MedJourney

 We introduce a new Chinese benchmark dataset MedJourney that covers the entire workflow of the patient's clinical journey. MedJourney consists of 12 datasets.

 We divide the clinical journey into four stages:


 ## Planning


At this stage, patients are becoming aware of potential health issues and are considering seeking medical care at a hospital.


### 1) Department Recommendation (DR) 
DR assists in identifying the most suitable departments based on patients’ primary complaints; 


### 2) Pre-Consultation Dialogue Summary (PCDS) 
PCDSutilizes a multi-turn conversation to gather and summarize patients’ information; 

### 3) Hospital Reception QA (HQA) 
HQA compiles frequently asked questions from patients before and during their hospital visits.

## Access

Following the planning stage, the patient can consult with the appropriate doctor. During the face-to-face diagnosis, there are two primary tasks where LLM can be utilized: 

### 1) Doctor Response Generation (DRG)

DRG can generate the doctor’s next response based on the historical patient-doctor dialogue. This can assist novice doctors and serve as a reminder for experienced doctors during the conversation; 

### 2) Patient-Doctor Dialogue Summarization (PDDS)

PDDS can alleviate the workload associated with writing medical records by providing concise summaries.


 ## Delivery

Upon receiving a patient’s information, doctors carefully review it to assess the individual’s medical history, current symptoms, and any pertinent diagnostic test results. They are then tasked with providing an initial diagnosis. This process entails determining the necessity for further examinations, identifying the patient’s disease, and deciding on the most suitable medication and treatment for their condition. To evaluate whether the medical LLM can accurately assess a patient’s complex condition in real-world clinical diagnoses, we’ve divided the service delivery into four stages:


### Examination Prediction (EP)


### Disease Prediction (DP)

### Treatment Prediction (TP) 

### Medication Prediction (MP)



## Ongoing Care


At this stage, patients have transitioned from receiving in-hospital care to managing their health independently outside the hospital. There are three key tasks where LLM can be applied: 

### 1) Drug QA (DQA)

This task involves addressing common questions patients may have about their medications;
### 2) Insurance QA (IQA)

This task includes answering frequently asked questions about medical insurance; 

### 3) Mental Health QA (MQA)

This task involves addressing common questions from patients who may be dealing with mental health issues outside the hospital.


## Citation

If you find our benchmark helpful, feel free to give us a cite.

```
@misc{MedJourney,
    title = {MedJourney: Benchmark and Evaluation of Large Language Models over Patient Clinical Journey},
    author = {Wu, Xian and Zhao, Yutian and Zhang, Yunyan and Wu, Jiageng and Zhu, Zhihong and Zhang, Yingying and Ouyang, Yi and Zhang, Ziheng and Wang, Huimin and Lin, Zhenxi and Yang, Jie, and Zhao, Shuang and Zheng, Yefeng},
    booktitle = "NeurIPS",
    year = {2024}
}

```

  
