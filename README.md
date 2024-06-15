# FullStackReactVideoApp
**Project Structure**

**Backend (FastAPI):**

main.py: The main FastAPI application file that contains the endpoints for uploading, listing, streaming, and deleting videos.

**Frontend (React):**

Cam.jsx: The main React component that handles video recording, uploading, and UI interactions.

WebcamStream.jsx: A component that initializes and displays the webcam stream.

ControlButtons.jsx: A component that contains the start and stop recording buttons.

VideoNameInput.jsx: A component that allows the user to input the video name and upload the video.

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
