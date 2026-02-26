#PRAKTIKUM 2
Pada v3, Tailwind mengharuskan kita untuk menulis config dalam file .js. Di v4, Tailwind terintegrasi langsung ke dalam CSS menggunakan variabel CSS standar. Jadi tidak lagi membutuhkan file konfigurasi terpisah karena CSS itu sendiri adalah konfigurasinya. Di v4, semua variabel warna, font, dan ukuran didefinisikan langsung di dalam blok @theme di file CSS

- v3 Menggunakan @tailwind base, @tailwind components, dan @tailwind utilities. Cara lama ini bekerja dengan menyisipkan beban CSS yang sangat besar ke dalam tiga layer utama secara sekaligus
- v4 Menggunakan @import "tailwindcss";. Tailwind v4 lebih mirip dengan native CSS, v4 menggunakan standar @import yang lebih bersih. Seluruh layer (base, components, utilities) sudah dibundel secara otomatis di dalamnya.

#PRAKTIKUM 4
Jika memberi warna pada latar belakang elemen, cth. bg-blue-600, maka Komponen box model yang terpengaruh warna latar adalah? = Content, Padding, dan Border

#PRAKTIKUM 7
link gambar : https://drive.google.com/file/d/1weEEp8PauV9yV7FuqKzY0QhzZOBN3yCU/view?usp=drive_link