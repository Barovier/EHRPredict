<p align="center">
  <img src="https://github.com/Barovier/EHRPredict/assets/59474259/11e6a620-6f9b-482e-b9ba-e8c24335a58d" width="20%">
</p>


# EHRPredict
Makes predictions of patient outcomes on the basis of a variety of medical records

# Inputs
This project considers the following inputs:
- EMR
 - Imaging
  - Ultrasound
  - MRI
  - CAT Scan
  - Xray
 - Electronic Medical Record
  - Patient history
  - Patient symptoms
 - Lab tests
  - Blood assays
  - Urine samples
  - Stool samples

# Architecture
Generally we will use state of the art (SOTA) models according to the input medium. For example, we will use UNet for Imaging data, GPT, Amazon Comprehend Medical, or ClaudeAI to understand unstructured medical text (patient records), and simple regression models on numeric data such as that arising in lab testing. 

# Inspiration
Machine learning algorithms can be trained to recognize patterns in patient data, including lab results, imaging and medical history, in order to identify early signs of kidney disease and thereby allow timely diagnoses and prompt initiation of treatment plans that can improve outcomes for patients.

https://academic.oup.com/ckj/advance-article/doi/10.1093/ckj/sfad182/7233740
