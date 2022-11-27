#Transfer Learning with TensorFlow: Skin cancer classification using Kaggle HAM10000 Dataset
I have created a computer vision program to classify dermatoscopic images of skin cancer lesions. I have used the HAM10000 MNIST dataset to train my model. The model's backbone is EfficientNetB1 and a Global average pooling 2D layer is added on top.
Here are the results: accuracy on test set 84.3%
pigmented lesions this model detects: Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv) and vascular lesions (vasc).
