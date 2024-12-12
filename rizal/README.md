## Notebook Rizal

### Data Preparation

Template colab untuk melakukan scrapping data product dari website Indomaret berdasarkan enam kategori sebagai berikut:

- home living
- kecantikan
- kesehatan
- makanan
- minuman
- product segar

Seluruh data product dari setiap kategori kemudian di merge menjadi satu file csv dan dilakukan shuffle. Hal ini bertujuan agar distribusi data menjadi lebih merata untuk training dan validation.

Akses link: [ml-data-preparation](https://colab.research.google.com/drive/1ub9DEDWK6IHSfELRUw-8yibeaVj_xtos?usp=sharing)

### Receipt Generator

Template notebook untuk generate custom random receipt berdasarkan data hasil scrapping pada notebook sebelumnya. Gunakan font monospace agar format tidak hancur dan konsisten. Font dapat diunduh melalui google fonts, kemudian diimport ke colab dan diberi nama font.ttf.

Akses link: [ml-receipt-generator](https://colab.research.google.com/drive/1iDcR0TSDfU4fccUIpFciPAj5v-08lstJ?usp=sharing)

### Object Detection

Berikut adalah template notebook untuk melatih model YOLO untuk object detection dengan tiga label. Berikut beberapa label yang dapat dideteksi oleh model tersebut:

- product_item
- product_item_voucher
- product_item_discount

Akses link: [ml-receipt-product-item-object-detection](https://colab.research.google.com/drive/17hk3dNzTcKOXFavB0gl-OQ0Y8VSwLVIj?usp=sharing)

### Natural Language Processing

Template notebook colab untuk klasifikasi sebuah product berdasarkan nama menjadi salah satu dari enam label. Beberapa label tersebut adalah sebagai berikut:

- home living
- minuman
- product-segar
- kecantikan
- kesehatan
- makanan
- lainnya (jika prediksi < threshold)

Akses link: [ml-product-classification-nlp](https://colab.research.google.com/drive/1OFVkkYzcKNfkysjA0GZJCj0px2XvkySk?usp=sharing)
