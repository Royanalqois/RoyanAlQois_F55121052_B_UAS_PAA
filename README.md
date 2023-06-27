# RoyanAlQois_F55121052_B_UAS_PAA2
1. Analisis Algoritma Bubble Sort dan Insertion Sort

Analisis Algoritma:

Worst Case:

Bubble Sort: O(n^2)
Pada kasus terburuk, ketika elemen-elemen dalam array terurut secara terbalik, bubble sort akan melakukan perbandingan dan pertukaran pada setiap pasangan elemen dalam array. Jumlah iterasi yang dibutuhkan adalah sebanyak n * (n-1) / 2, di mana n adalah jumlah elemen dalam array. Oleh karena itu, kompleksitas waktu dalam kasus terburuk adalah O(n^2).

Insertion Sort: O(n^2)
Pada kasus terburuk, ketika elemen-elemen dalam array terurut secara terbalik, insertion sort akan memerlukan pergeseran elemen dalam jumlah maksimum untuk memasukkan setiap elemen ke posisinya yang benar. Dalam hal ini, kompleksitas waktu dalam kasus terburuk juga adalah O(n^2).

Best Case:

Bubble Sort: O(n)
Pada kasus terbaik, ketika elemen-elemen dalam array sudah terurut dengan benar, bubble sort akan melakukan satu kali iterasi untuk memastikan bahwa array sudah terurut. Jumlah iterasi yang dibutuhkan adalah sebanyak n-1. Oleh karena itu, kompleksitas waktu dalam kasus terbaik adalah O(n).

Insertion Sort: O(n)
Pada kasus terbaik, ketika elemen-elemen dalam array sudah terurut dengan benar, insertion sort hanya memerlukan sedikit pergeseran elemen saat memasukkan setiap elemen ke posisinya yang benar. Dalam hal ini, kompleksitas waktu dalam kasus terbaik adalah O(n).

Average Case:

Bubble Sort: O(n^2)
Pada kasus rata-rata, bubble sort akan melakukan perbandingan dan pertukaran pada setiap pasangan elemen dalam array. Jumlah iterasi rata-rata yang dibutuhkan adalah sekitar n * (n-1) / 4. Oleh karena itu, kompleksitas waktu dalam kasus rata-rata adalah O(n^2).

Insertion Sort: O(n^2)
Pada kasus rata-rata, insertion sort akan memerlukan pergeseran elemen dalam jumlah yang lebih besar tergantung pada seberapa teracaknya array awal. Kompleksitas waktu dalam kasus rata-rata juga sebanyak O(n^2).

Pada kedua metode pengurutan, kompleksitas waktu tergantung pada ukuran array yang diurutkan. Bubble sort dan insertion sort adalah algoritma pengurutan sederhana yang lebih efisien untuk array yang relatif kecil atau hampir terurut. Namun, untuk array yang besar, algoritma pengurutan yang lebih efisien seperti merge sort atau quick sort lebih disarankan.

2. Analisis Algoritma Traveling Salesman Problem(TSP) dan Djikstra

Algoritma TSP (Traveling Salesman Problem):
Worst Case (Kasus Terburuk): Pada TSP, tidak ada kasus terburuk yang tetap ada. Algoritma TSP memiliki kompleksitas waktu eksponensial O(n!), di mana 'n' adalah jumlah node atau kota yang harus dikunjungi. Kasus terburuk terjadi ketika ada banyak node dan permutasi semua kemungkinan jalur harus diuji untuk menemukan jalur terpendek.

Best Case (Kasus Terbaik): Pada TSP, kasus terbaik terjadi ketika terdapat sedikit node, seperti hanya dua node atau ketika semua node memiliki bobot yang sama. Pada kasus terbaik ini, algoritma TSP dapat mencapai kompleksitas waktu O(1) atau konstan, karena jalur terpendek langsung diketahui.

Average Case (Kasus Rata-rata): Tidak ada analisis rata-rata yang tepat untuk algoritma TSP karena kompleksitas waktu algoritma ini sangat tergantung pada ukuran masalah. Namun, pada umumnya, kompleksitas waktu algoritma TSP cenderung eksponensial O(n!), yang berarti semakin banyak node yang harus dikunjungi, semakin tinggi kompleksitas waktu yang diperlukan.

Algoritma Dijkstra:
Worst Case (Kasus Terburuk): Pada Dijkstra, kasus terburuk terjadi ketika setiap simpul atau node harus diproses dan setiap sisi atau edge dalam graf harus dijelajahi. Dalam kasus ini, kompleksitas waktu algoritma Dijkstra adalah O((V + E) log V), di mana V adalah jumlah simpul dan E adalah jumlah sisi dalam graf.

Best Case (Kasus Terbaik): Pada kasus terbaik, algoritma Dijkstra memiliki kompleksitas waktu O(V + E), di mana V adalah jumlah simpul dan E adalah jumlah sisi dalam graf. Kasus terbaik terjadi ketika simpul awal adalah simpul tujuan atau ketika simpul tujuan berada tepat di sebelah simpul awal.

Average Case (Kasus Rata-rata): Pada kasus rata-rata, algoritma Dijkstra memiliki kompleksitas waktu O((V + E) log V). Namun, kompleksitas waktu rata-rata yang sebenarnya dapat bervariasi tergantung pada struktur graf, jarak antara simpul, dan bobot sisi. Dalam kasus rata-rata, algoritma Dijkstra cenderung lebih efisien daripada kasus terburuk, tetapi tetap memiliki kompleksitas waktu yang bergantung pada ukuran graf.
