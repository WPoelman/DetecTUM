# DetecTUM

This is the system submission of team DetecTUM for the CLIN-33 shared task on machine-generated text detection.
The tasks consisted of binary classification of texts in Dutch and English spanning several domains.
More information can be found here:

* CLIN-33: https://clin33.uantwerpen.be/
* Shared Task: https://sites.google.com/view/shared-task-clin33/home
* Slides: https://wesselpoelman.nl/files/clin_2023_slides.pdf

Our submission mainly focused on characterizing the difference (if there was any) between human- and machine-generated texts.
To this end, we focused on creating cross-lingual and cross-domain features.
This final system came second in the shared task for both languages.
The question whether our approach to the detection task, and even the task itself, is feasible, generalizable, and reliable is an open question.

We have not included all experiments, this is the skeleton setup for our system and analysis.

## Installation
1. Use with Python 3.10 (due to [trankit](https://github.com/nlp-uoregon/trankit/issues/76))
2. `pip install -r requirements.txt`
3. Get the data from the shared task organizers, due to copyright reasons, we cannot distribute them.
4. Run the notebook.

## Participants
- Esther Ploeger, Aalborg University
- Juraj Vladika, Technical University of Munich
- Wessel Poelman, Technical University of Munich & KU Leuven
