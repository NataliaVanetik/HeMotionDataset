# HeMotionDataset
Emotions dataset (Hebrew) based on Plutchik's emotion classification (8 main emotions)

Fine-grained emotion detection for Hebrew remains underexplored due to the lack of publicly available annotated resources. 

This repository contains HeMotion, a manually annotated dataset for fine-grained emotion detection in Hebrew, based on Plutchik’s eight basic emotion categories: Joy, Trust, Fear, Surprise, Sadness, Disgust, Anger, and Anticipation. It is a manually annotated and balanced Hebrew dataset for emotion classification based on Plutchik’s eight-emotion model, consisting of 670 sentences.

Each entry includes a Hebrew sentence labeled with an emotion, along with its English translation to support multilingual research and cross-lingual modeling.

📁 Dataset Format

The dataset is provided as an Excel file (.xlsx) with the following columns:

**Column**	**Description**

ID:     running text ID

author:	Identifier of the annotator or source group (fully anonymized)

label:	  Emotion category (Plutchik-based)

text:	  Original Hebrew sentence

translation:	English translation of the sentence (when available)

** Prompting **
We also supply here (as screenshots) the zero shot prompt we used for evaluation and sentences used to turn it into a few-shot prompt.

