# FullStackReactVideoApp
Project Structure
Backend (FastAPI)

main.py: The main FastAPI application file that contains the endpoints for uploading, listing, streaming, and deleting videos.

Frontend (React)

Cam.jsx: The main React component that handles video recording, uploading, and UI interactions.

WebcamStream.jsx: A component that initializes and displays the webcam stream.

ControlButtons.jsx: A component that contains the start and stop recording buttons.

VideoNameInput.jsx: A component that allows the user to input the video name and upload the video.

API Endpoints

Upload Video
URL: /upload
Method: POST

video: The video file to be uploaded.
name: The name of the video.
Response: Metadata of the uploaded video.
List Videos
URL: /videos
Method: GET
Response: A list of all uploaded videos.
Stream Video
URL: /videos/{video_id}
Method: GET
Response: The requested video stream.
Delete Video
URL: /videos/{video_id}
Method: DELETE
Response: Metadata of the deleted video.
How to Use
Record a Video:

Navigate to the frontend application.
Click on "Start Recording" to start the video recording.
Click on "Stop Recording" to stop the recording.
Upload the Video:

After stopping the recording, input a name for the video.
Click on "Upload" to upload the video to the server.
List Videos:

Navigate to the videos listing page to see all uploaded videos.
Stream a Video:

Click on a video in the list to start streaming it.
Delete a Video:

Click on the delete button next to a video in the list to delete it.
Run Api with  python -m uvicorn main:app --host localhost --port 8000 --reload. 
Run front end with npm run dev, with node js and react dependencies installed. 
