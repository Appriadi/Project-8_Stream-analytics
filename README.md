# Project-8_Stream-analytics
## Analisis Sentimen Menggunakan TextBlod
  ### Langkah Langkah :
#### 1.Buat lingkungan virtual dengan menjalankan perintah berikut:
' python3 -m venv env
#### 2.Instal paket-paket Python yang diperlukan  : 
' pip3 install -r requirements.txt
#### 3.Jalankan docker-compose up untuk memulai broker Kafka
'docker-compose up
#### 4.Jalankan sentences_producer.py untuk menghasilkan data
'python3 sentences_producer.py
#### 5.Jalankan analytics.py untuk mendapatkan aliran data dari Kafka dan menjalankan analisis sentimen
'python3 analytics.py


