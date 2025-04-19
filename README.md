# Depression Severity Facial Action Units (AU) Feature Dataset

This dataset consists of 223,647 facial image frames with extracted Facial Action Unit (AU) intensity features. The samples are categorized into four classes representing depression severity levels: Healthy, Mild, Moderate, and Severe. The AU features were extracted using the OpenFace toolkit from clinical video recordings collected at Bahawal Victoria Hospital, Bahawalpur, Pakistan.

## 📁 File Structure

- `data/AU_features.csv` — CSV file containing 35 AU intensity features with corresponding depression severity labels.
- `docs/preprocessing_pipeline.md` — Description of data collection, preprocessing, feature extraction, and labeling process.
- `scripts/visualize_features.py` — (Optional) A script for plotting and visualizing the AU feature distribution across classes.
- `LICENSE.txt` — Dataset license under Creative Commons Attribution 4.0 (CC BY 4.0).

## 🧪 Dataset Summary

- **Total Samples**: 223,647
- **Features**: 35 Facial Action Unit (AU) intensity values (e.g., AU01_r, AU12_r)
- **Classes**:
  - `0`: Healthy Controls (13,269 samples)
  - `1`: Mild Depression (68,628 samples)
  - `2`: Moderate Depression (94,648 samples)
  - `3`: Severe Depression (47,102 samples)

## 🛠️ Recommended Use Cases

- Explainable AI for mental health diagnostics
- Depression severity prediction using interpretable machine learning models
- Clinical decision support system research
- Affective computing and facial expression analysis

## 📜 Citation

If you use this dataset in your research, please cite:

> Gilanie, Ghulam. (2025). *Depression Severity Facial Action Units (AU) Feature Dataset*. Zenodo. https://doi.org/10.5281/zenodo.15245035

## 🔐 Ethical Considerations

- All video recordings used for data extraction were obtained under proper clinical supervision and ethical approval.
- No identifiable patient information is included; only anonymized AU features are shared.

## 👨‍⚕️ Contact

**Dr. Ghulam Gilanie**  
The Islamia University of Bahawalpur, Faculty of Computing, Department of Artificial Intelligence  
Email: [ghulam.gilanie@iub.edu.pk]  
GitHub: [https://github.com/Prof-Gilanie](https://github.com/Prof-Gilanie)
