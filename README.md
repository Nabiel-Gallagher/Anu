# Rangkuman Materi UKL kelas X semester 1 (ganjil)
Berdasarkan Latihan Soal 3 November 2025
---

## 🏅 Level Mudah 
### ⚙️ Percabangan (if-else) : https://www.petanikode.com/java-percabangan/

```java
if (kondisi) {
    // kode yang dijalankan jika kondisi benar (true)
} else {
    // kode yang dijalankan jika kondisi salah (false)
}
```
**💡 Contoh :**
```java
public class ContohIfElse {
    public static void main(String[] args) {
        int nilai = 75;

        if (nilai >= 70) {
            System.out.println("Lulus!");
        } else {
            System.out.println("Tidak lulus!");
        }
    }
}
```

**📘 Penjelasan:**

Program mengecek apakah nilai >= 70

Jika benar → tampilkan "Lulus!"

Jika salah → tampilkan "Tidak lulus!"

**📤 Output :**
```java
Lulus!
```
Karena nilai yang diinput diatas 70 ``if (nilai>= 70)`` ``System.out.println("Lulus!")``

## 🥈 Level Sedang :
### ⚙️ Percabangan (if-else) : https://www.petanikode.com/java-percabangan/

```java
if (kondisi) {
    // kode yang dijalankan jika kondisi benar (true)
} else {
    // kode yang dijalankan jika kondisi salah (false)
}
```
**💡 Contoh :**
```java
public class ContohIfElse {
    public static void main(String[] args) {
        int nilai = 75;

        if (nilai >= 70) {
            System.out.println("Lulus!");
        } else {
            System.out.println("Tidak lulus!");
        }
    }
}
```

**📘 Penjelasan:**

Program mengecek apakah nilai >= 70

Jika benar → tampilkan "Lulus!"

Jika salah → tampilkan "Tidak lulus!"

**📤 Output :**
```java
Lulus!
```
Karena nilai yang diinput diatas 70 ``if (nilai>= 70)`` ``System.out.println("Lulus!")``

### ⚙️ Perulangan (for) : https://www.petanikode.com/java-perulangan/

```java
for (inisialisasi; kondisi; perubahan) {
    // kode yang diulang
}
```
| Bagian              | Fungsi                                             |
| :------------------ | :------------------------------------------------- |
| 🧩 **inisialisasi** | Menentukan nilai awal variabel perulangan          |
| 🔁 **kondisi**      | Mengecek apakah perulangan masih perlu dilanjutkan |
| ➕ **perubahan**     | Mengubah nilai variabel setiap kali loop berjalan  |

**💡 Contoh :**
```java
public class ContohFor {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Perulangan ke-" + i);
        }
    }
}
```

**📘 Penjelasan:**

int `i = 1` → mulai dari 1

`i <= 5` → selama `i` kurang dari atau sama dengan 5, loop terus jalan

`i++` → setiap selesai satu putaran, `i` bertambah 1

**📤 Output :**
```java
Perulangan ke-1
Perulangan ke-2
Perulangan ke-3
Perulangan ke-4
Perulangan ke-5
```
### ⚙️ Fungsi dan Parameter : https://www.petanikode.com/java-prosedur-dan-fungsi/

**☕️ 1. Apa Itu Fungsi (Method) dalam Java**

**📘 Pengertian:**
Dalam bahasa Java, fungsi disebut method.

➡️ Fungsi (method) adalah sekumpulan perintah (kode) yang digabung menjadi satu bagian dan digunakan untuk melakukan tugas tertentu.

Dengan fungsi, kamu tidak perlu menulis kode yang sama berulang kali — cukup buat sekali, panggil berkali-kali.

```java
static TypeDataKembalian namaFungsi(){
    // statement atau kode fungsi
}
```
| Bagian              | Fungsi                                             |
| :-------------------- | :------------------------------------------------- |
| 🧩 **static** | Untuk membuat fungsi yang dapat dipanggil tanpa harus membuat instansiasi objek.          |
|🔁 **TypeDataKembalian**| Tipe data dari nilai yang dikembalikan setelah fungsi dieksekusi. |
| ➕ **namaFungsi()**     | Nama fungsinya. Biasanya ditulis dengan huruf kecil di awalnya. Lalu, kalau terdapat lebih dari satu suku kata, huruf awal di kata kedua ditulis kapital.  |

**🧩 2. Jenis-jenis Fungsi dalam Java**

Fungsi di Java bisa dibedakan berdasarkan tujuan dan cara penggunaannya. Berikut jenis-jenisnya:

**🔹 a. Fungsi Tanpa Parameter dan Tanpa Nilai Kembali**

Fungsi ini hanya menjalankan perintah, tidak butuh input dan tidak mengembalikan hasil.

**📄 Contoh:**
```java
public static void tampilPesan() {
    System.out.println("Selamat belajar Java!");
}
```

**📞 Pemanggilan:**
```java
tampilPesan();
```
**🔹 b. Fungsi Dengan Parameter Tapi Tanpa Nilai Kembali**

Fungsi ini butuh data (parameter) dari luar, tapi tidak mengembalikan hasil.

**📄 Contoh:**

public static void sapa(String nama) {
    System.out.println("Halo, " + nama + "!");
}


**📞 Pemanggilan:**
```java
sapa("Nabiel!");
```

**💬 Output:**
```java
Halo, Nabiel!
```
**🔹 c. Fungsi Tanpa Parameter Tapi Dengan Nilai Kembali**

Fungsi ini tidak butuh input, tapi akan menghasilkan (return) nilai.

**📄 Contoh:**
```java
public static int getAngka() {
    return 7;
}
```

**📞 Pemanggilan:**
```java
int angka = getAngka();
System.out.println(angka); // Output: 7
```
**🔹 d. Fungsi Dengan Parameter dan Dengan Nilai Kembali**

Fungsi ini menerima input (parameter) dan mengembalikan hasil (return).
Ini adalah jenis fungsi yang paling umum digunakan.

**📄 Contoh:**
```java
public static int tambah(int a, int b) {
    return a + b;
}
```

**📞 Pemanggilan:**
```java
int hasil = tambah(5, 3);
System.out.println("Hasilnya: " + hasil);
```

**💬 Output:**

Hasilnya: 8

🎯 3. Apa Itu Parameter
📘 Pengertian Parameter:

Parameter adalah data atau nilai yang dikirim ke fungsi agar fungsi dapat melakukan tugasnya.
Parameter ditulis dalam tanda kurung ( ) setelah nama fungsi.

**📄 Contoh:**

public static void cetakNama(String nama) {
    System.out.println("Nama kamu: " + nama);
}


➡️ String nama adalah parameter, di mana:

String = tipe data parameter

nama = nama variabel parameternya

📞 Pemanggilan:

cetakNama("Nabiel");


💬 Output:

Nama kamu: Nabiel
