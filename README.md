![PJON](http://www.gioblu.com/PJON/PJON-github-header-tiny.png)
# PJON® Monitor
A PJON® Application to **receive and send messages** from a user-friendly GUI.

![CI](https://github.com/mauricebauer/PJON_Monitor/workflows/CI/badge.svg?branch=master)

![Mockup](https://docs.google.com/uc?id=1cjngjnUMiB0Q5b4Du5QqewDXpAili5-v "Mockup")

At the moment this application is only a **concept** and we are searching for the right technology-stack (my idea was to use C#+WPF but then the application will be Windows only, the alternative in my mind could be [Electron](https://electronjs.org/)). Suggestions are welcome.

## Feature-suggestions for the first version
- Support SoftwareBitBang strategy
- Receive messages and show them sorted by time
- Send PJON messages from the GUI
- Analyze each message in detail (e.g. show Header-Bits)

## Feature-suggestions for the future
- Support different bus strategies
- Save and load a project (e.g. for saved device names)
- Support multiple busses at the same time
- Identify repetitions in packets (and count them)
- Track induced interference

I think the key to success in the PJON®-Community is to use **easy available hardware** for the gateway to the bus. So for SoftwareBitBang I think an Arduino is the way to go (sure it is not that fast). In the future I can imagine using an ESP8266 connected to the bus (e.g. in a switch cabinet) and connect to it and log over WiFi.
