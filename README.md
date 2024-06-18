# SIB6_Project8

# Studi Kasus Memuat Kata Random
https://wonderwords.readthedocs.io/en/latest/quickstart.html#the-randomsentence-class

# Langkah-langkah
1. Jalankan 'python -m venv env' Untuk Membuat Virtual Environment
2. Aktivasi 'env/Scripts/activate'
3. Jalankan 'pip install -r requirements.txt' Untuk install Python packages
4. Jalankan 'docker-compose up' untuk pull Kafka broker
![Project8 1](https://github.com/ZidanAliZaqi/sib6_project8/assets/97864880/747e85a3-cebe-4531-b2ed-d67924fd25cc)
5. Jalankan 'python sentences_producer.py' menjalankan producer untuk menghasilkan data
![Project8 2](https://github.com/ZidanAliZaqi/sib6_project8/assets/97864880/b045b2d2-3e36-4d4e-9426-8238f25e0573)
6. Jalankan 'python analytics.py' mendapatkan data stream dari Kafka dan menjalankan sentiment analysis
![Project8 3](https://github.com/ZidanAliZaqi/sib6_project8/assets/97864880/0cf7a011-4101-4ee8-8553-d87b04032c5a)
