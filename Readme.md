#### a. How many data your publlsher program will send to the message broker in one
run?
Program publisher akan mengirimkan 5 data ke pialang pesan dalam satu kali jalankan.

#### b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Kedua URL sama karena keduanya mengirimkan permintaan ke server RabbitMQ. Perbedaannya dengan subscriber adalah bahwa permintaan ini dari publisher akan menghasilkan pengiriman pesan ke antrian (queue), sedangkan untuk subscriber, sebuah pendengar (listener) dibuat untuk mengambil data dari antrian pesan.

