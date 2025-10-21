🇹🇷 Türkçe Açıklama (İzahatlı)

Bu Jupyter Notebook, görüntü işleme tekniklerini uygulamak amacıyla hazırlanmıştır.
Kodda şu kütüphaneler kullanılmıştır:

OpenCV (cv2): Görüntüleri okumak, dönüştürmek, filtrelemek ve üzerinde işlemler yapmak için kullanılmış.

NumPy: Görüntü pikselleri üzerinde matematiksel işlemler yapmak için kullanılmış.

Matplotlib: İşlenen görüntüleri grafiksel olarak göstermek (plot etmek) için kullanılmış.

Kodun əsas adımları bunlardır:

Görüntünün içe aktarılması – cv2.imread() fonksiyonu ilə şəkil faylı oxunur.

Renk uzaylarının dönüştürülmesi – məsələn cv2.cvtColor() ilə görüntü BGR → RGB və ya gri ton (grayscale) formata çevrilir.

Filtreleme və dönüşümler – bulanıklaştırma (cv2.GaussianBlur()), kenar tespiti (cv2.Canny()), ya da histogram analizleri kimi əməliyyatlar edilir.

Sonuçların gösterimi – matplotlib.pyplot ilə orijinal və işlənmiş görüntülər yan-yana göstərilir.

Bu çalışma, temel düzeyde görüntü iyileştirme, kenar bulma, renk filtreleme gibi konuları deneysel olarak göstermektedir.

🇬🇧 English Description (With Explanation)

This Jupyter Notebook demonstrates image processing techniques using Python.
The main libraries used are:

OpenCV (cv2): For reading, transforming, filtering, and analyzing images.

NumPy: For performing numerical operations on image pixels.

Matplotlib: For visualizing the processed images.

Main steps in the code:

Image loading – the image is read using cv2.imread().

Color conversion – images are converted from BGR to RGB or to grayscale using cv2.cvtColor().

Filtering and transformations – includes blurring (cv2.GaussianBlur()), edge detection (cv2.Canny()), or histogram analysis.

Result visualization – processed images are displayed side by side using matplotlib.pyplot.

Overall, this project illustrates basic operations such as image enhancement, edge detection, and color filtering in a simple and educational way.
