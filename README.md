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
```java
public static double hitungVolume(double jariJari, double tinggi) {
    double volume = Math.PI * jariJari * jariJari * tinggi;
    return volume;
}

public static void sapa(String nama) {
    System.out.println("Halo, " + nama + "!");
}
```
