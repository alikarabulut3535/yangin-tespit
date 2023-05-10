# yangin-tespit
 OpenCv ile yangın tespit
Bu proje, görüntü işleme ile yapılan bir uygulamayı içerir. Bir web kamerası veya kamera gibi bir görüntü kaynağından alınan görüntüleri işler ve görüntülerdeki alevleri tespit eder. Ardından, ateş tespit edildiğinde, bir mesaj yazdırılır ve aynı zamanda bir ses dosyası çalınır.

Proje, OpenCV ve playsound gibi Python kütüphanelerini kullanır. OpenCV, bilgisayarın kameradan görüntüleri işlemesine ve analiz etmesine olanak tanır. Playsound ise, bir ses dosyasını çalmak için kullanılan basit bir kütüphanedir.
pip install opencv-python
pip install opencv-contrib-python
pip install playsound

Projenin başlangıcında, "fire_detection.xml" adlı bir dosya içe aktarılır. Bu dosya, alevleri tespit etmek için kullanılan önceden eğitilmiş bir sınıflandırıcıdır.

Daha sonra, bir döngü başlatılır ve her turda, kameradan bir görüntü alınır ve alevleri tespit etmek için sınıflandırıcı kullanılır. Alevler tespit edildiğinde, çerçeveye mavi bir kare çizilir ve ekrana “Dikkat ateş tespit edildi” mesajı yazdırılır. Aynı zamanda, "ses.mp3" adlı bir ses dosyası çalınır.

"q" tuşuna basarak programı sonlandırabilir. Bu durumda, kamera kapatılır.

![projee](https://github.com/alikarabulut3535/yangin-tespit/assets/122460361/f64afacd-04d1-4696-9b9c-f40a205b76de)
![frame](https://github.com/alikarabulut3535/yangin-tespit/assets/122460361/83b04f9f-8b67-41c7-be5f-eaabd6b1bd3a)
