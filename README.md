# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No  | Adı Soyadı           | Bölüm          		    | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|-------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505042  | Umut Can CESUR		 | Yazılım Mühendisliği     | PROJE_1       | [Github](https://github.com/umutcancesur)         |
| 1200505057  | Erdoğan AYDIN        | Yazılım Mühendisliği     | PROJE_1       | [Github](https://github.com/erdoganaydinn)        |
| 1200505053  | Hayatullah ALKIŞ     | Yazılım Mühendisliği     | PROJE_1       | [Github](https://github.com/hayatullahalkis)      |
| 1200505064  | Eyyüp SÜMER          | Yazılım Mühendisliği     | PROJE_1       | [Github](https://github.com/Eyyup1010)            |

---

## Proje Açıklaması

Projede PyTorch teknolojisi kullanılarak ANN, CNN ve Transfer Learning modelleri oluşturulmuştur. Projenin amacı yapay sinir ağı teknolojileriyle veri setindeki fotoğraflardan
kanserli hücreleri tespit etmektir. Projede ANN,CNN ve Transfer Learning için Doğruluk (Accuracy), Kesinlik (Precision), Recall (Duyarlılık), F1 Skoru (F1 Score), Konfüsyon Matrisi (Confusiom Matrix) ile değerlerndirme sonuçları
verilmiştir. Ayrıca CNN modeli için hiperparametre optimizasyonu (hyperparameter optimization) yapılmıştır.


## Proje Dosya Yapısı

- **/public**
- `ann-condition-1-fit.pth`
- `ann-condition-4-fit.pth`
- `ANN-fit-condition-1.ipynb`
- `ANN-fit-condition-4.ipynb`
- `ANN-predict-condition-1.ipynb`
- `ANN-predict-condition-4.ipynb`
- `cnn-condition-1-best-model.pth`
- `CNN-fit-condition-1.ipynb`
- `CNN-predict-condition-1.ipynb`
- `cnn-condition-4-best-model.pth`
- `CNN-fit-condition-4.ipynb`
- `CNN-predict-condition-4.ipynb`
- `SplitDatasetCode.ipynb`
- `transfer-learning-condition-1-fit.pth`
- `transfer-learning-condition-4-fit.pth`
- `Transfer-learning-fit-condition-1.ipynb`
- `Transfer-learning-fit-condition-4.ipynb`
- `Transfer-learning-predict-condition-1.ipynb`
- `Transfer-learning-predict-condition-4.ipynb`
- `README.md` 


---

## Kurulum

Öncelikle public klasörü altında bulunan tüm dosyaları bilgisayara indirin.
[BURADAN](https://drive.google.com/file/d/1pxkEk-3t_9NHJtiKStPXpogwfsd8Ivnl/view) veri setini indirin indirdiğiniz dosyalarla aynı konuma ekleyin. SplitDatasetCode.ipynb dosyası ile belirlediğiniz train,test ve validasyon oranlarında verisetini aynı dizine ayırın.
Eğer google collab ortamında çalışıyorsanız google drive hesabınız tüm dosyaları ve veri setini yüklemeniz gerekmektedir.
Sonra istediğiniz işlemin dosyasını açarak çalışabilirsiniz.

Kütüphane Sürümleri:

Python versiyon: 3.10.12
Pytorch versiyon: 2.1.0+cu121
torchvision versiyon: 0.16.0+cu121
scikit-learn versiyon: 1.2.2
seaborn versiyon: 0.12.2

---

## Kullanım

Projede istediği dosyayı çalıştırırken kütüphanelerin doğru bir şekilde import edildiğinden emin olunmalıdır.
Ayrıca verilen düzgün bir şekilde çekildiğinden emin olunmalıdır. Dosya yolu kontrol edilmelidir.

---

## Katkılar

Aşağıda projede kullandığımız teknolojilerin website linkleri yer almaktadır.

Derleyiciler:
[Google Colab](https://colab.google/) 
[Jupyter Notebook](https://jupyter.org/)
 
Kütüphaneler:
[Pytorch](https://pytorch.org/) 
[torchvision](https://pytorch.org/vision/stable/index.html) 
[scikit-learn](https://scikit-learn.org/stable/) 
[seaborn](https://seaborn.pydata.org/)     

---

## Öneriler

Eğer derleyici olarak Google Collab ortamında çalıştırmak istiyorsanız model eğitirken "session connection error" veya "runtime error" hatası alabilirsiniz. 
Bu hata ram ve işlemci kullanımının ücretsiz Google Collab versiyonunda sınırlandırılmış olmasından kaynaklanmaktadır.
Sorunsuz ve daha performanslı eğitim ve test senaryoları için Google Collab Pro kullanımını öneriririz.

---

## İletişim

Umut Can Cesur - ucesur.74@gmail.com
Erdoğan Aydın - erdoganaydinse@gmail.com
Hayatullah Alkış - hayatullahalkiss@gmail.com
