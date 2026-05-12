# Speech NLP Classification


## C'est quoi ce projet ?
Classification de données vocales via un pipeline Speech-to-NLP (en combinant Speech Processing et NLP)
L'idée est de transcrir des audios en texte, puis d’appliquer des modèles NLP pour effectuer une tâche de classification.

## Pipeline
1. Audio puis Transcription puis preprocessing puis feature extraction et enfin classification

## Modèles implémentés
- Baseline : TF-IDF + Régression Logistique
- Features audio :  Random Forest
- Deep Learning : BiLSTM (TensorFlow/Keras) et BERT pour le fine-tuning

## Dataset
Dataset utilisé : ...
Type : données vocales avec transcriptions
Langue : anglais
Taille : 

## Évaluation
Les modèles sont évalués avec : Accuracy ; F1-score et matrice de confusion

## Auteure
Fait par Maram Sall Gueye dans le cadre d'une préparation pour mon summer

## Installation
pip install -r requirements.txt
# speech-nlpclassification
