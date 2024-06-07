# Cancer Image Analysis Competition Overview

## Submission link Before saturday EOD https://forms.gle/9FycfXsSXgD9Hmuo7

Welcome to the Cancer Image Analysis Competition! I'm hosting this to select some people for the hepatoma project in which we will be working with Task 1: Construct **Graph** based networks to extract **nucleus specific information** to make classification inferences.
task 2: Downstream task to use a **generative network** to generate cancerous versions of the non cancerous images.

Feel free to use ANY TOOL, ANY AI, ChatGPT and whatever you want as you wish :)

## Tasks
These tasks will be evaluated based on approach (not acuracy not any other metric so it ** DOES NOT MATTER IF THE SOLUTION IS ACCURATE OR NOT** due to the time constrain) 

Use only 500 samples from the training data, the accuracy and other metrics don't matter as long as it's minimal so don't waste time on that :)

1. **Utilize Graph Based Networks (GNNs) to analyze nucleus features**, Incorporate strategies from the reference paper and,
Utilize GNNs 
The key idea is to learn nucleus features based on structure, texture, and edge at the nuclei level first and then move to inter-nuclear graphs (see paper;mentioned above).<br>
2. **Generate cancerous images from non-cancerous images using generative networks**: Use Any type of generative network (i'd prefer gans / diffusion models) to take the NON CANCEROUS images as input and generate an output of how this image would look like if it was cancerous. 
(eg: Non-cancerous image -> GAN -> Cancerous image)<br>

(Don't focus on tuning the gan and increasing the accuracy)<br>

yes i know this sounds counterproductive but for the main project you will be required to *generate* the next stage of the cancer from the current stage using GAN so this is why this task is important <br>

## Important Information
- **Submission Deadline:** Before Friday
- **Platform:** Any Jupyter notebook (I'd suggest link the data to collab and utilize the free gpu there, although you wont need it much)
- **Dataset:** [Histopathological Cancer Detection - Cropped](https://drive.google.com/drive/folders/1T4De029U-OJAEEHCbym_efc2mdFox6S5?usp=sharing)
(Additionally can be found on kaggle https://www.kaggle.com/datasets/drbeane/hcd-cropped/data)
- **Reference Paper** (Utilize the techniques form this paper): [Learning Shape-Aware Features with Generative Models for Nuclei Classification](https://arxiv.org/abs/2302.11416)
- **Reference Code from the paper above:** [SENUCLS](https://github.com/Lewislou/SENUCLS/tree/main)

## Evaluation Criteria

The evaluation for this selection is **not based on accuracy** or **performance metrics** but on **how the problem is approached**. Since the problem statement is very abstract and can be solved in multiple ways, your methodology and creativity are key :)




