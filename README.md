# 🧠 PolypV7-Segmentation
**Genç bir araştırmacıdan medikal yapay zeka projesi**

Merhaba! Ben 16 yaşındayım ve bu proje, bağırsak poliplerini tespit eden bir segmentasyon modeli geliştirme çabamın bir ürünüdür. Yaşım yüzünden birçok profesyonel GPU platformuna erişimim yok. Yine de bu projeyi sonuna kadar geliştirmek istiyorum. 🌱

---

## 🎯 Proje Amacı
Kolon kanserinin erken teşhisinde kullanılabilecek, açık kaynaklı ve verimli bir **polip segmentasyon modeli** geliştirmek.

## ⚙️ Teknik Bilgiler
- **Model:** VGG19 FCN + RFPN Adında kendi imzamız olan mimarimiz (VGG-19 tabanlı, dense katman yok)
- **Framework:** TensorFlow / Keras
- **Aktivasyon:** Sigmoid (2 sınıflı çıktı: polip ve arkaplan)
- **Girdi boyutu:** 288x384
- **Loss:** Dice Loss

## 📊 Örnek Sonuçlar
> Aşağıdaki örneklerde segmentasyon başarılarını görebilirsiniz:

| Giriş Görseli | Segmentasyon Çıktısı |
|---------------|----------------------|
| ![input](results/input1.png) | ![output](results/output1.png) |
| ![input](results/input2.png) | ![output](results/output2.png) |

## 🚧 Eksikler / Devam Edenler
- [ ] GPU erişimi (şu an sadece Kaggle/Colab ile uğraşıyorum)
- [ ] Eğitim dataset'i üzerinde daha fazla augmentation
- [ ] Test set performans raporları (IoU, Dice)

## 🔮 Gelecek Planlar
- [ ] Ileride sahte polip görüntüleri oluşturarak görüntü sayısını artırmak

## 💬 Destek Olmak İsterseniz
Bu projeyi sürdürebilmek için GPU erişimine veya önerilere ihtiyacım var.

Yardımcı olabileceğiniz bazı şeyler:
- 🧠 GPU (Cloud, Fiziksel GPU, donate)
- 🧪 Dataset önerisi
- 🌟 Projeye yıldız bırakmak bile büyük motivasyon

## 📫 İletişim
- Mail: keremakman5109@hotmail.com
- GitHub Issues üzerinden de yazabilirsiniz

## 🔒 Lisans ve Kod Erişimi Hakkında

> **⚠️ Bu proje açık kaynak değildir.**

PolypV7-Segmentation projesine ait kodlar, mimari detaylar ve eğitim dosyaları yalnızca geliştiricisine aittir.

Kodlar hiçbir şekilde paylaşıma açık değildir, ticari ya da akademik amaçlarla kullanılamaz, kopyalanamaz, alıntılanamaz.

**Bu proje üzerindeki tüm fikrî haklar saklıdır.**

