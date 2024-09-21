# Multimodal Natural Disaster Scene Recognition with Integrated Large Model and Mamba

## Data Preparation

(1) Prepare for ImageNet dataset:


---


```markdown
/path/to/imagenet
├── images
│   ├── class1
│   │   └── img1.jpeg
│   ├── class2
│   │   └── img2.jpeg





(2)Prepare for text ansd probabilities used for training

With the help of gemini1.5, it is generated through question and answer method. The question and answer prompts are as follows：

1.prompt for text

Please describe the content of this picture in detail

2.prompt for probabilities

Use pictures to judge natural phenomena. There are eleven picture categories: hail, snow, earthquake, rain, food, wildfre, hurri-cane, lightning, sandstorm, frost, andhaze.


## Train Mamba-MDRNet with EffcientNet

run Mamba-MDRNet.ipynb
