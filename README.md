# Medusa

**MEDical Utility Segregation Algorithm
<img width="1275" alt="image" src="https://user-images.githubusercontent.com/71515520/161372695-f34408cb-d9e5-4d76-9b3f-f992df9d2528.png">

Different types of healthcare wastes are generated by every department in a hospital, from the janitorial and housekeeping staff to surgical suites, infectious disease units, and so forth. 

It is highly hazardous which can give birth to serious diseases that may be lethal; therefore it is a problem of global nature. Biomedical waste management is of prominent importance to lessen the serious health consequences.

We aim to create a deep learning model for segregating medical wastes. Waste segregation is a vital role in waste management and proper segregation can result in effective waste management. This model will classify the given waste image into prominent medical waste categories (radioactive, sharp, chemical and general).

In order to achieve this, we have developed a two stage CNN for classifying the images. The first stage classifies it into one of three prominent medical wastes namely sharp, chemical and infectious. The second stage of CNN classifies it into non-bio-degradable, recyclable and incinerative. The dataset we prepared for both satges have around 1000 images consisting of sharp, chemical and infectious medical wastes along with non-bio-degradable, recyclable and incinerative. 

We have developed a mobilenetV2 based transfer learning model for performing image classification for both the stages. We found out that this model gave the best results with the lowest parameters. Then we developed a website using streamlit as our frontend language. We have also added outputs based on regional language for people to understand.  

We designed a webpage using HTML, CSS and JS that contains information about our problem statement, our research work and the scope of our project.

**Screenshots of Websites
<img width="1256" alt="image" src="https://user-images.githubusercontent.com/71515520/161372930-367ee242-ed46-48f3-9d64-9695258a5cc3.png">
<img width="1246" alt="image" src="https://user-images.githubusercontent.com/71515520/161372939-234c6994-3a4f-44a0-a1d2-9adb71e8718f.png">
<img width="1250" alt="image" src="https://user-images.githubusercontent.com/71515520/161372951-b2b415bf-b226-4f7b-a792-fe3a0276ac71.png">
<img width="1252" alt="image" src="https://user-images.githubusercontent.com/71515520/161372959-9a9b9303-9ee6-4d9b-aaca-df5ea7a31c11.png">
<img width="1243" alt="image" src="https://user-images.githubusercontent.com/71515520/161372969-500aae82-154d-47b0-88d4-dec8c48dc35c.png">
<img width="1242" alt="image" src="https://user-images.githubusercontent.com/71515520/161372975-fdf234f2-2dee-4123-adca-5164647856e4.png">
<img width="1240" alt="image" src="https://user-images.githubusercontent.com/71515520/161372985-06bf7393-f8a1-4444-8577-089caf84bdfc.png">

**Screenshots of the CNN Algorithm
<img width="986" alt="image" src="https://user-images.githubusercontent.com/71515520/161373037-43671252-d5e4-46a6-bb59-93d34c0a37f8.png">
<img width="1126" alt="image" src="https://user-images.githubusercontent.com/71515520/161373054-352aa246-d8a2-4324-bfda-b1c0bcdb6c84.png">
<img width="926" alt="image" src="https://user-images.githubusercontent.com/71515520/161373071-fad53820-d1e0-468b-8b2d-02b670a566d3.png">
<img width="1006" alt="image" src="https://user-images.githubusercontent.com/71515520/161373091-f575004c-4c81-4a0f-9ca1-016fc4651b5f.png">
<img width="992" alt="image" src="https://user-images.githubusercontent.com/71515520/161373122-81ee21c3-6d3c-40dd-b4db-048adab94b7c.png">
<img width="971" alt="image" src="https://user-images.githubusercontent.com/71515520/161373141-755b2f0b-739b-4140-b373-cd8451ea6ee3.png">
<img width="956" alt="image" src="https://user-images.githubusercontent.com/71515520/161373160-2e453dcd-fb72-4bb5-9895-70b5fbb4e136.png">


