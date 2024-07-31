# Numerik dan Status:

1 - age :(numeric)

2 - job : jenis pekerjaan 
(categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self employed","retired","technician","services")
    
3 - marital : status perkawinan 
(categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
    
4 - education : 
(categorical: "unknown","secondary","primary","tertiary")
    
5 - default: apakah memiliki kredit macet? 
(binary: "yes","no")
    
6 - balance: saldo rata-rata tahunan, dalam euro (numeric)

7 - housing: apakah memiliki kredit rumah?
(binary: "yes","no")
    
8 - loan: apakah memiliki pinjaman pribadi?
(binary: "yes","no")


# Terkait dengan kontak terakhir dari kampanye saat ini:

9 - contact: jenis komunikasi kontak 
(categorical: "unknown","telephone","cellular")

10 - day: hari kontak terakhir dalam bulan (numeric)

11 - month: bulan kontak terakhir dalam tahun
(categorical: "jan", "feb", "mar", …, "nov", "dec")

12 - duration: durasi kontak terakhir, dalam detik (numeric)


# Atribut Lainnya:

13 - campaign: jumlah kontak yang dilakukan selama kampanye ini dan untuk klien ini (numeric, includes last contact)

14 - pdays: jumlah hari yang berlalu setelah klien terakhir dihubungi dari kampanye sebelumnya (numeric, -1 means client was not previously contacted)

15 - previous: jumlah kontak yang dilakukan sebelum kampanye ini dan untuk klien ini (numeric)

16 - poutcome: hasil dari kampanye pemasaran sebelumnya (categorical: "unknown","other","failure","success")

Output variable (desired target):
17 - y - apakah klien berlangganan deposito berjangka? (binary: "yes","no")

# Isi Konten:

a. Proses Data Cleansing
