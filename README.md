Research plan: General-purpose brain tumor segmentation and classification model
using machine learning methods.
Abstract
These days, a leading cause of death worldwide is cancer accounting for 10 million deaths in 20201
.
Especially brain cancer, one of the deadliest types of cancer, is a bigger threat to humanity. For
instance, glioblastoma, one of the deadliest types of cancer has a 22% survival rate for patients
with 20-44 age according to the American Cancer Society. In Mongolia, 1.2 percent of total cancerdiagnosed male patients have brain and nervous system cancer2
. The number may appear low, but
the population is nearly 3.4 million thus it is still a concerning number. In the case of Japan, the
mortality rate of brain cancer has been also increasing according to the National Cancer Center
Japan3
. Thus, early detection and diagnosis of malignant brain tumors are necessary.
Main
Brain tumor segmentation and classification whether the tumor is malignant or benign is a crucial
task in medical image processing. Early diagnosis of brain tumors impacts greatly a patient’s
survival rate and treatment options. Especially diagnosing in the early 5 years is important because
a great number of people know after 5 years or higher, reducing the lifespan and leaving not an
adequate amount of time and choice of treatments. Brain segmentation can be classified as manual
segmentation, semi-automatic segmentation, and fully-automatic segmentation. Manual
segmentation can be a difficult and time-consuming process. In recent years, fully-automatic
segmentation based on deep learning techniques using MRI-based image data proved popular
because it has been showing better performance than other methods. Although there are other
imaging techniques, MRI showed greater results due to its better differentiation between factors
such as better soft tissue contrast. There are other imaging techniques such as Diffusion tensor
imaging, which is an MRI method that visualizes the direction and flowability of water molecules,
providing information about white matter tracts 4
. Traditional MRI methods do not give any
information about the structure of connectivity of brain regions thus DTI technique provides
information that is not obtainable from MRI. Also, there are multiple traditional imaging
techniques such as CT scan, PET scan, Ultrasound, etc. The purpose of this research is to practice
and implement machine learning methods to these imaging techniques and build a general-purpose
model which can take any type of image that is used in modern medicine as input and classify
whether the brain tumor is benign or malignant and segment the tumor area from the image
regardless of the imaging technique and finally implement it as a software for applications for reallife uses in clinics and institutions.
1
Ferlay J, Ervik M, Lam F, Colombet M, Mery L, Piñeros M, et al, "Global Cancer Observatory: Cancer Today."
2
“GLOBOCAN 2020 Mongolia Factsheet.”
3
“Cancer Statistics in Japan; Table Download：[国立がん研究センター がん統計].”
4 Pierpaoli et al., “Diffusion Tensor MR Imaging of the Human Brain.”
Summarized steps of the research:
1. Data collection: Collect a large and diverse amount of images from multiple techniques
such as MRI, DTI, PET, CT, etc. with the correct label from various valid sources (Potential
dataset sources: The Cancer Imaging Archive (TCIA) dataset, The Ischemic Stroke Lesion
Segmentation (ISLES) dataset, The Brain Tumor Segmentation Challenge (Brats) dataset,
etc.)
2. Pre-processing data: Perform various image processing techniques to get rid of noise
3. Feature extraction: Extract useful features for classification
4. Training model: Train the machine learning model using extracted features to classify and
segment the tumor area.
5. Evaluation: Measuring the model’s performance using various metrics.
6. Optimization: Optimizing the model by improving architectures and features.
7. Improve the model using other different model features and methods.
8. Implement the model into software for real-life applications such as clinics and institutes.
Conclusion
The application of a general-purpose model for brain tumor classification and segmentation has
the potential to improve diagnosis accuracy and efficiency in real-life clinics and institutes. The
ability to take any kind of imaging that is used in modern medicine as input and classify whether
the brain tumor is malignant or benign and segment the tumor area from the image can be useful
for clinicians and radiologists thus leading to better patient outcomes in real-life situations.
However, some challenges need to be aware of in order to implement the practical model. One of
the main issues is the model has to be generalized and loses no accuracy regardless of the input
image. This requires a large and diverse amount of dataset images from multiple valid sources.
Another challenge is to ensure that the model has to be easy to use and interpretable for
clinicians, radiologists, experts, and potential patients. Last but not least, the model should be
tested in real clinics to evaluate its performance and accuracy.
+ Additional improvements: real time training, updating?
References
(1) Ferlay J, Ervik M, Lam F, Colombet M, Mery L, Piñeros M, et al. Global Cancer
Observatory: Cancer Today. Lyon: International Agency for Research on Cancer; 2020
(https://gco.iarc.fr/today, accessed February 2021).
(2) International Agency for Research on Cancer. (n.d.). GLOBOCAN 2020 Mongolia
factsheet. Retrieved from https://gco.iarc.fr/today/data/factsheets/populations/496-
mongolia-fact-sheets.pdf.
(3) Vital Statistics in Japan, tabulated by Cancer Information Service, National Cancer Center,
Japan.
(4) Pierpaoli, C, P Jezzard, P J Basser, A Barnett, and G Di Chiro. “Diffusion Tensor MR
Imaging of the Human Brain.” Radiology 201, no. 3 (December 1996): 637–48.
https://doi.org/10.1148/radiology.201.3.8939209.
