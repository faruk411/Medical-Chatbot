## Tıp Alanında Sorulara Cevap Veren Chatbot 

Bu projede Tıp alanında sorulara metin şeklinde cevap üreten chatbot modeli geliştirdik.

Modelde kullandığımız veriseti Soru-Cveap sütunlarından oluşmaktadır, modeli eğitirken 60 bin veri kullanarak eğittik. 

Elimizde daha fazla veri vardı lakin donanım kısıtlaması yüzünden 60 binini kullanmak zorunda kaldık.

Modelden bahsedicek olursak model mimarisi olarak seq2seq mimarisi kullandık.

Bu mimaride 3 yapıdan oluşmaktadır. Bu yapılar ise encoder - decoder - attention.

Bu mimariyi kullanarak eğittiğimiz modelin bleu skoru ise %21 olarak ölçülmüştür.

İlerleyen süreçlerde fine-tuned işlemleri ile başka modellerde test edilecektir.

Bu eğittimiz modelide flask api ile bir mobil uygulamayada entegre ettik.

## Mobil uygulama

![tıpMobil](https://github.com/user-attachments/assets/ec20e643-1fd7-4c51-9285-2a21f0a81f6c)



![tıpMobil2](https://github.com/user-attachments/assets/6320d59f-0b6a-4798-b32e-b54b382e6aba)
