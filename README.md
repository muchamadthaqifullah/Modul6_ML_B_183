# Modul6_ML_B_183

**Paper Rujukan :** [MobileNetV2: Inverted Residuals and Linear Bottlenecks]([https://vciba.springeropen.com/articles/10.1186/s42492-021-00091-z](https://openaccess.thecvf.com/content_cvpr_2018/html/Sandler_MobileNetV2_Inverted_Residuals_CVPR_2018_paper.html)

***Dataset yang digunakan :*** [Image RPS dari Modul 5].
Preprocessing yang digunakan : Data Augmentation dan Resizing
Model yang digunakan : [MobileNetV2](https://www.section.io/engineering-education/building-a-multiclass-image-classifier-using-mobilenet-v2-and-tensorflow/cnn-architecture.png)

**Akurasi** yang didapatkan menggunakan model MobileNetV2 adalah : **99%**

## Overview Dataset 
Gambar yang digunakan adalah gambar gunting, batu dan kertas. Terdiri dari 840 gambar untuk masing-masing kelasnya
Splitting Dataset : Training = 50%, Validation = 50%

## Preprocessing dan Modelling

 **Preprocessing Model** : resize(224,224), rotation_range=20, horizontal_flip=True, shear_range = 0.2, zoom_range = 0.2.


