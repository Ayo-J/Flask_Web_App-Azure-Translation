
# Flask Web App with Azure Translation Service


This project is a Flask web application that integrates Azure's Translation Service for text translation and language detection. The frontend is built using HTML and CSS, providing a responsive and user-friendly interface. The backend is developed with Python Flask, which handles the server-side logic and integrates with Azure's Translation API for real-time text translation.

Tech Stack
Frontend: HTML, CSS


Backend: Python Flask


API Integration: Azure Translation Service


## Acknowledgements

 -Python 3.6 or later installed on your machine. You can download Python from [Here](https://www.python.org/downloads/)

  -Create an Azure account: If you don’t already have an Azure account, you can create one [Here](https://azure.microsoft.com/en-us/free/)

  Create a Translator resource:

    1 Go to the Azure portal.

    2 Click on Create a resource.

    3 Search for Translator.

    4 Click Create.

    5 Fill in the necessary details (Subscription, Resource Group, Name, Region, Pricing tier).

    6 Click Review + create and then Create



Get API Key and Endpoint:

After the resource is created, go to the resource overview.

You will see the Key 1 and Key 2 under Keys and Endpoint. Copy one of the keys.

Copy the Endpoint URL.






   



## Project Setup

Clone the repository

```bash
 git clone https://github.com/Ayo-J/Flask_Web_App.git
 cd flask-azure-translation

```

Create a virtual environment and activate it:
```bash
 python -m venv venv
 source venv/bin/activate   # On Windows, use `venv\Scripts\activate`


  ```

Install the required packages:
  ```bash
pip install -r requirements.txt

     

  ```

Set up the environment variables:

Create a file named .env in the root directory of the project.
Add your Azure Translator API key and endpoint to the .env file


Run the Flask application:



```bash
flask run


  ```



    
