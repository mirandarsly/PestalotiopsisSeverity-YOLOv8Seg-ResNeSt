# Performance Analysis of the Combined Method of YOLOv8 Segmentation and ResNeSt for Classifying the Severity of the Leaf Drop Disease of Pestalotiopsis on Rubber Plants
Rubber is a commodity that makes a significant contribution to the Indonesian economy, occupying the second position as the largest rubber producer in the world, with total production reaching 3.12 million tons. However, since 2017, the Pestalotiopsis rubber leaf fall disease caused by Pestalotiopsis sp. has become a serious threat to rubber cultivation and caused economic losses. The disease infects the leaves, causing ongoing necrosis and leaf drop, which inhibits photosynthesis. The area of rubber plantations affected by this disease was 382,000 ha in 2019 and increased by 30,328.84 ha in 2021, causing a loss of rubber latex production of up to 30%. This disease causes economic losses of billions of rupiah and expensive control costs, so early detection is necessary to enable rapid intervention. However, conventional detection requires high time, effort and costs as well as special expertise. Therefore, in this research, a deep learning model was developed to reduce the time, costs and energy in detecting the severity of the Pestalotiopsis rubber leaf fall disease into 5 levels, in accordance with research conducted by the Sembawa Rubber Research Center. 

In this study, the approach taken was to segment the spots of the Pestalotiopsis leaf fall disease and leaf veins from rubber leaf image data using the YOLOv8 segmentation model. Next, to train the ResNeSt classification model, image data that has been segmented by the trained YOLOv8 segmentation model is used. Thus, the classification of the severity of the Pestalotiopsis rubber leaf fall disease was carried out by only looking at the disease spots and rubber leaf veins, without paying attention to the overall color of the leaves. The metrics used are precision, recall, mAP50, mAP50-95, and accuracy.

This project utilizes pre-trained ResNeSt scripts built with TensorFlow from https://github.com/Burf/ResNeSt-Tensorflow2
