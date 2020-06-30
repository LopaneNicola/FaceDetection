# FaceDetection
## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#Setup)
* [Related Work](#Related-Work)

## General info
Effettuare un confronto tra il modello VGGFace (basato su VGG16) ed il modello VGGFace (basato su ResNet50),
andando ad addestrare i due modelli, usando come dataset FER2013, seguendo un approccio Dense-Sparse-Dense e 
confrontando i risultati ottenuti.

## Technologies
Lista dei packages più importanti utilizzati in questo progetto:

* Keras versione 2.3.1
* opencv-contrib-python versione 3.4.2.16
* opencv-python versione 3.4.2.16
* scikit-learn versione 0.23.1
* tensorflow versione 2.1.0

## Setup
Per avviare lo script, seguire i seguenti passaggi:

* Scaricare il dataset di FER2013 dal seguente link https://www.kaggle.com/deadskull7/fer2013.
* Inserire il dataset in una cartella vuota e denominarla "data".
* Clonare il repository GitHub ed aggiungere la cartella "data".
* Installare i packages necessari attraverso il comando "pip install requirements.txt".
* Eseguire il file Image_Classification per estrarre le immagini dal FER2013.
* Eseguire i file FaceDetectionvggFACE e FaceDetectionResnet per addestrare i due modelli.
* A training concluso, eseguire il file FD_realTime per avviare il riconoscimento delle emozioni del volto in tempo reale.

## Related Work
M. I. Georgescu, R. T. Ionescu e M. Popescu, "Local Learning With Deep and Handcrafted
Features for Facial Expression Recognition", May 16, 2019.
