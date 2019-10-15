# Project-Indexing

A. Text Indexing (Swish-e)

1. install swish-e dengan syntax: `sudo apt-get install swish-e`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text1.png)

![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text2.png)

![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text3.png)

2. Setelah itu, kita masukkan `IndexDir ./Provinsi` ke dalam file configurasi rdm.conf. 
- file text provinsi.txt kita isi dengan nama-nama provinsi yang ada di Indonesia. 
- Setelah itu, kita jalankan program indexing dengan syntax `swish-e -c rdm.conf` bisa dilihat bahwa ternyata didalam file terdapat 38 kata. 
- setelah selesai indexing, kita coba search kata "medan" file akan di run dan menunjukkan letak folder dimana kata itu berada.

![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text4.png)

isi rdm.conf
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text5.jpg)

isi text file provinsi.txt
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/text6.jpg)



B. Image Search Indexing

1. Pertama kita lakukan clone pada git dengan syntax `git clone https://github.com/kudeh/image-search-engine`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img1.jpg)

2. setelah itu kita lakukan upgrade `sudo apt-get upgrade`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img2.jpg)

3. setelah itu install python-3: `sudo apt-get install python3-pip`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img3.jpg)

4. untuk menginstall modul python kita masukkan syntax: `pip3 install -r requirements.txt`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img4.jpg)

5. masuk ke folder app dan ketik syntax `python3 index.py --dataset static/images --index index.csv` untuk menjalankan program image search.
- cek hasil nya dengan `pico index.csv`
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img5.jpg)

hasil sebagai berikut. untuk mengubah image ada di folder app/static/images
![alt text](https://github.com/qarnara/Project-Indexing/blob/master/Screenshot/img6.jpg)

# Sumber
1. Swish-e packet on ubuntu
2. Image-search-engine by kudeh : https://github.com/kudeh/image-search-engine
