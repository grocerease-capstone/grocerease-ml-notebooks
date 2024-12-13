## Datasets

In this directory, there are two datasets to train the model. The product items dataset to train the NLP model and the receipts dataset to train the object detection model.

The product items dataset is obtained using the scrapping method from the Indomaret website. The dataset was initially separated based on its category. Then each csv file is merged into one csv with category as the label. Next, the csv is shuffled so that the distribution of data becomes more evenly distributed during training and validation.

The receipts dataset is generated using python and the pillow library. We designed the receipts very precisely like the original receipts. Next, we randomize the product items for each receipt based on the product items dataset that has been obtained by scrapping previously. The result is 500 receipt images that are ready to be annotated using the Roboflow website. Here is the access link to get the receipt dataset that has been annotated on the Roboflow website: [receipts dataset with annotation](https://app.roboflow.com/alfaindostruk/receipt-indomaret/1)
