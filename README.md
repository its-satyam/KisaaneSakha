# KisaaneSakha: A multiservice web-app for Indian Farmers. 

<center><img src="https://github.com/its-satyam/KisaaneSakha/blob/main/KisaaneSakha/authkv/static/images/farmers.jpg?raw=true" style="width:200px; height:200px "  /></center>


## PURPOSE:

Agriculture and its allied sectors play a vital role in the Indian economy. In today's digital age, it is crucial for these areas to keep up with technological advancements. As a part of our initiative, we aim to raise awareness among Indian farmers about the diverse range of e-farming features that can greatly benefit them. Although our initiative may be small in scale, it is not limited in its potential. We believe that there is significant scope for the future of e-farming and for our system to make a meaningful impact.

## ABOUT THE APPLICATION:

Our Django and ML-based web application is designed to revolutionize the E-Agro industry by providing a wide range of powerful features. These include crop prediction with a 99% accuracy rate using Random Forest Classifier, plant disease detection with a 95% accuracy rate using Sequential Model, tool renting functionality using Django Models, climate information through REST API, news updates through REST API, and expert assistance with contact details and feedback options. Our application aims to empower farmers with advanced technologies for optimizing farming operations, making informed decisions, and improving agricultural outcomes.

## FEATURES:

- Crop Prediction - Random Forest Classifier : 99% accuracy
- Plant Disease Detection - Sequential Model : 95% accuracy
- Renting Tools - Django Models
- Know the climate - REST API
- NEWs - REST API
- Expert assistance - contact details and feedback

## CONTRIBUTERS:

- Satyam Gupta: https://www.linkedin.com/in/satyam-gupta-152699207/
- Ishika Gupta: https://www.linkedin.com/in/ishika-gupta-09a187213/
- Nikhil Soni: https://www.linkedin.com/in/nikhil-soni-435b13217/

## TECHNOLOGY USED:

Machine Learning,
Image Processing,
Django, REST APIs,
HTML, CSS, JS,
Tensorflow.

## TOOLS:

VS Code,
Canva.

## DATASETS:

- Crop Prediction: .csv file is included in the corresponding feature folder.
- Plant disease detection : https://www.kaggle.com/datasets/emmarex/plantdisease

## REQUIREMENTS TO RUN THE WEB APP:

(Below stated versions were used to build this application)
- Python V3.8.7
- Django V3.2.4
- Tensorflow V2.7.0

## USAGE:

1. Download the zip file "KisaaneSakha" and unzip it in your system, or clone the repository.
2. Download .h5 file, and place it in the "plant_disease_detection" app folder.
3. Open the "settings.py" file located in "KisaaneSakha/KisaaneSakha" and make the necessary changes on line 141 and 142 by adding your email ID and password for the email account.
4. Open the command prompt and navigate to the "KisaaneSakha" folder that contains the "manage.py" file and all the apps.
5. In the command prompt, run the following commands:
    -> python manage.py makemigrations
    -> python manage.py migrate
    -> python manage.py runserver

## FUTURE SCOPE:

Future Directions:
1. Expanding the crop prediction model by incorporating larger datasets.
2. Enhancing the plant disease detection model by adding more leaf diseases and improving accuracy.
3. Integrating online payment methods for renting tools to streamline the process.
4. Refining the tool renting functionality to only display details of tools available from farmers in the same region as the user.
5. Adding a weather forecast feature to provide extended weather predictions for a week or more.

