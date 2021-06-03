# COVID-19-CAD
Deep CNN-Based CAD System for COVID-19 Detection Using Multiple Lung CT Scans.

Due to the COVID-19  pandemic and the imminent collapse of healthcare systems following the excessive consumption of financial, hospital, and medicinal resources, the World Health Organization (WHO) changed the alert level on the COVID-19 pandemic from high to very high. Meanwhile, the world began to favor less expensive and more precise COVID-19 detection methods. Machine vision-based COVID-19 detection methods especially Deep learning as a diagnostic technique in the early stages of the disease have found great importance during the pandemic. This study aimed to design a highly efficient Computer-Aided Detection (CAD) system for COVID-19 by using a NASNet-based model.

Code is available in [this notebook](https://github.com/MehradAria/COVID-19-CAD/blob/main/Deep-COVID.ipynb).

![COVID-19-CAD Model](https://github.com/MehradAria/COVID-19-CAD/blob/main/model.png?raw=true)

Results of detection on 25 random samples from the test set. “I” is image index, “P” is predicted value and “L” is grand truth label. Caption in green color means correct detection and red means wrong:

![COVID-19-CAD Results](https://github.com/MehradAria/COVID-19-CAD/blob/main/results.png?raw=true)


We also made available a large public COVID-19 (SARS-CoV-2) lung CT scan dataset, containing total of **8,439** CT scans which consists of 7,495 positive cases (COVID-19 infection) and 944 negative ones (normal and non-COVID-19). Data is available as 512×512px PNG images and have been collected from real patients in radiology centers of teaching hospitals of Tehran, Iran. The aim of this dataset is to encourage the research and development of effective and innovative methods such as deep CNNs which are able to identify if a person is infected by COVID-19 through the analysis of his/her CT scans. As a baseline for this dataset we used a CNN-based approach inspired by transfer learning which we could achieve an accuracy of 99.61% which is very promising.

Dataset is also available at: [https://www.kaggle.com/mehradaria/covid19-lung-ct-scans](https://www.kaggle.com/mehradaria/covid19-lung-ct-scans)

You may access the related paper at: [Deep Convolutional Neural Network–Based Computer-Aided Detection System for COVID-19 Using Multiple Lung Scans: Design and Implementation Study](https://doi.org/10.2196/27468)

Please kindly cite as:
`Ghaderzadeh M, Asadi F, Jafari R, Bashash D, Abolghasemi H, Aria M. 
"Deep Convolutional Neural Network–Based Computer-Aided Detection System for COVID-19 Using Multiple Lung Scans: Design and Implementation Study" 
J Med Internet Res 2021;23(4):e27468
URL: https://www.jmir.org/2021/4/e27468
DOI: 10.2196/27468
PMID: 33848973`


`Ghaderzadeh M, Asadi F, Jafari R, Aria M. "COVID-19 Lung CT Scans: A large dataset of lung CT scans for COVID-19 (SARS-CoV-2) detection." Kaggle (2021). DOI: 10.34740/kaggle/dsv/1875670.`
