# stream-u
Simple Realtime Streaming Web Application

# Installation
Simply run `npm run setup`

# OBS Setup
1. Download OBS Studio App from [here](https://obsproject.com)
2. Install it on your desktop
3. Create a new scene
4. Add your input display and input audio into your new scene
5. Adjust your stream key in Settings => Stream => Choose Service as Custom
6. Set the Server url to `rtmp://localhost/live` and stream key to your stream id
7. Click OK and then click Start Streaming

# Run The App
1. Run the server with command `npm run start-server`
2. Open a new command line and run `npm run start-client`
3. And then open another new command line and run `npm run start-rtmp`
4. Open your browser

# ScreenShots
![Screenshot1](https://drive.google.com/uc?export=view&id=1nN-e-cC2uy7q0UDi3FdbadTHlx4qwFMn "StreamU")