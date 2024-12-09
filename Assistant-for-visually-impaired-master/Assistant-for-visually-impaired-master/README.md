V.E.A.D: Voice Assistant for the Visually Impaired
V.E.A.D is a voice assistant designed to empower visually impaired individuals by improving accessibility and enhancing their quality of life through innovative features. The system uses a combination of speech-to-text, object recognition, and natural language processing to deliver tailored functionalities.

Key Features of V.E.A.D:
1. Environmental Awareness:
Surrounding Description: Provides a concise description of the user's surroundings.
Road Conditions: Informs users about nearby road conditions to assist in navigation.
Context Recognition: Identifies specific locations like classrooms, kitchens, or bedrooms.
Object and People Detection: Identifies the number of people and objects visible in the webcam frame.
2. Object Finder:
Responds to commands such as "Where is my purse?" or "Is my watch here?" by detecting specified objects in the camera's view.
3. Text Reading:
Text Detection: Recognizes text in images and reads it aloud to the user.
Summarization: Capable of summarizing content from sources like newspapers.
4. Form Assistance:
Reads out form fields, simplifying tasks like filling out bank forms.
5. Mobile Integration:
Reads notifications from mobile devices.
Can respond to messages, emails, and manage calendar events.
6. General Chatbot Functions:
Provides basic assistance, including answering time-related queries, lighting conditions, and general "wh-" questions.
System Overview:
The system integrates the following hardware:

Wearable headphones.
Logitech webcam connected to a Raspberry Pi.
Tasks are initiated through voice commands and executed with verbal feedback.

Technologies Used:
Speech Recognition: Google API for converting speech to text.
Text-to-Speech: Implemented using the pyttsx3 library.
Object Recognition: Utilizes the COCO dataset.
Google Cloud Vision API: For advanced image analysis.
Dialogflow: Handles chatbot conversations and natural language understanding.
Installation and Setup:
Prerequisites:
Install dependencies.
Download credentials for the Google Vision API.
Place the credentials in the required directory.
Steps:
bash
Copy code
git clone https://github.com/mansi1710/DobaraMatPuchana
cd DobaraMatPuchana
pip install -r requirements.txt
Run the Program:
bash
Copy code
python main.py
This project represents a step toward inclusivity by leveraging cutting-edge technology to address the challenges faced by the visually impaired.