# Hierarchical Fusion Network with Manifold Learning for Multimodal Humor Recognition on Memes
📜This is the dataset for our paper `Hierarchical Fusion Network with Manifold Learning for
Multimodal Humor Recognition on Memes`

## 1.1 Dataset Construction Process
We use crawler programs to collect the data required for our experiments from the current mainstream communities.
We use #meme and #memes as our search keywords. We use [Baidu AI](https://ai.baidu.com/tech/ocr/general) and [iFlytek API](https://www.xfyun.cn/services/common-ocr) to perform Optical Character Recognition(OCR) on the obtained images to obtain the captions in memes. 
<br>
<br>

![data (1)](https://github.com/DericWmy/HuME/assets/102895417/72fb7d03-8cb9-4f5c-9c9b-3eaae423b907)

***

## 1.2 Annotation Process
 ### 1.2.1 Pre Annotation
 In this step, we collected 200 memes and distributed them to all the annotators and asked them
to watch each meme according to pre-specified principles, and then gave humorous labels for each meme. In addition,
we also asked the annotators provided None tags for them to mark questionable humor labels when pre-labeling. For
questionable memes, the labelers need to explain the basis for their judgment of whether such memes are humorous or
not. After further discussion, according to the consistency requirements of the rules , the final humor label is determined
based on the majority rule. 
 ### 1.2.2 Formal Annotation
  After achieving a reasonable consensus among all annotators, we proceed to the formal
annotation phase. We distribute all memes to annotators, instructing them to perform the labeling task strictly according
to the prescribed guidelines. The majority vote is then employed to determine the gold label, which is subsequently
integrated into the entire dataset.
***
## 1.3 Dataset Statistics
We divided the experimental data into training, validation,
and test sets in a ratio of 80%:10%:10%, ensuring a consistent distribution of positive and negative samples. All statistics of this data set are shown in the table.

 Dataset  | Train  | Valid  | Test  | Total
 ---- | ----- | ------ | ------ | ------  
 Humorous  | 4,831 | 604  | 604  | 6,039
 Non Humorous  | 3,660 | 451  | 450  | 4,561
***
 ## 1.4 Dataset Link
The data can be obtained through link https://pan.baidu.com/s/1975K5hqanjBCQUtLdFK2Pw <br>
code: arvq.
 
