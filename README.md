# Evie
## So you don't have to feel lost
### Personal assistant to guide you through your visit in Tieto Intelligent buildings

This is the sum up of everything we managed to create during Junction 2016 Hackathon

### Team:
 - Axel Auvinen
 - Leo Lahti
- Samu Saukkonen
- Rosa Suominen



## Code summary
### Front End - Evie
Built with Ionic 2, using Angular 2. In production level ought to be PWA, website and Mobile app

### Peer Server - WebRTC Video call Server
NodeJS socket server to transmit data from enduser to another

### Collector - Data collecting and serving
NodeJS server to collect sensor data, pushing it into RethinkDB and serving it to client