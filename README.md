[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) ![](https://img.shields.io/badge/Python-snap7/telegram-blue)
<p align="center">
  <img src="telegram.jpg" width="1000" height="400">
</p>

# Pyemens
<sub>Python program used to communicated an Telegram Bot with Siemens S7-1200 1214</sub>

Bot created to test the `snap7` library together with an telegram bot for information exchange between the PLC and an Smartphone.
This project was an concept to show that's possible to perform, but the final development wasn't approved by the custumer.

The idea is an simple project that reads an specific `DB` of the PLC, retrieving the information by the GET/POST communication already enabled on Siemens PLC.
It was able to sent and alarm if the current temperature ( simulated, during the test) exceeds 100ºC, as also shows the status of an given byte and the current status of two buttons.

The application was tested with only one user, tests with extra users were not performed.

The project showed that it's viable to perform and execute this kind of solution, even for simple automations. There are some improvements that are possible to be applied to better suit each different aplication.

Access the notebook : [Here!](https://colab.research.google.com/github/Lessinger/Pyemens/blob/main/Pyemens.ipynb)






---
[![author](https://img.shields.io/badge/author-lessinger-green)](https://www.linkedin.com/in/guilherme-lessinger/) 
