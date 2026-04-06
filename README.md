## **Makine Öğrenmesi Yöntemleri ile Betonarme Yapıların Hakim Titreşim Periyodunun Tahmini**




   Bu çalışma, Doç.Dr. Dilek OKUYUCU danışmanlığında Muhammet ÖZDEMİR tarafından **ÇOK KATLI BETONARME YAPILARDA OPERASYONEL MODAL ANALİZ UYGULAMASI ÜZERİNE SENSÖR OPTİMİZASYONU** başlıklı doktora tezi kapsamında üretilmiş olup betonarme (BA) yapıların hakim titreşim periyotlarının yapısal parametreler kullanılarak makine öğrenmesi yöntemleri ile tahmin edilmesine yönelik geliştirilen modelleri, ilgili kodları, model dosyalarını ve açıklayıcı dokümantasyonu içermektedir. 


   Tez çalışması kapsamında, 29 adet betonarme (BA) yapının hakim titreşim periyotları hem teorik modal analiz hem de deneysel modal analiz yöntemleri kullanılarak belirlenmiştir. Teorik modal analiz aşamasında oluşturulan sonlu eleman (SE) modelleri, deneysel modal analiz sonuçları esas alınarak kalibre edilmiştir. Kalibrasyon sürecinin ardından, elde edilen modeller üzerinde kat sayısı ve beton elastisite modülü parametreleri sistematik olarak değiştirilmiştir. Bu kapsamda, farklı yapısal özellikleri temsil eden toplam 176 adet betonarme yapıya ait veriyi içeren bir veri seti oluşturulmuştur.


 Oluşturulan 176 adet betonarme (BA) yapıya ait veri setinde; yapı yüksekliği, beton elastisite modülü, plan alanı (Lx × Ly), toplam kolon alanı, toplam perde alanı ve toplam duvar alanı yapısal parametreleri giriş değişkenleri olarak kullanılmış, yapıların hakim titreşim periyodu değerleri ise çıktı parametresi olarak tanımlanmıştır. Bu veri seti kullanılarak, rastgele ormanlar (Random Forest), destek vektör regresyonu (SVR), en yakın komşular (KNN) ve doğrusal regresyon (Linear Regression) yöntemleri ile ayrı ayrı makine öğrenmesi modelleri oluşturulmuştur. Her bir yöntem için model eğitim süreçleri bağımsız olarak yürütülmüş, uygun hiperparametre optimizasyonları gerçekleştirilmiş ve elde edilen modellerin tahmin performansları karşılaştırmalı olarak değerlendirilmiştir. Model başarılarının belirlenmesinde R², RMSE, MSE ve MAPE performans ölçütleri kullanılmıştır. 


 **Bu depoda yer alan klasörler ve dosyalar aşağıdaki şekildedir.** 

 **1. README**

 
 Bu dosyanın amacı, kapsamı, kullanılan yöntemler, dosya yapısı ve kullanım adımlarına ilişkin açıklamaları içeren ana tanıtım dosyasıdır.

 **2. Veri Seti**

 Model geliştirme sürecinde kullanılan, 176 BA yapının yapısal parametre bilgilerini ve hakim titreşim periyotlarını içeren veri setini ifade etmektedir.

 **3. Makine Öğrenmesi Modelleri**

 Eğitilmiş makine öğrenmesi modellerinin yer aldığı klasördür.
 
