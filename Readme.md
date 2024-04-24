#### a. How many data your publlsher program will send to the message broker in one
run?
Program publisher akan mengirimkan 5 data ke pialang pesan dalam satu kali jalankan.

#### b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Kedua URL sama karena keduanya mengirimkan permintaan ke server RabbitMQ. Perbedaannya dengan subscriber adalah bahwa permintaan ini dari publisher akan menghasilkan pengiriman pesan ke antrian (queue), sedangkan untuk subscriber, sebuah pendengar (listener) dibuat untuk mengambil data dari antrian pesan.

[gambar1](https://cdn.discordapp.com/attachments/1229389526179250287/1232682473989738496/image.png?ex=662a5883&is=66290703&hm=e0cc6b3e9a51950bc2147d5dbc46a3b4387d900581cb394cdc4a50634a615f56&]
