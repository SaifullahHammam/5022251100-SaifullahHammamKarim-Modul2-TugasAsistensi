Menambahkan #include <stdio.h>
x, y tidak didefinisikan, karena pakai #define N 3, cukup pakai int M[N][N].
Pada loop for (int j = 0; k < N; j++) k seharusnya j.
Menambahkan {} pada setiap for loop.
Tipe data array pada scanf int, tapi format specifier pakai %lf (double), seharusnya %d.
Variabel sum belum dideklarasikan, seharusnya int sum = 0;.
printf pada rint_matrix memakai %c (char), padahal isi matriks int, seharusnya %d.
read_matrix(B) tidak ada ; seharusnya read_matrix(B);