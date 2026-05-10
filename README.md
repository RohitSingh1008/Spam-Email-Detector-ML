# Spam Mail Detection Website ❤️
## Description 😀

1. The Website will tell you the message entered is spam or ham.
2. This website is built using the Flask web framework.
5. Used RandomForestClassifier Machine Learning algorithm for model building which gives 97.30% accuracy.

## Packages Used 👀
1. Flask
2. Pandas
3. Sklearn
5. Joblib
   
## Tools Used 🛠
1. language: Python, HTML, CSS & JS
2. UI: Flask, Bootstrap

## Video 🚀
https://github.com/RohitSingh1008/projects

## How to run project : - In VS code terminal 
1. Pahle Check kare ki python install hai ya nahi : py --version   or python --version then enter, iske version show hone agega jaise ki Pytho 3.13.3

2. Write py -m venv venv then enter

3. Write venv\Scripts\activate then enter har bar likhna hai

5. Write pip install -r reqirements.txt then enter then wait... not 

6. Write app.py then enter and waiting... after that click on  Running on http://127.0.0.1:5000 


## 💡 BONUS: Ye cheezein ek baar hi hoti hain, har baar nahi karni:

Command	           Har baar?	Kab likhna padta hai
-------------------------------------------------------
py --version	      ❌	       Sirf install check karne ke liye
python -m venv venv	  ❌	       Sirf pehli baar project setup ke time
pip install -r requirements.txt	❌	Sirf pehli baar ya naya package install ke baad
venv\Scripts\activate	✅	        Har baar new terminal me
python app.py	        ✅	        Jab bhi app run karna ho
 

Spam for search testing : /* Preloader Style */
#loader {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    z-index: 9999;
    transition: opacity 1s ease, visibility 1s ease;
    visibility: visible;
}

body.loaded #loader {
    opacity: 0;
    visibility: hidden;  /* This hides the preloader */
    pointer-events: none;
}

/* Smooth transition for body content */
body {
    opacity: 0;
    transition: opacity 1.5s ease-in-out;
}

body.loaded {
    opacity: 1;
}

/* Loader Spinner */
.loader-icon {
    border: 8px solid #f3f3f3;
    border-top: 8px solid #3498db;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    animation: spin 1s linear infinite;
    margin-top: 10px;
}

@keyframes spin {
    0% { transform: rotate(0); }
    100% { transform: rotate(360deg); }
}
<!--===testing code no popupopen===-->
