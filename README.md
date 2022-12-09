# 虚拟主播数据集(Vtuber-Vup-Dataset)
## 项目介绍(Project Introduction)
  - 这是一个Vtuber和Vup（即虚拟主播）的目标检测（yolov）数据集仓库，包括18名Vtuber/Vups。  
  - 数据集由小阳（我）建立并开源，数据来源是互联网以及各大主播在Bilibili的动态图片。  
  - This is a warehouse of object detection (yolov) datasets for Vtuber and Vup (i.e., virtual streamers), including 18 Vtuber/Vups.  
  - The dataset was built and open source by Xiaoyang小阳 (I), and the data source is the Internet and the dynamic pictures of these Vtuber/Vups on Bilibili.  
## 使用范例(Usage examples)  
  - 您可以将本数据集用于训练任意的目标检测模型，具体的训练方法请参考对应的模型介绍。  
  - 以下是虚拟主播目标检测示例，采用yolov5m模型进行检测。 
  - You can use this dataset to train any object detection model, please refer to the corresponding model introduction for specific training methods.
  - The following is an example of Vtuber/Vups anchor target detection, which is detected using the Yolov5m model.  
### 顾子韵GZY 
![Image text](https://raw.githubusercontent.com/JiaXinSugar-114514/Vtuber-Vup-Dataset/main/gzy.jpg)
## 数据集介绍(Introduction to datasets)
### 数据集格式(Dataset format)  
  - 采用labelimg软件进行标注，标签标注格式为yolov格式，和每一类的图片存放在同一个文件夹下。  
  - 共有1904张Vtuber/Vups的图片，其中有1841张图片作为训练集，63张图片作为测试集。  
  - 数据集中每一个文件夹的名字就是一位虚拟主播的代号，这里采用拼音命名和主播自己的英文名结合的方法给主播命名。  
  - 文件夹下面即可看到对应的图片和标签，在根目录下也可以看到包含所有类别名字的classes.txt文件和yolov5的数据集路径配置的yaml文件。  
  - Use labelimg software for annotation, label labeling format is yolov format, and each type of picture is stored in the same folder.  
  - A total of 1904 Vtuber/Vups images, including 1841 images as training sets and 63 images as test sets.  
  - The name of each folder in the dataset is the code name of a virtual host, and the method of combining pinyin naming and the host's own English name is used to name the host.  
  - The corresponding pictures and tags can be seen under the folder, and the YAML file containing all the category names and .txt the YOLOV5 dataset path configuration can also be seen in the root directory.  
### 数据集内容(Dataset content)
数据集包含18位Vtuber/Vups，他们的类别名字如下：  
The dataset contains 18 Vtuber/Vups with the following class names:  
- Nana7mi 七海娜娜米  
- DongXueLian 东雪莲  
- BingTangIO 冰糖IO  
- MieLi 咩栗  
- Diana 嘉然  
- Taffy 塔菲  
- DaSi 大思(凜凜蝶凜)  
- MingQianNaiLv 明前奶绿  
- XiaoKe 小可学妹  
- XingTong 星瞳  
- TaoJiOvO 桃几OvO  
- LingYuan_yousa 泠鸢  
- ShenLeQiNai_KaguraNana 神樂七奈  
- MaoLei_Nyaru 猫雷  
- KizunaAI 绊爱  
- Azi 阿梓  
- GZY_w 顾子韵  
- Mayumi 麻尤米  
## 关于我(About me)
  - 我是一位还在就读大学三年级的本科生(2022年)，建立此数据集也单纯的是出于兴趣爱好。  
  - 如果您对我的数据集有任何疑问，或是该数据集涉及了一些版权问题等，请联系我。  
  - 您可以称呼我为小阳，您可以通过如下两种方式联系到我：  
    - 我的邮箱是：jiaxinsugar@gmail.com。  
    - 您也可以在哔哩哔哩平台上私信我，我的哔哩哔哩UID:436636983。  
  - I am a third-year undergraduate student (2022), and I built this dataset purely out of interest.  
  - If you have any questions about my dataset, or if the dataset involves some copyright issues, etc., please contact me.  
  - You can call me 小阳Xiaoyang, you can contact me in two ways:  
    - My email address is: jiaxinsugar@gmail.com。  
    - You can also send me a private message on the Bilibili platform, My Bilibili UID: 436636983。  
