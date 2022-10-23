# SpeechMe!

An app for those who want to check their pronounciation of English words...

## Backend folder
The backend folder houses a main function, which is not really used in the actual applicaiton, but can be used to check the backend functionality.
The main function calls Get_Score housed in transcribe.py, which returns a score for the user's pronounciation based on a recording and a target word.
The app.py is a flask file that runs Get_Score and returns it's value to the caller... which in this case is the swift front end.

## Frontend folder
The frontend folder houses the Swift front end, which contains the UI design for the Speech me app. It includes 4 screens: Welcome, user word input screen, voice recording screen, and score screen. It allows users to navigate between screens depending on the number of times the user wants to practice a given word. 
