# Driving-License-data-extract


In government organizations, extracting data from images is challenging. We have identified this problem and decided to extract the data, like a person’s name, address, Driving license number etc, from the driving license like G1, G2, and G or any other country’s license. So it will become easy for the employees; they do not need to add the data manually. This web application will help them to extract the data from the images. They can also download the extracted data in Excel format. 
Initially, we collected the driving license data from some online resources or from our friends and family. After doing the annotations, we tried to train the multiple custom YOLO v5 models. At last, we compared the results of the trained custom models and tried to figure out which model works best for our project . At last, we developed the Flask API so that anyone can upload the license images by using the web app and get the license data. The API can also be modified easily to return JSON response while being in consumption.

Folder structure - \Driving License Data extract\final_data_v2\final_data_v2\images
For Labels - \Driving License Data extract\final_data_v2\final_data_v2\labels 
