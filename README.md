# COVID-19-CAD
## Deep CNN-Based CAD System for COVID-19 Detection Using Multiple Lung CT Scans.

Due to the COVID-19  pandemic and the imminent collapse of healthcare systems following the excessive consumption of financial, hospital, and medicinal resources, the World Health Organization (WHO) changed the alert level on the COVID-19 pandemic from high to very high. Meanwhile, the world began to favor less expensive and more precise COVID-19 detection methods. Machine vision-based COVID-19 detection methods especially Deep learning as a diagnostic technique in the early stages of the disease have found great importance during the pandemic. This study aimed to design a highly efficient Computer-Aided Detection (CAD) system for COVID-19 using a `NASNet`-based model.

## Model architecture
<h1 align="center">
 <a href="https://github.com/MehradAria/COVID-19-CAD"><img src="https://github.com/MehradAria/COVID-19-CAD/blob/main/model.jpg?raw=true" alt="Deep CNN-Based CAD System for COVID-19 Detection Using Multiple Lung CT Scans."></a>
</h1>

## Train/Inference
You may use [Deep-COVID.ipynb](https://github.com/MehradAria/COVID-19-CAD/blob/main/Deep-COVID.ipynb), training is as simple as:

```shell
# Example
history = fit_model(Epochs, Callbacks, class_weight=class_weight)
```

And to predict:

```shell
# Example
classes = model.predict(images)
```

## Results:
The proposed model's performance achieved a detection sensitivity, specificity, and accuracy of 0.999, 0.986, and 0.996, respectively.
The following is the result of the detection on 25 random samples from the test set. “I” is the image index, “P” is the predicted value, and “L” is the grand truth label. Caption in green color means correct detection and red means wrong:

<h1 align="center">
 <a href=""><img src="https://github.com/MehradAria/COVID-19-CAD/blob/main/results.png?raw=true" alt="COVID-19-CAD Results"></a>
</h1>

## Conclusions:
The proposed model achieved acceptable results in the categorization of 2 data classes. Therefore, a CAD system was designed on the basis of this model for COVID-19 detection using multiple lung computed tomography scans. The system differentiated all COVID-19 cases from non–COVID-19 ones without any error in the application phase. Overall, the proposed deep learning–based CAD system can greatly help radiologists detect COVID-19 in its early stages. During the COVID-19 pandemic, the use of a CAD system as a screening tool would accelerate disease detection and prevent the loss of healthcare resources.

---
### Paper / Data / pre-trained model availability:

- The paper (Open Access): [Deep Convolutional Neural Network–Based Computer-Aided Detection System for COVID-19 Using Multiple Lung Scans: Design and Implementation Study](https://doi.org/10.2196/27468)

- Dataset is accessible via Kaggle: [COVID-19 Lung CT Scans: A large dataset of lung CT scans for COVID-19 (SARS-CoV-2) detection.](https://www.kaggle.com/mehradaria/covid19-lung-ct-scans)

> A large public COVID-19 (SARS-CoV-2) lung CT scan dataset, containing total of **8,439** CT scans which consists of 7,495 positive cases (COVID-19 infection) and 944 negative ones (normal and non-COVID-19). Data is available as 512×512px PNG images and has been collected from real patients in radiology centers of teaching hospitals in Tehran, Iran.

```
Aria, M., et al. "COVID-19 Lung CT Scans: A large dataset of lung CT scans for COVID-19 (SARS-CoV-2) detection." Kaggle (2021).
doi: https://doi.org/10.34740/kaggle/dsv/1875670.
```

- The model is not publicly available at this moment.

---
### Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:
```
Ghaderzadeh M, Asadi F, Jafari R, Bashash D, Abolghasemi H, Aria M. 
"Deep Convolutional Neural Network–Based Computer-Aided Detection System for COVID-19 Using Multiple Lung Scans: Design and Implementation Study" 
J Med Internet Res 2021;23(4):e27468
URL: https://www.jmir.org/2021/4/e27468
DOI: 10.2196/27468
PMID: 33848973
```

2) Please do not distribute the database or source codes to others without author authorization.
Authors’ Email: `mehrad.aria[at]shirazu.ac.ir` (M. Aria).
