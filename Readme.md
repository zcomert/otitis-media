#[Computerized Otoscopy Image-based Artificial Intelligence Model utilizing Deep Features Provided by Vision Transformer, Grid Search Optimization and Support Vector Machine for Otitis Media Diagnosis](https://link.springer.com/article/10.1007/s00521-024-10457-y)

### Dataset Description

#### Overview

The dataset used in this study comprises otoscope images collected from the Department of Otorhinolaryngology at the Clinical Hospital of the Universidad de Chile. It consists of images from 180 subjects aged 7 to 65 years, each diagnosed with one of four otoscopic conditions: chronic otitis media (COM), myringosclerosis, earwax plug, or normal otoscopy.

#### Data Collection

- **Equipment:** DE500 Firefly digital otoscope
- **Resolution:** 640×480 pixels
- **Frame Rate:** 20 frames per second (fps)
- **Region of Interest:** Eardrum region cropped to 420×380 pixels

#### Dataset Structure

The dataset is divided into training and testing subsets with equal representation across four diagnostic categories. The distribution is as follows:

| Class                | # of Training Samples | # of Testing Samples | Total Samples |
|----------------------|-----------------------|----------------------|---------------|
| Chronic Otitis Media | 180                   | 40                   | 220           |
| Myringosclerosis     | 180                   | 40                   | 220           |
| Earwax Plug          | 180                   | 40                   | 220           |
| Normal               | 180                   | 40                   | 220           |
| **Total**            | **720**               | **160**              | **880**       |

#### Ethical Considerations

- **Ethical Approval:** The dataset creation followed approved ethical guidelines.
- **Consent:** All participants provided informed consent for their data to be used in the study.

#### Data Preparation

- **Frame Selection:** Frames were selected based on a blur threshold to ensure quality.
- **Image Processing:** The region of interest containing the eardrum was isolated and cropped.

#### Diagnostic Categories

1. **Chronic Otitis Media (COM):** Persistent inflammation of the middle ear often accompanied by recurrent ear discharge and hearing loss.
2. **Myringosclerosis:** Formation of white patches or plaques on the eardrum due to repeated episodes of inflammation or infection.
3. **Earwax Plug:** Accumulation of earwax blocking the ear canal.
4. **Normal:** No signs of inflammation, infection, or other irregularities.

#### Key Features

- **Balanced Representation:** Equal number of samples across all classes ensures unbiased training and evaluation.
- **High-Quality Images:** Selection based on quality criteria to maintain high data standards.
- **Ethical Compliance:** Adherence to ethical standards and participant consent.

This dataset is publicly accessible and serves as a robust foundation for training and evaluating machine learning models for the automated diagnosis of otitis media and related conditions.

**Related paper** 

M. Viscaino, J.C. Maass, P.H. Delano, M. Torrente, C. Stott, F. Auat Cheein, Computer-aided diagnosis of external and middle ear conditions: A machine learning approach, PLoS One. 15 (2020) e0229226. https://doi.org/10.1371/journal.pone.0229226.
