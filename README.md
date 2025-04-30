# Light Controll

This is a remote light controll UI

# Installation

There was no usage of a package manager (pip) but packages needed are found inside the python script files.

# Usage

If you have mosquitto installed in your PC, type this is the terminal

For starting the mosquitto service

```bash
mosquitto
```

For running the server or publisher script

```bash
py server.js
```

For running the client or subscriber script

```bash
py subscriber.js
```

# Frontend

Open the html file with live server and test the program. Make sure you have you embedded setup ready.

# Empasis

Make sure to set 'COM4' to '/dev/ttyUSB0' in subscriber.py if you are using linux.

```bash
ser = serial.Serial('COM4', 9600)
```
