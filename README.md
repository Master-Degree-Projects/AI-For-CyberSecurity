# Artificial Intelligence For Cybersecurity Project


## Introduction
This project implements and evaluates malware detection systems using machine learning and deep learning approaches. We compare their performance and assess vulnerability to adversarial attacks.
### Key Componets
- Implementation of ML and DL classifiers for malware detection
- Training and validation on Dataset 1, generalization testing on Dataset 2
- Robustness evaluation using GAMMA attack framework on 100+ malware samples
- Analysis of potential defense mechanisms

Our methodology includes feature extraction, model training, performance evaluation across datasets, and adversarial testing with varying attack parameters to provide insights into the security limitations of ML-based malware detection systems.

_**More details about the choices made can be found in the `report.pdf` file.**_

## Authors and Acknowledgment
Project contributors:
- **[Mariniello Alessandro](https://github.com/alexmariniello)**
- **[Pepe Paolo](https://github.com/paolopepe00)**
- **[Rabasca Dario](https://github.com/Dariorab)**
- **[Vicidomini Luigi](https://github.com/luigivicidomini)**

Thank you to all the contributors for their hard work and dedication to the project.

# How To Execute
> [!IMPORTANT]
> To replicate the experiment, you must download the dataset. [LINK](https://drive.google.com/file/d/19yu5mKhqqOERdkpgN00AI_bNTFgDAB7q/view?usp=sharing)
> We are not responsible if your system gets infected.

> [!CAUTION]
> The samples are malware and you must avoid executing them. If using Colab, be cautious, as it may lead to a ban.


The delivery contains the following files and folders:
- **Machine learning model** folder that contains:
    - **extracted_features**: a folder containing all the features extracted for the training and validation of the models;
    - **models**: a folder containing some of the model trained during this
    phase;
    - **GAMMA attack**: a folder containing the results of the GAMMA attack
    and a zip file of the malware used during the attacks;
    - **handcrafted_training_and_test.ipynb**: python notebook containing
    all the procedures used to train and validate the models and also a
    feature analysis section;
    - **handcrafted_vs_GAMMA_attack.ipynb**: python notebook containing
    all the procedures used for the GAMMA attacks;

- Deep learning model folder that contains:

    - **models**: a folder containing some of the model trained during this
    phase;
    - **GAMMA attack**: a folder containing the results of the GAMMA attack
    and a zip file of the malware used during the attacks;
    - **deep_training_and_test.ipynb**: python notebook containing all the
    procedures used to train and validate the models and also a feature
    analysis section;
    - **deep_vs_GAMMA_attack.ipynb**: python notebook containing all the procedures used for the GAMMA attacks;

