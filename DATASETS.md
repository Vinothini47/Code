
# 📊 Dataset Description for COVID-19 Severity Detection

This project utilizes four publicly available datasets to train, validate, and evaluate the performance of the proposed FRCNN-GJS model for automatic COVID-19 severity prediction from CT scans.

---

## 1. COVID-19 CT Scan Dataset

- 📁 **Source**: [Kaggle - COVID19 CT Scans](https://www.kaggle.com/datasets/andrewmvd/covid19-ct-scans)  
- 📈 **Total Images**: 12,058 CT slices  
- 🧪 **Classes**: COVID-19 positive and Normal (non-COVID)  
- 🏥 **Origin**: Negin Medical Center, Sari, Iran  
- 🗓️ **Collection Period**: March 5 – April 23, 2020  
- ✅ **Ethics**: Patient data anonymized; follows data-sharing regulations  
- 📝 **Reference**: Jangam et al., 2022  

This dataset is especially useful for deep learning applications in clinical environments where radiologists are limited.

---

## 2. LUNA16 Dataset

- 📁 **Source**: [Kaggle - LUNA16](https://www.kaggle.com/datasets/avc0706/luna16)  
- 📈 **CT Scans**: 888 CT scans  
- 🫁 **Focus**: Lung nodule detection (non-COVID-specific)  
- 🧑‍⚕️ **Annotations**: 1,186 nodules evaluated by expert radiologists  
- 🏛️ **Organizations**: Lung Image Database Consortium (LIDC), American College of Radiology (ACR)  
- ✅ **Ethics**: Anonymized patient data; Institutional approvals  
- 📝 **Reference**: Bhattacharyya et al., 2023  

This dataset supports model generalization by introducing diverse lung CT characteristics.

---

## 3. COVID-CT Dataset

- 📁 **Source**: [Papers with Code - COVID-CT](https://paperswithcode.com/dataset/covid-ct)  
- 📈 **Total Images**: 812 (349 from COVID-positive, 463 from control group)  
- 🧑‍🤝‍🧑 **Patients**: 271 total (216 COVID-19 patients)  
- 🧾 **Metadata**: Age, gender, location, scan date, severity level, and medical notes  
- 🏥 **Sources**: Scientific articles (medRxiv, bioRxiv) + hospital donations  
- ✅ **Ethics**: Data anonymized and ethically approved  
- 📝 **Reference**: Jangam et al., 2022  

Images are extracted using PyMuPDF, with manual validation of metadata, offering enriched data for training.

---

## 4. SARS-CoV-2 CT Dataset

- 📁 **Source**: [Kaggle - SARS-CoV-2 CT-scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)  
- 📈 **Total Images**: 2,482 CT scans  
- 🧑‍🤝‍🧑 **Patients**: 120 (60 positive, 60 negative)  
- 👨‍⚕️👩‍⚕️ **Demographics**: Balanced gender (32M/28F infected, 30M/30F uninfected)  
- 🏥 **Origin**: São Paulo hospitals, Brazil  
- ✅ **Ethics**: Full anonymization and institutional clearance  
- 📝 **Reference**: Jangam et al., 2022  

This dataset is crucial for robust model evaluation due to its balanced design and demographic clarity.

---

## 📌 Usage Note

All datasets used in this study are open-source and licensed for academic use. Please check the individual dataset licenses on their respective links before commercial use.

