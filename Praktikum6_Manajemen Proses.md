# PSO_Tugas-6_09030582226038_TK4B


__Manajemen Proses__

Langkah-langkah pengerjaan:

1. Login sebagai studentOS dan lihat status proses, perhatikan kolom keluaran ps –au sebagai 
berikut :  
a. Sebutkan nama-nama proses yang bukan root  
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/dd83a190-244e-4c65-acd2-7d3c8d4e374c)
b. Tulis PID dan COMMAND dari proses yang paling banyak menggunakan CPU time
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/89422b5f-0b13-4926-b6f4-55bbe13ec118)
__PID : 1868__
__COMMAND : bash__
c. Sebutkan buyut proses dan PID dari proses tersebut
Buyut proses yaitu proses ang memiliki PID terkecil yang menandakan program tersebut merupakan program yang pertama dijalankan.
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/6f84cb3e-5b1d-4b23-b85f-21d06e9a182a)
__Buyut proses : /isr/lib/gdm3__
__PID : 822__
d. Sebutkan beberapa proses daemon
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/afb635c8-460c-4995-aa77-5115f5303018)
e. Pada prompt login lakukan hal-hal sebagai berikut :
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/6972f354-f92e-4a2d-98ef-423ab1463b09)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/fac08b74-a462-4734-bb86-e587298011c8)
Sebutkan PID yang paling besar dan kemudian buat urut-urutan proses sampai ke PPID =1.
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/f16b16b3-e461-4c5a-9a56-7e0ef6766071)
__2383, 2367, 2365, 1868, 1005, 826, 822__

2. Modifikasi program prog.sh sebagai berikut :
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/bc45f326-3d30-481f-8839-67846eb52351)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/a8387b91-fd03-4f40-bd52-c86fec65a20b)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/64c4b802-2624-4e93-8096-d95f3d26d426)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/5399b3ba-19ab-44a2-af17-ac0751f84928)

3. Modifikasi program  
myjob.sh. Buatlah trap sedemikian rupa, sehingga bila proses tersebut dihentikan (kil), otomatis 
file berkas akan terhapus.  
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/56860a80-ff2b-4293-afd7-88eaf307e265)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/42733cad-934e-41f8-9777-574329d28bb4)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/de636e65-06e5-49e5-b3ef-1cea4b0009a3)
![image](https://github.com/dwiaurelia/PSO_Tugas-6_09030582226038_TK4B/assets/126183346/0e00a1a8-b4d4-4459-8fb3-8fcfea6abbfa)





