# Medusa

MEDical Utility Segregation Algorithm
<img width="1275" alt="image" src="https://user-images.githubusercontent.com/71515520/161372695-f34408cb-d9e5-4d76-9b3f-f992df9d2528.png">

Different types of healthcare wastes are generated by every department in a hospital, from the janitorial and housekeeping staff to surgical suites, infectious disease units, and so forth. 

It is highly hazardous which can give birth to serious diseases that may be lethal; therefore it is a problem of global nature. Biomedical waste management is of prominent importance to lessen the serious health consequences.

We aim to create a deep learning model for segregating medical wastes. Waste segregation is a vital role in waste management and proper segregation can result in effective waste management. This model will classify the given waste image into prominent medical waste categories (radioactive, sharp, chemical and general).

In order to achieve this, we have developed a two stage CNN for classifying the images. The first stage classifies it into one of three prominent medical wastes namely sharp, chemical and infectious. The second stage of CNN classifies it into non-bio-degradable, recyclable and incinerative. The dataset we prepared for both satges have around 1000 images consisting of sharp, chemical and infectious medical wastes along with non-bio-degradable, recyclable and incinerative. 

We have developed a mobilenetV2 based transfer learning model for performing image classification for both the stages. We found out that this model gave the best results with the lowest parameters. Then we developed a website using streamlit as our frontend language. We have also added outputs based on regional language for people to understand.  

We designed a webpage using HTML, CSS and JS that contains information about our problem statement, our research work and the scope of our project.
