![banner](https://raw.githubusercontent.com/Tayyab885/Tayyab885/main/banner.png)

<h1 align="center">Hi, I'm Muhammad Tayyab</h1>
<h3 align="center">Machine Learning Engineer, working on AI for medical imaging</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-tayyab885/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://kaggle.com/muhammadtayyab885"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
  <a href="https://muhammadtayyab-my-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:m.tayyab273@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=tayyab885&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
</p>

---

### About me

I train deep learning models on medical images and spend most of my time on how they get
measured. Several of the projects below started as a published pipeline that reported a
good number, and the work was finding out how much of that number came from the way the
data was split. Two of them ended with a lower score than the version I started from,
which is the point.

The recurring themes are leakage-free splits, testing on a dataset the model never saw,
per-subgroup metrics, and Grad-CAM when a prediction needs to be explained rather than
just scored. I use PyTorch, TensorFlow, and scikit-learn, and I train on a 6GB laptop GPU
or Kaggle when the dataset is too big for it.

I am looking for research work and graduate study in medical imaging. Email is
m.tayyab273@gmail.com.

---

### Research projects

| Project | Question it answers | Result |
| --- | --- | --- |
| [Lung field segmentation across unseen sources](https://github.com/Tayyab885/chest-xray-lung-segmentation) | Does a lung segmentation model hold up on a chest X-ray source it never trained on? | Leave-one-dataset-out over three public sources. Off-domain Dice stays between 0.93 and 0.97, so transfer mostly holds. On the one hard fold, HD95 is three to four times worse while Dice barely moves, which is a boundary failure the overlap metric hides. |
| [Chest X-ray fairness audit](https://github.com/Tayyab885/Chest-Xray-Fairness-Audit) | Which patients does a 14-pathology DenseNet121 serve worse than the average? | Patient-level splits, macro AUROC 0.801. The age gaps are much larger than the sex gaps. Group-balanced resampling was tried as a fix and the writeup reports where it failed to close the gap. |
| [Brain tumor MRI classification](https://github.com/Tayyab885/Brain-Tumor-Classification-Using-CNN) | How much of a published accuracy belongs to the split rather than the model? | Removing a train/test leak took 89% down to 79% and uncovered a glioma collapse. The same pipeline on a cleaner dataset reaches 94% and the collapse goes away, so the failure was a dataset artifact, not an architecture problem. |
| [Lip reading with Conv3D-BiLSTM-CTC](https://github.com/Tayyab885/Lip-Reading-Project-Using-Deep-Learning) | What does the model score once you actually measure it? | WER 1.7% and CER 0.71% over 995 GRID clips, with the caveat printed next to it: one speaker only, so it does not compare to LipNet's cross-speaker numbers. |

---

### Tech stack

Machine learning and imaging
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

Engineering
<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
