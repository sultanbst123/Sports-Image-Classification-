# Sports-Image-Classification

Memprediksi 100 label olahraga berdasarkan gambar. 

- Train accuracy: 99%
- Validation accuracy: 97%
- Test(unseen) accuracy: 96%

## Note: 

Saya mengunakan 2 jenis model: 
### MobileVit
<p align="center">
 <img src="https://github.com/sultanbst123/Sports-Image-Classification-/blob/main/images.jpeg"><i> EfficientNet </i>
</p>

MobileViT, transformer citra yang ringan dan serbaguna. MobileViT menyajikan perspektif yang berbeda untuk pemrosesan informasi global dengan transformer, yaitu transformer sebagai konvolusi. Hasil kami menunjukkan bahwa MobileViT secara signifikan mengungguli jaringan berbasis CNN dan ViT di berbagai tugas dan kumpulan data.

### EfficientNetV2
untuk penjelasan silahkan kunjungi repo "EfficientNetV2 with TPU".

- weight: imagenet 
- optimizer: AdaBelief
- Learning Rate: 5e-4
- weight decay: 1e-4

## Dataset 
https://www.kaggle.com/gpiosenka/sports-classification?select=train

## Demo 
Stay tuned
