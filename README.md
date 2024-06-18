# ReactVideoAppWithAPI
**Project Structure-**

**Backend (FastAPI):**

main.py: The main FastAPI file that contains the endpoints for uploading, listing, streaming, and deleting videos.

**Frontend (React):**

Cam.jsx: The main React component that handles video recording, uploading, and UI interactions.

WebcamStream.jsx: A component that initializes and displays the webcam stream.

ControlButtons.jsx: A component that contains the start and stop recording buttons.

VideoNameInput.jsx: A component that allows the user to input the video name and upload the video.

VideoList.jsx: A component that displays all of the recorded videos in the list along with the name of the video

**API Endpoints**

URL: http://localhost:8000

Upload Video
URL: /upload
Method: POST

List Videos
URL: /videos
Method: GET

Stream Video
URL: /videos/{video_id}
Method: GET

Delete Video
URL: /videos/{video_id}
Method: DELETE

**How to Use:**

Run Api with terminal command: "python -m uvicorn main:app --host localhost --port 8000 --reload". 

Run front end with terminal command: "npm run dev", with node js and react dependencies installed.  

Start recording, then stop recording, name video and hit upload. 

Upload Complete.

Page will Refresh and display recorded videos in a list with a delete button. 

Due to github restriction of uploading less than 100files at a time, I had to zip the project and upload therefore you will have to unzip the file twice when downloading. 
