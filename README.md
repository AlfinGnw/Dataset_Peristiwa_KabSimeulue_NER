Dataset ini merupakan dataset NER dari berbagai peristiwa kejadian yang ada di kabupaten Simeulue. 
Sumber data ini diambil melalui teknik scraping pada media pemberitaan yang meliput peristiwa yang pernah terjadi di Kabupaten Simeulue. 
Dataset ini telah dilakukan proses preprocessing yang melalui 3 tahapan (Penghapusan URL, Tokenisasi dan Pelabelan).
Pelabelan menggunakan skema label NER yang terdiri dari 4 label data, yaitu EVENT, LOC, TIME dan O.
Label EVENT menunjukkan entitas peristiwa, label LOC menunjukkan lokasi terjadinya peristiwa, kemudian label TIME untuk entitas waktu kejadian peristiwa dan label O untuk bukan entitas.

Dataset ini masih jauh dari kata bagus, hal tersebut dikarenakan distribusi dari masing-masing label tidak seimbang. Sehingga hal tersebut dapat mempengaruhi optimalisasi model NER sendiri.

![image](https://github.com/user-attachments/assets/ff032b81-7544-4b2f-a501-6d78b8a67767)

Gambar diatas merupakan distribusi label, dimana label O mendominasi dalam dataset ini. Sehingga diperlukan teknik seperti sample weigth untuk mengakali hal tersebut agar model dapat berlatih pada data minoritasnya.
Dataset ini mungkin akan dilakukan pengupdate an demi mencapai kualitas data yang baik.
