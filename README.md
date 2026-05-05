<img width="674" height="446" alt="image" src="https://github.com/user-attachments/assets/1332a5bf-95a3-4948-b3b4-e5f1fa77d191" />

# Image-Annotation-CVAT-Electrical-Components-

---

# 📄 Image Annotation README (CVAT – Electrical Components)

## 🧩 Project Overview

This project involves **image annotation for electrical infrastructure components** using the CVAT platform.

The goal is to accurately label **insulators** and **surge arresters** in images using bounding boxes and predefined classes.

---

## 🔗 Task Access

* **CVAT Job Link:** https://app.cvat.ai/tasks/1991591/jobs/3565349
---

## 🖼️ Sample Annotation
<img width="1653" height="800" alt="image" src="https://github.com/user-attachments/assets/bde5b0fd-6f37-43ca-a95f-f434200c7c0f" />

<img width="1632" height="766" alt="image" src="https://github.com/user-attachments/assets/82738db4-236a-4d31-a302-70bb2378d41e" />

<img width="1635" height="765" alt="image" src="https://github.com/user-attachments/assets/b8162bc6-b1d0-4040-ab80-ffd95a6e1893" />

<img width="1613" height="803" alt="image" src="https://github.com/user-attachments/assets/fc3d166e-f9c7-46e9-aa37-5951c780b6a3" />

<img width="1604" height="775" alt="image" src="https://github.com/user-attachments/assets/aa3b1418-13bf-498b-a0fc-6ef500b5ba89" />

<img width="1691" height="813" alt="image" src="https://github.com/user-attachments/assets/c0031619-61c2-4812-9eda-04730652dba8" />

<img width="1710" height="803" alt="image" src="https://github.com/user-attachments/assets/1ee7482a-deeb-4b23-bb54-19fcd3de20c1" />

> This shows an example of bounding box annotations and label assignments in CVAT.

---

## 🛠️ Tools Used

* CVAT – for image annotation
* Bounding Box Tool – for object detection labeling

---

## 🏷️ Label Classes

Only the following **four labels** were used (strictly enforced):

1. **Insulator Polymer**
2. **Insulator Porcelain**
3. **Arrester Polymer**
4. **Arrester Porcelain**

No additional labels were created or modified.

---

## 📌 Annotation Guidelines

### 1. Object Identification

* Identify all visible:

  * **Insulators**
  * **Surge (lightning) arresters**

---

### 2. Bounding Box Rules

* Draw **tight bounding boxes** around each object
* Ensure:

  * Object is fully enclosed
  * Minimal background inclusion
* Avoid:

  * Including poles, wires, or unrelated structures

---

### 3. Classification Criteria

Each object is classified based on:

#### ➤ Function

* Insulator
* Surge Arrester

#### ➤ Material

* Polymer
* Porcelain

---

## 🔍 Label Identification Guide

### 🔹 Insulator Polymer

* Dark grey or black
* Flexible silicone/rubber material
* Non-ceramic sheds

---

### 🔹 Insulator Porcelain

![Image](https://images.openai.com/static-rsc-4/0-wfmdXpdF6x5AkzSUoHtI4b5bIpfQbmkma-yq7qccOiwzYvGdetwlgEj10VrCKqsM-_ZaA4AgWucsmrFXIdD7li-IxPugF69pOVLjKiBkpnZkWaX-ACYxDEnBfmdnfhiLy4HDh3wWWJW9YfbB6x00mzPNYl4GjtQP1HIf_jc4a3caGBk7wXNPhDCmiOY5yS?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/ck-mpgXWEFkbQY2Y4OdKwwJk_mLbU-7lbWgXpTmUpLMZzVMIVsqofUWW4ISh2-sTYsUHQ13oMh2bBOvFQDmJLeMEZwbpAmBbpXs110fA_LtQY562K3Nb_IsPei5ybg-WdYj6FtnSlT-8DFsYTyOcnSRn8VEFvJq6z_owyKQbcKsSCWFSbp54oGg3xxhsNWoV?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/nQskTWJM-oBdIsnr0ilmW8M3AQHpb_kWrztu0zP5vJmNNNFjzFIYTg8TLSjACAISasoDZ4aTfdbIPO4fQ9hLZTPaD8-g963I4rthKBDX9qsrEvpmQrZpLq0Y1H7X4_DnMFyz_dyEuBR1rTjO9MWwHDbKCCixRGCPio28VO5advTV2pny9wZggiwdr34yKnzl?purpose=fullsize)

* Light grey or off-white
* Rigid ceramic structure
* Glossy finish

---

### 🔹 Arrester Polymer

![Image](https://images.openai.com/static-rsc-4/8KgdzM2QutiXOB-dyf_lT2QjIixzOqzlKGdZ2ZB4vv_344uAWXF5_lafOlZ7Sf0ow4O5_9w9ealRCe4vojDeQ34RJxcpjGObEI13R1sHirPrcVTpRk5pAGB9duvMbTcDzVdc8g4z-xwuOyxMYmn79dHMw1O0RVObK98YWiILEOfx9r7NvaGzZdL6XYVsq0RL?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/npuef2aABk13LTFsEPZ8kjPTNx3ahENDJoNeWQka-rQ17XAvM-AJie2UUHCFei2Hga5WDG-XjwUdVFVDFICdsG23OhtzLYJxDfFLVYRPVTHS7NUVH9wMEOBCoIVohuNAmgkBhuroCHM_5VPdVJijKbuGrWD5t5Ey-Bkd-K38IZJWDhy9lUvBW138edxHNOZd?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/muUJyhJD1avPKoyv0SrDZGoKHImfAaTmitT5Z3hWxhVHWNZgWZE9PN04vJicduTT38LBEmCeOXCM6WAizbRIv2lh0BrtM3ZeTa-zOny4b9FLTDnR1mYi3-MptHRyiHbiyDEvcfaZpmQlPbhjkO7YqFmc-k594H_LpFNJNzToF6IVuSIIGFbcDeTnBv2UO0fh?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/oGlNMPEI1xHZtbv6zrAY-uQ8ZsYK1qKm0SGHzPIvxxTZRKkfQ6PUPBeHJxf3S6YW2Efrl59nXdVtrU6teIxjOF8cN8_ZaxAv60XHS0APW2ER9EmuPK6FP2DRZWLBq4rqAljNDsVkT0Pz5afC-D5NDLj9yUIL8JIWtLOErhwLdzRs9gDaMTZOZVD_1WYxYCUU?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/I4FqZG5IGn9mly20hV63MY9pmXlfib5oZ-a9yTtgIz8oVQ8Wt98EH7vjk1cOJ2ksOSQIuo6k8YJ1_auX4B2RR84_aUt131dvQ94FHc8cvp4vNWSCZHI3PTNG8jqG-y_cidCQl9_rznqx8QMOIW5Yo66L_x_qTzKcubXjZZ8Fu3BgE0xPX8N1eVV-3IvslMIa?purpose=fullsize)

* Dark rubber housing
* Typically connected between phase and ground

---

### 🔹 Arrester Porcelain

![Image](https://images.openai.com/static-rsc-4/tpeEYu42eoqNVuT7Fyp8KK8RiBxuAUkPaAbgGkM31befiBdzMQQbgfeSZSFakkAnV8ADVmj7ztjSgQbs4dQMx5cx3xLM-2DSxxctqPv3IOsNFFI6zDV_zCfvPdpobXExX1SsSB2ZbP4XYj3q0F8heZxQbTZ0Uhvj5DTeL7AaS3BjRW2Is_P4NTbc2tuYcZXZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/f4xDzbC1sg8zCunfr2B9DmPblun1oN7wbfSn76lNlXbdCE3spdmkS88l6QkJuSK7Q9BNBF_Zxc3EeMMSYWWRsUGE7UmyjG_bLGx8f9LbA1LRhHIdpGdu4CuoPQt3NkwUJAVf6xs7lSgtqGf9djKu7Se68hvV6EU_7rFOGwYsLQOlArnvQfFDBYDXN3jGkKEx?purpose=fullsize)

* Light grey ceramic housing
* Heavier, segmented sheds

---

## 📏 Annotation Rules

* Annotate **all valid objects** in each image
* Do **not annotate**:

  * Blurry or unclear objects
  * Broken or incomplete components
* Each object must have:

  * **One bounding box**
  * **One label**
* Avoid unnecessary overlap between boxes
* Maintain **consistency across all images**

---

## ✅ Quality Control

* Labels were reviewed for:

  * Accuracy
  * Consistency
  * Completeness
* Bounding boxes checked for:

  * Tight fit
  * Correct object coverage

---

## 📤 Submission

* Task completed and saved on CVAT
* Submission link provided via required form

---

## 📚 References

* CVAT Documentation
* Annotation tutorials and guides

---

## ✍️ Notes

* This task follows strict labeling conventions to ensure dataset quality for machine learning applications.
* Domain knowledge (material + function) was applied during classification.

