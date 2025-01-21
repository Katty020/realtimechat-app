<h1>Real Time Chat App</h1>

This is a real-time chat application that allows you to chat with others in real time.

## Features
- Tech Stack- React+Vite , Framer Motion, Dasiy UI
- User authentication with JWT :lock:
- Real-time messaging with Socket.io :speech_balloon:
- State management with Zustand :clipboard:
- Styled with Tailwind CSS :nail_care:

## :book: Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Katty020/realtimechat-app.git
   ```

2. Navigate to the project directory:

   ```
   cd react-chat
   ```

3. Install the dependencies for both client and server folders:

   ```
    cd client && npm i && cd ../server && npm i && cd ..
   ```

4. Create a .env file in the server directory and add your environment variables. You can use the .env.example file as a template:

   ```
   cp server/.env.example server/.env
   ```

   Modify the `.env` file with your environment-specific variables.

5. Start the client:

   ```
   cd client && npm run dev
   ```

6. Open another terminal, navigate to the project directory, and start the server:

   ```
   cd server && npm run dev
   ```

7. Open your browser and visit http://localhost:5173.

8. Start chatting in real-time! :wink:


## 🖼️ Screenshots

![Login](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALYAAACjCAMAAAAQNRQeAAAAb1BMVEX///8AAAAgICCGhobc3Nzn5+fAwMDw8PBra2tvb2/R0dHq6ur09PTNzc0+Pj4kJCQrKyswMDCurq5LS0uioqKNjY3W1tZ4eHipqalcXFxVVVXh4eFlZWW6urqlpaXGxsZBQUGAgICYmJgvLy83NzcxTmeIAAADkUlEQVR4nO2c63LiMAyFHUNLQ4CUW4FSCmV5/2fc2ZmSDYkUS45N5Bmd37HO1zQJtiXLGJVKpVKpVCqVSqWiazpa2E69tccUq90NH1AWLYuOqxELB/S7zRxqBV0tHWMeuX0sHFo5I/4L+vJI4R6R97Nw6UgJmWX1mFvKkLyXhVNrUsh6zB8SRd7HwqkZ7U7UYpL+43VsvoVbc1rI/zEnRIjc34KgDTfmJ3FA7m9B0JYZk/h61bG5FhSNmDG/iNfXsLkWEbCpr5cw7DOVWhb2Lk3sMk1s8qMtCrsgU4vCniaG/TurPEXEZk1caTHvc/hvMrUtPC16YKMrpivs2L0o41n0wP7g/ZHTkBY9sMesq133iWfxNOxTmtiOZ0QqtotAsRVbsRVbsRU7ALZrViQUe54m9ipN7J14bHAX8o94bHDP106kY8Mr9410bHifxErHnoDY2VU4NrIHaJs5X2nYSK7uJhx7BWN3frsFYGPpPXsWjW0WyO22M9HYc2xjfi0a2yyx270VjT3FbrfF5t1Pw+6c+KMJ1TKYhSd29+Yzmi07BLPww26b1IN+oI/JPpRFIOzHxApavQOnX4bL3TTSWGg5zjKYRQzsGfp456EsYmDjPzr2VTK2GaHc7R95Qdjmgl14EY2N1sO0f+QlYZszyt1MQYnCxqsYy1koixjY6NQ7+xSNjRYy2k0oixjY5oRyHyVj4wVfy2AWMbDNDbt8F8wiBnaBPibjUBa9sLGFOVoVvQhm0QP78R2r6w0bMQ9mQcYevTbUsceHreQv4Syo2Jxl9Qu2T1VxiNhwaGmPcFe7xzKxzQHGfheObeBTONWXQSo2skS7f0ukYiMr+fuESiw2fETlvl8jFhtO6VzEY4Mfk3veTy72Pk1sMM0qH/uYJjZ4ZkE+NpjUVmzFVmzFVmzFVmzFVmzFload6Hx7nCY2XCD9bGxuIVMBFmp0Yj+5VuoAdleCgnRjP7dW6kBvK1Bl+YavlRozqKs6zOFrpcAvBqadl8Xg2N9pYnduy4vFrs61JIbtZzE0du5nMTT23M9iYGzraUETr8UWA/vqaUETtVEKF7t2YCtGzzRqfysmtq210YjRoY7XrI+Kbb+8LYhitUakYq/9LYhiNaKkYdvGIQWs5KQPNqvtJ2nialtnmiN0FuU1WXUuE2wJHZ6M0MfVsLrmwouyX93yPXbLfBrzqlQqlUqlUqlUKpVKpVLF0F9+jEMSvsdQNwAAAABJRU5ErkJggg==)
![Login](screenshots/signup.png)
![Login](screenshots/chat.png)
