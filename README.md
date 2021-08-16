# UBUNTUX
install ubuntu server &amp;&amp; desktop , gunakan android/ios anda :)

# UBUNTU SERVER

# UBUNTU DESKTOP
pkg install x11-repo
pkg install tigervnc
vncserver
vncpasswd  (note : masukan password minimal 4-6)
export DISPLAY=":1"

# sampai tahap ini harusnya aplikasi GUI di termux mu sudah bisa dijalankan dan tidak menampilkan pesan “Gtk-WARNING **: cannot open display: :0.0” #

note (penting)

"(TERMUX ERROR ” Gtk-WARNING **: cannot open display: :0.0) "

“Pesan ini akan muncul jika environment variable belum diset (lihat langkah 3) atau vncserver kamu belum berjalan,jadi pastikan cek dulu apakah vnc server mu sudah berjalan dengan mengetikan perintah $ vncserver -listsetiap kali kamu ingin menjalankan aplikasi GUI di termux , untuk close/kill vnc server di termux kamu bisa menggunakan perintah $ vncserver -kill :a (ganti a dengan nomer display)

# download vncserver di Android / ios
jika lupa password anda 
masukan perintah : 

vncpassword
ifconfig
