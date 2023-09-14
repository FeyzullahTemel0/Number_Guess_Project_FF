perl

# Sayı Tahminleme Uygulaması

Bu uygulama, kullanıcıların el ile çizdikleri sayıları tanımak için bir SVM (Destek Vektör Makinesi) modeli kullanır. Kullanıcılar, 300x300 piksel boyutlu bir kanvas üzerine çizim yapabilirler. Daha sonra "PREDICT" düğmesine tıkladıklarında, çizdikleri sayının tahmin edilen sonucunu alırlar.

## Kullanım

Uygulamayı çalıştırmak için aşağıdaki adımları izleyin:

1. Python ve PyQt5 gereksinimlerini yükleyin:

   ```bash
   pip install PyQt5

    Bu depoyu klonlayın veya indirin.

    Ana dizinde, eğitilmiş SVM modelini içeren bir SVM_Model.pkl dosyası bulunmalıdır. Modeli oluşturmak ve eğitmek için train_model.ipynb Jupyter defterini kullanabilirsiniz.

    Uygulamayı çalıştırın:

    bash

python main.py

Uygulama başladığında, bir sayı çizin ve "PREDICT" düğmesine tıklayarak tahmin sonucunu alın.

Örnek Ekran Görüntüsü

![Resim 1](https://github.com/FeyzullahTemel0/Number_Guess_Project/assets/109575132/d358c11f-8220-40f9-8b02-31a15882df8f)

![Resim 2](https://github.com/FeyzullahTemel0/Number_Guess_Project/assets/109575132/5d398946-8fb9-4a5c-9707-12fef3cb794e)


Geliştirme Ortamı

Bu uygulama, PyQt5, NumPy ve Pillow gibi Python kütüphaneleri kullanılarak geliştirilmiştir. Anaconda veya başka bir sanal ortam kullanmanızı Öneririm.
