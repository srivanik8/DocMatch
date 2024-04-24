# DocMatch
## Problem Statement
Post Covid, humans have grown fragile. They have lost their ability to face physical stress and Covid has scarred us enough to leave us weak leading to high rates of deaths. It has also instilled fear and indicated the significance of awareness regarding the body, showing us that no symptoms shall be left unattended and treated with our own knowledge. The possibility of disease that is the presence of symptoms  without proper awareness leads to mental agony. The absence of good contacts with doctors and medical personnel might create a confusion about whom to approach and what sort of doctor to visit and to look for. 
Problem Statement : The objective is to develop an medical AI assistant that addresses medical issues faced by users. The system should have the capability to monitor and analyze user data, predict diseases, and recommend doctors aligned with user's medical conditions.
* Medical Assistant: Develop a healthcare recommendation system that analyzes user symptoms leveraging symptom data (using mock data), healthcare provider databases, and user ratings,  recommends doctors with matching specialties and aligned schedules

## Solution
1. Capture key user details like age, gender, and alcohol use. For pregnant users, note pregnancy status and trimester. Also, collect concise information on experienced symptoms for a comprehensive understanding.
2. Examine symptoms and offer the option to inquire about disease description and precautions for a more thorough understanding
3. Leveraging a predefined medication database, we offer personalized recommendations based on predicted diseases derived from user details. Additionally, we reveal anticipated health issues and suggest suitable medications.
4. Post medication recommendations, we facilitate users by directing them to nearby hospitals featuring specialists aligned with their specific medical condition.
## Setup of local environment
1. Fork this repo.
2. Run the command `git clone https://github.com/srivanik8/DocMatch.git`
3. All the data used for training and testing the models (disease prediction & symptom analysis) are in the folder models.
4. Install the required libraries using `pip install -r requirements.txt`.
5. Run command `python app.py`.
6. The website will start to run on `localhost:5000`
### How to use
1. Provide user details such as age, gender, alcohol consumption, and pregnancy status (if applicable).
2. Enter the symptoms experienced.
3. Click on "Predict Disease" to receive the predicted disease and personalized medication recommendations.
4. Use the hospital locator feature to find nearby healthcare facilities.
5. Use the specialization feature to recieve the specialist's info based on ratings and reviews along with their adddress and phone numbers.
## Demo
https://drive.google.com/file/d/1Q-UG8PwF6XaItq1-AG4E_CmgJfSo7B0-/view?usp=sharing 

