# borneo_deforestation

Palm oil has become ubiquitous in various industries, such as food production, animal feed, and cosmetics. 
Southeast Asia is the major global producer, with Indonesia alone accounting for almost half of the world's oil palm production. 
However, this extensive cultivation has led to alarming levels of deforestation in Indonesia, contributing one-third to the loss of old-growth forests, resulting in biodiversity decline, and carbon emissions. 

To monitor the impact of oil palm cultivation and ensure sustainable practices, regular forest monitoring is imperative. 
Satellite remote sensing, particularly with Sentinel-1 Synthetic Aperture Radar (SAR), offers an efficient solution for regular forest monitoring in cloud-prone areas like Indonesia, as it can penetrate cloud cover. 

For this study, Borneo Island in West Kalimantan was chosen as a case study due to its high cloud cover frequency and its priority status from Global Forest Watch. 
Monthly Sentinel-1 GRD images for 2018 to 2021 were collected and processed using GEE and Python. 
Image normalization was applied to every monthly image of 2020 and 2021 in respect of their median and standard deviation from two previous years to minimize backscattering noise and ensure consistency. By combining five different filter windows (no filter, 3x3, 5x5, 7x7, 9x9) and seven threshold level of backscattering coefficient (0 to -1.25 with an increment of 0.25), the best possible combination for deforestation detection was determined and validated using high-resolution planet images. 

We found maximum overall accuracy 94.74% when a 9x9 filter is applied with a threshold value of -0.25. 
The results revealed that approximately 14.7 km2 of deforestation occurred between 2020 and 2021, 80% of which took place after June 2021. 
The month of August 2021 experienced the highest deforestation rate, with 4.92 km2 lost. 
The primary forest area, which was relatively intact in 2020, suffered severe deforestation due to oil palm concessions after June 2021. This study demonstrated the potential of Sentinel-1 SAR for detecting forest cover changes in cloud-covered regions where cloud-free optical satellite images are scarce. 
It highlights the urgent need for sustainable practices in the oil palm industry, especially in areas with significant environmental impacts like Borneo Island.
