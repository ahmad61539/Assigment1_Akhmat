﻿# Penjelasan Tugas

## Tugas 1
1. perulangan for yang menjelaskan menggunakan int dan variabel i adalah 1. Jika i kurang dari 100. maka variabel i ditambah.
 ```sh
   for (int i = 1; i <= 100; i++)
   ```
2. Jika variabel i kurang dari 9 maka akan memunculkan output angka yaitu 1, 2, 3, 4, 5, 6, 7, 8, 9.
```sh
   if (i <= 9) {
  System.out.println(i);
}
   ```

3. Jika lebih dari 9 maka akan muncul output Akhmat Qavidhufahmi sampai ke 100
```sh
   else {
   System.out.println("Akhmat Qavidhufahmi");
}
   ```

# Tugas 2
```sh
   Scanner scanner = new Scanner(System.in);
int number;
   ```
Membaca input dari pengguna dan penamaan variabel yaitu number menggunakan type data integer


```sh
   System.out.print("Masukkan sebuah bilangan bulat: ");
number = scanner.nextInt();
   ```
Menampilkan ( Masukkan sebuah bilangan bulat: ) dan menginput variabel number sesuai dengan pengguna input


```sh
   while (number != 0) {
            if (number > 0) {
                System.out.println("Bilangan positif.");
            } else {
                System.out.println("Bilangan negatif.");
            }
            System.out.print("Masukkan sebuah bilangan bulat (atau 0 untuk keluar): ");
            number = scanner.nextInt();
}
   ```
