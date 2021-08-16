# UBUNTUX
install ubuntu server &amp;&amp; desktop , gunakan android/ios anda :)

# UBUNTU SERVER

# UBUNTU DESKTOP
# $pkg install x11-repo
# $pkg install tigervnc
# $vncserver
# $vncpasswd  (note : masukan password minimal 4-6)
# $export DISPLAY=":1"

# sampai tahap ini harusnya aplikasi GUI di termux mu sudah bisa dijalankan dan tidak menampilkan pesan “Gtk-WARNING **: cannot open display: :0.0” #

note (penting)

"(TERMUX ERROR ” Gtk-WARNING **: cannot open display: :0.0) "

“Pesan ini akan muncul jika environment variable belum diset (lihat langkah 3) atau vncserver kamu belum berjalan,jadi pastikan cek dulu apakah vnc server mu sudah berjalan dengan mengetikan perintah $ vncserver -listsetiap kali kamu ingin menjalankan aplikasi GUI di termux , untuk close/kill vnc server di termux kamu bisa menggunakan perintah $ vncserver -kill :a (ganti a dengan nomer display)

# download vncserver di Android / ios

untuk mengakses GUI termux di android mu dari hp android mu kamu bisa buka aplikasi vnc viewer di android > klik tanda plus > pada address masukan 127.0.0.1:5901 ,beri nama terserah lalu tap create
kalau sudah di create kamu tap ke list vnc yang kamu buat tadi, jika minta password masukan password yang telah kamu set di vnc server tadi.Harusnya kamu sudah mendapatkan tampilan hitam dan ada terminal linux nya,kamu bisa mengeksekusi aplikasi GUI dari terminal emulator tersebut.

jika lupa password anda 
masukan perintah : 

# $vncpassword (note : setting password desktop)
# $ifconfig
