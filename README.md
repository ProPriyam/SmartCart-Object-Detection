# Smart Cart Object Detection
This repository builds a product detection model to recognize products that are put in the smart cart. The dataset comes from [here](https://github.com/gulvarol/grocerydataset).

* The provided dataset is converted to TFRecords for easy compatibility with the TFOD API. Further notes are available inside the `Colabs/GroceryDataset_EDA_Prep.ipynb` notebook.
* Detection network used: SSD MobileDet.
* For testing your images change the file image2product.json in Annotated Files

## Dataset citation
```
@article{varol16a,
      TITLE = {{Toward Retail Product Recognition on Grocery Shelves}},
      AUTHOR = {Varol, G{"u}l and Kuzu, Ridvan S.},
      JOURNAL = {ICIVC},
      YEAR = {2014}
}
```
