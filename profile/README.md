# Welcome to the MrBuggy organization 🏎️

This is the home of (most of) the code, protocols and utilities we have used and are still using in the NXP cup EMEA, the autonomous car racing competition in which we are contending for the Vrije Universiteit Amsterdam.

Most of our code so far is written in Go and Python3, and we are currently in the process of porting everything to Go because it is nice and fast. We also previously worked from a monorepo setup but are mgirating to an organization multi-repo setup.

## If you want to sponsor us

Looking for a way to promote your brand? Or do you want to help some poor students out? Send an email to mrbuggy@ielaajez.com and we can definitely work something out.

## Roadmap 🛣️

We will gradually open source our software after a clean up and inspection. 

### i2c drivers

- [X] pca9685 16-channel PWM controller [published](https://github.com/MrBuggy-Amsterdam/go-pca9685driver)
- [X] urm09 ultrasonic ranging sensor [published](https://github.com/MrBuggy-Amsterdam/go-urm09driver)
- [ ] ads1100 analog to digital converter
- [ ] mpu6050 accelerometer

### Utilities

- [ ] PWM_reset: reset PWM values using the pca9685 board
- [ ] PWM_tune: set custom PWM values using the pca9685 board

### Protocols

- [ ] High-level overview of the wireless control mechanism to view livestream, control the car and adjust tuning parameters on the fly

### Forwarding server

- [ ] The bi-directional forwarding server that is the middle man in communication between client (a laptop) and the core (the car)

### Controlling client

- [ ] The web aplication that is used to view the livestream and sensoric data, and adjust tuning parameters

### Remote control

- [ ] The PS4 remote-control application that can be used to control the core (the car)

### The core

- [ ] The core application running on the car, the brain behind the autonomous driving
