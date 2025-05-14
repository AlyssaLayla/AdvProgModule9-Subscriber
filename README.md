**Nama**: Alyssa Layla Sasti  <br /> 
**Kelas**: AdPro B  <br />
**NPM**: 2306152052 <br />

## REFLECTION MODULE 9 
1. What is amqp?
    - AMQP (Advanced Message Queuing Protocol) adalah sebuah protokol komunikasi terbuka yang dirancang untuk sistem message-oriented middleware. Dengan kata lain, AMQP digunakan untuk mengirim dan menerima pesan antar aplikasi atau komponen sistem secara asinkron melalui message broker seperti RabbitMQ. Saya memahami bahwa AMQP memungkinkan aplikasi-aplikasi untuk saling bertukar informasi (pesan) dengan cara yang aman dan terpisah secara logis. Hal ini berguna terutama ketika dua sistem atau layanan tidak dijalankan secara bersamaan (misalnya, satu layanan mengirim data dan layanan lain menerima saat tersedia).
2. What does it mean? guest:guest@localhost:5672, what is the first guest, and what is the second guest, and what is localhost:5672 is for?
    - guest:guest adalah format username:password untuk login ke broker AMQP. Dalam hal ini:
        - guest pertama adalah username default
        - guest kedua adalah password default
    - localhost menunjukkan bahwa koneksi dilakukan ke server lokal (komputer saya sendiri) di mana broker seperti RabbitMQ berjalan.
    - 5672 adalah port default yang digunakan oleh RabbitMQ untuk menerima koneksi AMQP.
    - Jadi, keseluruhan guest:guest@localhost:5672 berarti saya mengakses RabbitMQ (yang berjalan di komputer lokal saya) menggunakan username dan password default melalui port 5672.
