Setup:

boblight.conf put in the hidden folder /etc in your root folder.

Arduino IDE will run the ambilight.ino.

boblightd 2 run in terminal

Plugin XBMC boblight is installed in XBMC. Settings- addons- all addons- services- xbmc boblight

Boblight settings inside a movie  by pressing ”n”
lägg till OSX:

http://mirrors.xbmc.org/build-deps/addon-deps/binaries/libboblight/osx/libboblight-osx.0.dylib.zip

And extract it into the directory "/Users/<your_user_name>/Library/Application Support/XBMC/userdata/addons/script.xbmc.boblight/resources/lib"

dvs filen libboblight-osx….

- script.xbmc… läggs i userdata/keymaps

Steg efter installation:

1. Ladda upp kod till arduino
2. kör boblightd i terminalen
3. starta xbmc (går att ha det igång alltid) 
4. PROFIT!

App to control the lights:
https://play.google.com/store/apps/details?id=com.mitjahenner.bobdroid&hl=sv


OBS: ljusslingan måste vara av en viss sort, den med endast gnd och en input. Finns de med två input också, därför går ej kod från adafruit användas.
