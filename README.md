# AutoTrain_ImageClassify_model_ByYOLOv5
![GitHub](https://img.shields.io/github/license/ZYM66/AutoTrain_ImageClassify_model_ByYOLOv5)  
Auto generate dataset  
Auto train models by YOLOV5

## Colab website
https://colab.research.google.com/github/ZYM66/AutoTrain_ImageClassify_model_ByYOLOv5/blob/master/Yolov5.ipynb

## Why use this?
  
  Most problems we meet in our daily life is the simple image classify problem.Although it's easy to train, we still spend a lot of time in dataset searching, model training and so on.To help us quickly establish the dataset and train our dataset, I write this notebook.The user who want to train their own image classify model can use this notebook to make the train effiently.
 
## How to use?
  It's extremely simple to use this.User only need to modify the **search_terms**.
  For example, if we want build a model that can identify the 
  > "郁金香", "月季", "红玫瑰", "白玫瑰", "绿萝", "蝴蝶兰 ", "康乃馨", "杜鹃花", "万年青", "薰衣草", "水仙花", "梅花", "马蹄莲", "君子兰", "金银花", "鸢尾花", "百合花", "昙花", "天竺葵", "牡丹花"
  
  We just write down in the search_terms and the notebook will auto establish the dataset from the image search API.
  Then we use YOLO command line to train this model.
## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ZYM66/AutoTrain_ImageClassify_model_ByYOLOv5&type=Date)](https://star-history.com/#ZYM66/AutoTrain_ImageClassify_model_ByYOLOv5&Date)
## LICENSE
MIT
