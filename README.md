
# IP Spoofing Tester v1.0 for Linux

## About the project

This image will run the CAIDA Spoofer (http://spoofer.caida.org/) to measure the Internet's
susceptibility to spoofed source address IP packets.

## Running

```
  docker login
  docker run --network=host -it --rm zmaximo1990/caida-spoofer-test
```

## Feedback

Currently maintained by Máximo Zarza (zmaximo1990@gmail.com) and Matias Silve (matiasnicolas.silva@gmail.com)
at UNLP (Universidad Nacional de La Plata).
Feedback, improvements and bugfixes are welcome.