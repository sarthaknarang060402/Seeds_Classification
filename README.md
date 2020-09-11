# Seeds_Classification

## Data_Set
...To download the dataset click on this link [DataSet](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/sandeep_nagar_research_iiit_ac_in/ESRAH-P_QKJEgNZAHP7vc4ABw9CycnUYBokWc9tbscfJzg?e=s6TtT3)
which contains a zip file (data/train, data/test) 0.8 and 0.2 respectively  also the list of images names and their label(train_datafile.csv, test_datafile.csv) 
... Or  create a folder to download the images run Seed_Classification/seeds_dataset/download_images.py which will download images in the images folder.

...The dataset contains 4 classes: Discolored-4, Broken-2, Pure-1, Silkcut-3.
Now we can run the main.py 
...Total images are 17802


## Models
1. Resnet 18, 34, 50, 101, 152
2. MobileNetV2
3. Basic_model ( 4 layers)
4.Squeezenet


## All the runnig code is in the src folder
1. model(MobileNetV2)
  ...train accuracy is 98%
  ...val_accuracy is 73%
