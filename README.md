# Machine Learning Jual.In
Machine learning model for image classification and location-based recommendation system in Jual.In application

## Contributing
Team Machine Learning on Jual.in:  
- [Satriadi Putra Santika](https://www.linkedin.com/in/spsantika/)
- [Fhillipus Mahendra](https://www.linkedin.com/in/fhlpmah/)

## Dataset  
We import the dataset from kaggle.com and web scrapping in dataumkm.com and Google Image
- [Fashion Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)

## Library  
Library we use in this model:
```bash
  tensorflow
  os
  numpy
  pandas
  cv2
  splitfolders
  scikit-learn
  matplotlib
  seaborn
``` 

## Image Classification
 This classification has 25 classes which is:
 - 0: 'Ayam Goreng Tepung'
 - 1: 'Baju'
 - 2: 'Baso'
 - 3: 'Celana'
 - 4: 'Dompet'
 - 5: 'Gaun'
 - 6: 'Jam Tangan'
 - 7: 'Jus'
 - 8: 'Kacamata'
 - 9: 'Kaos Kaki'
 - 10: 'Keripik'
 - 11: 'Kopi'
 - 12: 'Makeup'
 - 13: 'Martabak Manis'
 - 14: 'Mie Ayam'
 - 15: 'Mie Goreng'
 - 16: 'Nasi Goreng'
 - 17: 'Parfum'
 - 18: 'Pisang Goreng'
 - 19: 'Roti Bakar'
 - 20: 'Sate Ayam'
 - 21: 'Sendal'
 - 22: 'Sepatu'
 - 23: 'Tas'
 - 24: 'Topi'

We use transfer learning method [Xception](https://www.tensorflow.org/api_docs/python/tf/keras/applications/xception/Xception) on our model so it can reach high accuracy.

Accuracy before Fine-Tuning:  
![akurasi1](https://drive.google.com/uc?id=1guRY12wEn2mc-qumG4fZ41_HcoTWZ6JA)  

Accuracy after Fine-Tuning:
![akurasi2](https://drive.google.com/uc?id=1zGvgA9cnUb60mASeEit6NG5O_n5MI6s4)

Result predict on image:  
![Baju](https://drive.google.com/uc?id=1WwsVNdKRdKDf4b8uNINx3jdG_dNyRyJo)

![Parfum](https://drive.google.com/uc?id=1Bi2cZrjizz_zZYluAwNiYzwYWJJvYYaJ)
