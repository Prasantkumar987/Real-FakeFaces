
# Real Fake Face Image Classifier - "ArtificialFaces"

This Project has been created to classify the faces which are Real or Fake (generated by GAN). To be precise, the StyleGAN2 architecture generates the faces at an exceptional level producing these results indistinguishable from real photographs. But when I observed lots of very finely generated faces and observed some indications

Some key indications these pictures were generated are:

* Out-of-focus, non-descript backgrounds
* Only a single person in frame
* Odd artefacts, such as earrings merging with ears
* The identical positioning of the eyesThis is primary reason to
<br>

This is my inspiration to create this project. This Classifier can be used in differentiating Fake Account Photo on LinkedIn and other social media platfoms.

For this project work and with the [kaggle](https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection) dataset, a Real-Fake face classifier is developed using several approaches: *Convolutional Neural Networks* (CNN) and Transfer Learning with and without face cropping using the *Multi-Task Cascaded Convolutional Neural Networks* (MTCNN).

This is a real-fake face classifier built with convolutional neural networks. The classifier was trained on a
data set comprised of 1400 images (700 of each class) and tested on 600 images (300 per class). The classifier
achieved an accuracy of **83%**.

To extend this Project, and in order to leverage the created models, a Web Application is developed using the [```streamlit```](https://streamlit.io/) framework. For more information about the models or the project, check out the [```Project Notebook```](https://github.com/Prasantkumar987/Real-FakeFaces/blob/master/RealFake_faces_classification.ipynb) in the root directory of this repository. The application source code is in the [```app```](https://github.com/Prasantkumar987/Real-FakeFaces/tree/master/app) folder.

## View the web app live
Click [here](https://prasantkumar987-real-fakefaces-appapp-kl0mv2.streamlitapp.com/) to go to the app page.

https://user-images.githubusercontent.com/54981696/189492306-41a04efc-539f-46de-8d5b-16d9726c03ad.mp4

## Run the app locally

Open a terminal and start by cloning the project repository

```bash
  https://github.com/Prasantkumar987/Real-FakeFaces.git
```

Go to the project directory

```bash
  cd Real-FakeFaces
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server (Linux / MacOS)

```bash
  streamlit run app/app.py
```

Start the server (Windows)

```bash
  streamlit run app\app.py
```

If the browser window does not open automatically when the ```streamlit run``` command is executed, you can manually navigate to ```localhost:8501```
To terminate the application, go back to the terminal and shutdown the server by pressing ```CTRL + C```.

## App Snapshot

<p align="center">
  <img src="https://github.com/Prasantkumar987/Real-FakeFaces/blob/master/app-snap/app_snapshot.png">
</p>
