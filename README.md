# Simulating processes on MOSIP 
MOSIP ([mosip.io](http://mosip.io)) is a technology platform which helps governments and other organizations implement a digital, foundational identity system in a cost-effective way.

To help explore and understand MOSIP's operational behaviour, this repository will contain code for simulating a user interacting with the system. In particular, we focus on the [pre-registration journey](https://docs.mosip.io/platform/modules/pre-registration), where we simulate interactions with the pre-regitration UI using [Selenium](https://www.selenium.dev/). This approach may be used to [identify key operational data tap points](https://github.com/alan-turing-institute/mosip-data-extraction) in the MOSIP database schema. A further aim of this repository relates to the development of anomaly detection capabilities. For the latter purpose, the code contained herein enables the simulation of pre-registration transactions, where dwell-times along the pre-registration journey are sampled from pre-configured statistical distributions. In this way, it is possible to simulate different users with pre-defined behavioural categories interacting with the system.

These repositories are currently private but can be accessed on request. We will be releasing these publicly in due course. For the time being, please request access by opening a new [support issue](https://github.com/alan-turing-institute/mosip-data-extraction/issues).
