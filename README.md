# Cancer Image Analysis Competition Overview

Welcome to the Cancer Image Analysis Competition! In this competition, you will be working with histopathological images to complete a series of tasks designed to assess your skills in mainly: image classification, generative networks, and graph-based networks ( don't wory if you've not used GANs or GNN you can try an approach of your own or learn it and use it )
Feel free to use ANY TOOL, ANY AI, ChatGPT and whatever you want as you wish :)

## Tasks
Simple tasks, don't spend any time on these, copy code online instead
1. **Load, preprocess, and augment data**
2. **Classify images as cancerous or non-cancerous**
   
Complex tasks that will be evaluated based on approach (not acuracy not any other metric)
3. **Generate cancerous images from non-cancerous images using generative networks**
4. **Utilize Graph Convolutional Networks (GCNs) to analyze nucleus features**

## Important Information
- **Submission Deadline:** Before Friday
- **Platform:** Google Colab
- **Dataset:** [Histopathological Cancer Detection - Cropped](https://drive.google.com/drive/folders/1T4De029U-OJAEEHCbym_efc2mdFox6S5?usp=sharing)
(Additionally can be found on kaggle https://www.kaggle.com/datasets/drbeane/hcd-cropped/data)
- **Code Examples for task 1,2 :** [Kaggle Code Examples](https://www.kaggle.com/datasets/drbeane/hcd-cropped/code)
- **Reference Paper** (needed for step 4 and maybe 3): [Learning Shape-Aware Features with Generative Models for Nuclei Classification](https://arxiv.org/abs/2302.11416)
- **Reference Code from the paper:** [SENUCLS](https://github.com/Lewislou/SENUCLS/tree/main)

## Evaluation Criteria

The evaluation for this assignment is **not based on accuracy** or **performance metrics** but on **how you approach the problem**. Since the problem statement is very abstract and can be solved in multiple ways, your methodology and creativity are key.
Networks
## Tasks Details 

### Task 1: Load, preprocess, and augment data

Use only 500 samples from the training data, idc about the accuracy and performance so don't waste time on that :)

### Task 2: Classify if the image is cancerous or non-cancerous

Use any classification model of your choice. Don't spend too much time on this; focus on the approach **after step 2.**

### Task 3: Generate cancerous images from non-cancerous images using generative networks
Here's where the competition begins,
Use Any type of generative network (i'd prefer gans & diffusion models) to take the NON CANCEROUS images as input and generate an output of how this image would look like if it was cancerous. 
(eg: Non-cancerous image -> GAN -> Cancerous image)
Don't focus on tuning the gan and increasing the accuracy I will mainly evaluate the approach.



### Task 4: Utilize Graph Convolutional Networks (GCNs) to analyze nucleus features

Incorporate strategies from the reference paper and,
Utilize GCN / graph based networks.
The key idea is to learn nucleus features based on structure, texture, and edge at the nuclei level first and then move to inter-nuclear graphs (see paper;mentioned above).


## ** Important Note. **
Now i get that this might be too much to process but take your time, use any AI or reference or tool you want to and *please please please* dont focus on accuracy or metrics (this doesnt mean that you get reckless metrics but the bare minimum would work, dont tune the results instead focus on the approach), I want to evaluate your approach. If you've completed everything and have time before friday then sure feel free to improve the metrics for brownie points.



