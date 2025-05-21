🎵 Song Recommendation System Based on Emotion Detection
This project uses real-time facial emotion detection to recommend and play mood-appropriate songs from YouTube. By utilizing OpenCV, a pre-trained emotion recognition model, and a curated set of songs per emotion, the system delivers a personalized music experience based on how you're feeling.

🚀 Features
-Real-time facial emotion detection using webcam

-Emotion classification with a deep learning model (model.h5)

-Emotion-based song recommendation via .csv files

-Automatic YouTube search and playback using pywhatkit

-Fallback option to manually input mood if camera access is denied

🧠 Supported Emotions
-Angry

-Disgust

-Fear

-Happy

-Sad

-Surprise

-Neutral


🎵 How to Run the Emotion-Based Song Recommendation Project
📁 Step 1: Download the Project
->Go to the GitHub link.

->Click on "Code" → "Download ZIP".

->Extract the ZIP file to your computer.

🐍 Step 2: Install Python
->Make sure Python 3.8 to 3.10 is installed.

->If not, download and install from https://python.org.

💻 Step 3: Open Terminal / Command Prompt
->Go to the folder where you extracted the ZIP.

->Right-click → Open in Terminal (or use cd path/to/folder).

✅ Step 4: Install the Required Libraries
->Run this command:
pip install -r requirements.txt

📂 Step 5: Check Files
->Make sure the following are present:

->main.py file

->model.h5 file

"Song_Names folder with CSV files (like Happy.csv, Sad.csv)"

▶️ Step 6: Run the Project
Now run:

->python main.py

📷 Step 7: Use the App
->A webcam window will open.

->Press the Q key to take a photo.

->It will detect your emotion and play a matching song on YouTube.

❌ To Exit
->After the song, press Enter to play another song.

->Or type x and press Enter to stop the app.

