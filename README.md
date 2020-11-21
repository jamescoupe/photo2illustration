*Part 6 of BotBE*



**Description**

Using photos of birds as input, generate illustrated versions of them. This uses cyclegan.

**Usage**
python cyclegan/test.py --dataroot cyclegan/datasets/bird2illustration --name bird2illustration --model test --no_dropout --preprocess none --gpu_ids -1

**Training Data**:

- [Birds](http://www.vision.caltech.edu/visipedia/CUB-200.html)

- [Illustrations of Birds](https://drive.google.com/drive/folders/1DmYX29c5gpN687wPY6fdBrYYNKuuh4h9?usp=sharing)

**Pre-trained versions with sample results**
1. Pretrained network, using approx. 80 illustrations and 130 images: [link (43mb)](https://drive.google.com/file/d/13-MTb621-v5KLZWq055cK_M-qSsXAtoJ/view?usp=sharing)

![results80](https://github.com/jamescoupe/photo2illustration/blob/main/birdsofbritishem00gree101-201-078_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/birdsofbritishem00gree-1-100-045_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/birdsofbritishem00gree-1-100-052_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/birdsofbritishem00gree-1-100-018_fake_A.png?raw=true)

2. Same as 1, but with additional 435 Audobon illustrations:

![results80](https://github.com/jamescoupe/photo2illustration/blob/main/epoch173_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/epoch182_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/epoch187_fake_A.png?raw=true)
![results80](https://github.com/jamescoupe/photo2illustration/blob/main/epoch194_fake_A.png?raw=true)
