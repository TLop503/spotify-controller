# Spotify Controller

This is the code to go along with a youtube video you can watch [here](https://youtu.be/SWiPIBWvgIU).

This code is for a device that will control spotify using their web api.

## Set up steps

1. Go to https://developer.spotify.com/documentation/web-api and follow the instructions there to create an app.
2. In the app you have created there is a client_ID and client_Secret, copy these values into the spotify_buddy.ino at lines 62 and 63.
3. While you are editing that code also change the WIFI_SSID and PASSWORD on lines 58 and 59 to your local wifi name and password.
4. Upload the code
5. Once thats done you can start the device and it will display an IP on the screen. Write this down.
6. In the code change the YOUR_ESP_IP on line 64 to the ip you wrote down.
7. Go back to the spotify set up and copy line 64 of the code (""http://YOUR_ESP_IP/callback") into the Redirect URIs section of your app setting page.
8. Upload the code again and when the device starts go to the ip in a browser and follow the instructions. Everything should now work!

