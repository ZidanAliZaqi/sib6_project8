# sib6_project8

# Studi Kasus Memuat Kata Random
https://wonderwords.readthedocs.io/en/latest/quickstart.html#the-randomsentence-class

# Langkah-langkah
1. Jalankan 'python -m venv env' Untuk Membuat Virtual Environment
2. Aktivasi 'env/Scripts/activate'
3. Jalankan 'pip install -r requirements.txt' Untuk install Python packages
4. Jalankan 'docker-compose up' untuk pull Kafka broker
5. Jalankan 'python sentences_producer.py' menjalankan producer untuk menghasilkan data
6. Jalankan 'python analytics.py' mendapatkan data stream dari Kafka dan menjalankan sentiment analysis