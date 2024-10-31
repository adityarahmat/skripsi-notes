# PENDAHULUAN (Perlu Update, nunggu dari Pak Eko)
Bab ini membahas mengenai latar belakang, rumusan masalah, manfaat dan tujuan,
ruang lingkup, dan sistematika penulisan pada skripsi yang berjudul Optimasi Model Klasifikasi Jenis Kendaraan Menggunakan Model CNN dengan Arsitektur MobileNetV2.
1. Latar Belakang
   - Indonesia merupakan negara dengan tingkat kepadatan penduduk yang tinggi. Menurut data dari Badan Pusat Statistika (2023), jumlah penduduk di Indonesia terus meningkat hingga mencapai lebih dari 270.000.000 jiwa, hal tersebut turut berdampak pada naiknya jumlah kendaraan mencapai 146.000.000 unit. Peningkatan jumlah kendaraan yang tinggi menimbulkan masalah transportasi yang kompleks, seperti kemacetan lalu lintas, risiko kecelakaan yang tinggi, serta tingkat keamanan yang menurun. Pengawasan dan pengelolaan kendaraan secara tepat diperlukan untuk menyelesaikan masalah yang ada. Oleh karena itu, diperlukan pendekatan yang efisien untuk mengidentifikasi, melacak, dan mengawasi kendaraan di berbagai sektor seperti pengawasan lalu lintas, pengelolaan jalan tol otomatis, dan sistem parkir yang aman.
   - Identifikasi, pelacakan, pengawasan, dan keamanan kendaraan merupakan aspek penting dalam manajemen transportasi modern. Saat ini, manajemen transportasi banyak dilakukan dengan pendekatan *human-oriented*. Misalnya, pengidentifikasian dan pengawasan kendaraan secara manual di gerbang tol oleh petugas keamanan. Pendekatan ini memiliki keterbatasan karena bergantung pada tenaga manusia yang memiliki batas tenaga sehingga tidak dapat bekerja optimal sepanjang waktu. Meningkatnya jumlah kendaraan juga menjadi faktor untuk mencari solusi lain yang lebih efisien. Solusi berbasis teknologi yang dapat beroperasi secara otomatis dan *real-time* menjadi solusi yang tepat untuk peningkatan efisiensi manajemen transportasi.
   - Salah satu solusi yang dapat diandalakan adalah penggunaan teknologi *machine learning*. *Machine learning* memungkinkan mesin untuk belajar dari data dan membuat keputusan sendiri. *Deep learning*, cabang dari *machine learning* yang menggunakan neural networks complex, telah terbukti efektif dalam penggunaan Convolutional Neural Network (CNN) untuk klasifikasi citra gambar [Zhang et al., 2020]. CNN banyak digunakan untuk klasifikasi gambar, termasuk identifikasi jenis kendaraan. Banyak penelitian yang sudah dilakukan menunjukan efektivitas CNN dalam klasifikasi objek pada gambar, seperti deteksi masker, lalu lintas, dan identifikasi jenis kendaraan. Salah satu arsitektur yang sering digunakan dalam penelitian klasifikasi adalah MobileNetV2.
   - MobileNetV2 dirancang dengan efisiensi komputasi dan kemampuan untuk diterapkan pada perangkat dengan sumber daya terbatas, sambil tetap mempertahankan akurasi yang tinggi. Dalam penelitian oleh Sandler et al. (2018), MobileNetV2 terbukti dapat mencapai hasil akurasi yang baik dengan konsumsi memori yang rendah. Namun, mencapai performa terbaik dalam model berbasis deep learning sering kali membutuhkan percobaan yang banyak. Perlu adanya optimasi *hyperparameter* secara otomatis untuk mencapai hasil yang maksiamal.
   - Penelitian ini akan berfokus pada optimasi hyperparameter secara otomatis pada model klasifikasi jenis kendaraan menggunakan arsitektur MobileNetV2. Optimasi hyperparameter adalah proses untuk menentukan kombinasi hyperparameter terbaik dalam model, yang dapat mempengaruhi akurasi akhir dari model yang dilatih. Untuk menyederhanakan dan mempercepat proses ini, digunakan pendekatan optimasi otomatis menggunakan KerasTuner. Dengan optimasi otomatis ini, diharapkan model yang dihasilkan dapat mencapai performa yang lebih baik dalam klasifikasi jenis kendaraan. Studi ini diharapkan dapat memberikan kontribusi dalam pengembangan sistem klasifikasi kendaraan secara otomatis yang dapat diterapkan dalam berbagai sektor, seperti transportasi, keamanan, dan pengelolaan jalan tol.








Reference
  
Zhang,Y.; Wang,X.& Li,J.(2020 ) A review of machine learning methods for vehicle classification based on image processing techniques Journal Intelligent Transportation Systems ;24(3);251 –262 doi10108015472450202017414534 ;

1. Sandler, M., et al. (2018). _MobileNetV2: Inverted Residuals and Linear Bottlenecks_. IEEE Conference on Computer Vision and Pattern Recognition (CVPR). DOI: 10.1109/CVPR.2018.00474.
2. Ren, S., et al. (2017). _Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks_. IEEE Transactions on Pattern Analysis and Machine Intelligence. DOI: 10.1109/TPAMI.2016.2577031.
3. Basha, S.S., et al. (2023). _An Efficient Hyperparameter Tuning Approach for CNN Models using Keras Tuner_. IEEE Access. DOI: 10.1109/ACCESS.2023.3269987.


1. Badan Pusat Statistik (2023). _Statistik Kendaraan Bermotor di Indonesia_. BPS.
2. Yu, S., et al. (2020). _Automatic Vehicle Type Classification using Deep Learning_. IEEE Transactions on Intelligent Transportation Systems. DOI: 10.1109/TITS.2020.2992062.
3. Krizhevsky, A., et al. (2017). _ImageNet Classification with Deep Convolutional Neural Networks_. Communications of the ACM. DOI: 10.1145/3065386.
4. Sandler, M., et al. (2018). _MobileNetV2: Inverted Residuals and Linear Bottlenecks_. IEEE Conference on Computer Vision and Pattern Recognition (CVPR). DOI: 10.1109/CVPR.2018.00474.
5. Basha, S.S., et al. (2023). _An Efficient Hyperparameter Tuning Approach for CNN Models using Keras Tuner_. IEEE Access. DOI: 10.1109/ACCESS.2023.3269987.