## Notebook Rizal

### Data Preparation

Notebook template for scrapping product data from Indomaret website based on six categories as follows:

- home living
- kecantikan
- kesehatan
- makanan
- minuman
- product segar

All product data from each category is merged into one csv file and shuffled. This aims to make the data distribution more evenly distributed for training and validation.

Access link: [ml-data-preparation](https://colab.research.google.com/drive/1ub9DEDWK6IHSfELRUw-8yibeaVj_xtos?usp=sharing)

### Receipt Generator

Notebook template to generate custom random receipts based on the scrapped data in the previous notebook.

Instructions:
Use monospaced fonts to keep the formatting consistent. Fonts can be downloaded via google fonts, then imported into colab and named “font.ttf”.

Access link: [ml-receipt-generator](https://colab.research.google.com/drive/1iDcR0TSDfU4fccUIpFciPAj5v-08lstJ?usp=sharing)

### Object Detection

Notebook template to train the YOLO model for object detection with three labels. Here are some labels that can be detected by the model:

- product_item
- product_item_voucher [canceled]
- product_item_discount [canceled]

Access link: [ml-receipt-product-item-object-detection](https://colab.research.google.com/drive/17hk3dNzTcKOXFavB0gl-OQ0Y8VSwLVIj?usp=sharing)

### Natural Language Processing

Notebook template for classifying a product by name using NLP. The model will classify into one of the seven available labels. Some of these labels are as follows:

- home living
- minuman
- product-segar
- kecantikan
- kesehatan
- makanan
- lainnya (if confidence < threshold)

Access link: [ml-product-classification-nlp](https://colab.research.google.com/drive/1OFVkkYzcKNfkysjA0GZJCj0px2XvkySk?usp=sharing)
