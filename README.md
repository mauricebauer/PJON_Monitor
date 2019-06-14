![PJON](http://www.gioblu.com/PJON/PJON-github-header-tiny.png)
# PJON® Monitor
A PJON® Application to **receive and send messages** from a user-friendly GUI.

At the moment this application is only a **concept** and we are searching for the right technology-stack. Suggestions are welcome.

## Feature-suggestions for the first version
- Support SoftwareBitBang strategie
- Receive messages and show them sorted by time
- Send PJON messages from the GUI
- Analyze each message in detail (e.g. show Header-Bits)

## Feature-suggestions for the future
- Support different bus strategies
- Save and load a project (e.g. for saved device names)
- Support multiple busses at the same time

I think the key to success in the PJON®-Community is to use **easy available hardware** as the gateway to the bus. So for SoftwareBitBang I think an Arduino is the way to go (sure it is not that fast). In the future I can imagine using an ESP8266 connected to the bus (e.g. in a switch cabinet) and connect to it and log over WiFi.