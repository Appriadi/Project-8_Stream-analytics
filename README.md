# Project-8_Stream-analytics
## Analisis Sentimen Menggunakan TextBlob
### Langkah Langkah :
- Buat lingkungan virtual dengan menjalankan perintah berikut:  'python3 -m venv env
- Instal paket-paket Python yang diperlukan : 'pip3 install -r requirements.txt
- Jalankan docker-compose up untuk memulai broker Kafka: 'docker-compose up
- Jalankan sentences_producer.py untuk menghasilkan data : 'python3 sentences_producer.py
- Jalankan analytics.py untuk mendapatkan aliran data dari Kafka dan menjalankan analisis sentimen:'python3 analytics.py
