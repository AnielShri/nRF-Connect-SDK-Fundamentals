# nRF Connect SDK Fundamentals

Repository to get familiar with NRF hardware and Zephyr

More information here: https://academy.nordicsemi.com/courses/nrf-connect-sdk-fundamentals/

## Hardware
Hardware used for exeperiments is development board nRF7002-DK

* https://www.nordicsemi.com/Products/Development-hardware/nRF7002-DK
* https://developer.nordicsemi.com/nRF_Connect_SDK/doc/2.2.99-dev3/nrf/ug_nrf7002_gs.html

## Issues
* Failled to install SDK using VScode: https://devzone.nordicsemi.com/f/nordic-q-a/107146/installing-sdk-v2-5-1-failing-after-step-zscilib


# Lesson 1 – nRF Connect SDK Introduction
Relevant downloads

* nRF Command Line Tools
	* https://www.nordicsemi.com/Products/Development-tools/nRF-Command-Line-Tools/Download?lang=en#infotabs

* Segger J-link. NOTE: *Optional*, should be installed through `nRF Command Line Tools`, but in case of failure, use link below
	* https://www.segger.com/downloads/jlink/

* nRF Connect for VS Code Extension Pack. NOTE: install the pack => will add additional, related extensions
	* Use VScode extensions interface
	* Relevant changes in path location:
		* nrf-connect.toolchainManager.installDirectory
		* nrf-connect.toolchain.path
		* nrf-connect.topdir
		* kconfig.python

* Install toolchain using the NRF Connect extension
	* Click on  `Install Toolchain`
	* https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/installation/install_ncs.html#install-a-toolchain

*  Install nRF Connect SDK
	* In nRF Connect for VS Code, click on `Manage SDK` => `Install SDK`
