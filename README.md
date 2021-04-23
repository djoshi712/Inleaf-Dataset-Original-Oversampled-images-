# Inleaf Dataset
We have created Inleaf dataset for which the images are downloaded from internet. The ten categories of medicinal leaves in the ‘Inleaf dataset’ and their 
medicinal properties are as follows- Basil (Ocimum basilicum)- heal Cough, Cold, bronchitis; Cinnamon (Cinnamomum verum)- heal wounds, sores and boils;  
Peppermint- Digestive, Pain killer;  Neem (Azadirachta indica)- Sedative, analgesic,  epilepsy, hypertensive; Coriander (Coriandrum sativum)- renowned for 
their appetizing qualities;  Stevia (Stevia rebaudiana)- regulate blood sugar levels, kidney damage; Giloy (Tinospora Cordifolia)- beneficial in fever, chronic
fever, infections, low immunity, cancer; Drumstick (Moringa oleifera)- treating edema, preventing and treating cancer, fighting against bacterial diseases; 
AloeVera (Aloe barbadensis miller)- relieve sunburn and help heal wounds and Papaya (Carica papaya)-increase platelet count among patients with dengue fever.

It is less expensive to create such a dataset as opposed to well-defined standard datasets, which are often collected by capturing images from a high quality camera and/or processed in the lab before the training. In addition, the dataset generated from the internet reflects realistic images, which includes plenty of mislabeled, noisy and irrelevant images. 

# Inleaf Oversampled Dataset

It is vital to employ several preprocessing techniques; such as identifying mislabeled and irrelevant images from the dataset, data preprocessing and data balancing before final training of the model.The Inleaf dataset is balanced out by applying a data augmentation technique referred to as oversampling, based on a series of different sets of transformations.


# Dataset description
Total number of images before oversampling- 2572

Total number of images after oversampling- 4500

Training samples- 3150

Validation samples- 1350

No of classes- 10


# Results
The accuracy of the proposed architecture on the validation set of the original and the oversampled dataset is 93.41% and 94.81% respectively. 
