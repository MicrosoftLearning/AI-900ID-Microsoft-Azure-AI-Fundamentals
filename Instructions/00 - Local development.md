## Pengembangan Lokal 

Jika Anda bekerja dengan komputer lokal, Anda dapat mengikuti langkah-langkah ini untuk mengonfigurasi lingkungan agar berfungsi dengan lab.  

### C++ Redistributable 
1. Unduh dan instal [Visual C++ Redistributable (x64)](https://aka.ms/vs/16/release/vc_redist.x64.exe) 

### Python dan paket yang diperlukan 
1. Instal [Python 3.6.1](https://www.python.org/downloads/release/python-361/)  
   - **Penting**: Pilih opsi untuk menambahkan Python ke variabel JALUR dan untuk didaftarkan sebagai lingkungan Python default 
2. Setelah penginstalan, buka *Perintah* dan masukkan perintah berikut untuk menginstal paket yang diperlukan: 

> pip install ipython jupyter matplotlib pillow requests azure-cognitiveservices-vision-computervision azure-cognitiveservices-vision-customvision azure-cognitiveservices-vision-face azure-cognitiveservices-language-textanalytics azure.cognitiveservices.speech azure_ai_formrecognizer 

### Visual Studio Code 
1. Jika belum memiliki Visual Studio Code, [unduh di sini](https://code.visualstudio.com/Download). Setelah penginstalan, mulai Visual Studio Code dan di tab Ekstensi (CTRL+SHIFT+X), cari dan instal ekstensi **Python** dari Microsoft.

2. Dengan Visual Studio Code, buka Terminal baru, ketik **git clone https://github.com/MicrosoftLearning/AI-900ID-Microsoft-Azure-AI-Fundamentals** dan pilih *enter*. 

