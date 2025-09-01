# Spring Boot Actuator

## Overview

**Spring Boot Actuator** extension allows users to check Spring Boot Actuator's mostly used monitoring URLs including Info, Metrics, Heap dump and Thread dump to provide detailed status and data for a specified application by fetching information from the given URL.

## Features
* Easy to use 
* Configurable: Users configure the component by entering:
    * Application Name
    * URL
    * Selection of checkboxes for the following: **Info**, **Metrics**, **Heap Dump** and **Thread Dump**


## Functionality
The component calls the provided URL to retrieve application status information and then displays the following information:

* Application Name
* Application Version
* Status (Up/Down)
* For each selected checkbox, a link is displayed for detailed information.