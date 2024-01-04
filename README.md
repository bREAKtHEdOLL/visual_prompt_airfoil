# In-Context Learning and Prompt Design for Computer-Aided Aerodynamic Engineering Application

## Introduction
Welcome to the GitHub repository for my semester project at EPFL CVLab! Here you can find the code, data, and my report for my semester project.

## Abstract
This study explores the innovative application of visual prompting via image inpainting in the field of aerodynamic shape optimization, particularly for predicting pressure fields around airfoils. Our approach utilizes a $2\times$2 grid structure comprising airfoil images and their corresponding pressure fields. This grid structure is then fed into a pre-trained universal visual model that can predict the pressure field of an unseen airfoil based on the provided example, without any task-specific fine-tuning or model modification. We conducted extensive experiments to understand the effects of various factors such as airfoil size, color schemes of the pressure field, aggregation, and the similarity of airfoils used in the visual prompts. The results indicate that larger airfoils and specific color schemes enhance the model's accuracy. Aggregation also helps improve model performance. Moreover, using similar airfoils as examples significantly improves the performance compared to dissimilar ones.

## Dataset
The datasets we need are available at https://drive.google.com/file/d/1xZvFEghGXrVrVN5sSFdSvcCZm_sySjxW/view?usp=sharing. We only need the `mesh` and `restart_csv` folders from this link. Check [UIUC Airfoil Data Site](https://m-selig.ae.illinois.edu/ads.html) to learn more about the datasets.

## Code
The main code for this work is included in the `airfoil_pressure_field.ipynb` file. To run the model, use the `model.ipynb` file (credit to https://yossigandelsman.github.io/visual_prompt/). 
