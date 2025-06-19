# Overview
This repository contains the source code for training the imagen model for generating anime faces. 
The labeling notebook generates, for each image, a list of attributes (for example a list ["smug", "red hair", "blue eyes"] and saves this information together with the corresponding image. Each image-label pair is then used as input to the Imagen model, which learns to produce anime-style images conditioned on the given labels.
