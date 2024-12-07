<p align="center">
  <h1 align="center">SecureVehicleReservation</h1>

  <p align="center">
    A Web-Based Secure Vehicle Reservation System
  </p>
</p>

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Setup Guide](#setup-guide)

## Overview

SecureVehicleReservation is a web-based application that enables users to book vehicle services securely, prioritizing data privacy and user convenience.

## Requirements

* [Java EE SDK](https://www.oracle.com/java/technologies/java-archive-eesdk-downloads.html)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download/?section=windows)

## Setup Guide

### Steps to Build and Deploy
1. Clone this repository.
   ```sh
   git clone https://github.com/ashenrashmike2000/Web-Based-Secure-Vehicle-Reservation-System.git


2. Open the project in IntelliJ IDEA and set up the development environment.

3. Install dependencies listed in the pom.xml file.

4. Update the config.properties file in the src/main/resources directory with:

    Credentials from your Auth0 Identity Provider (IDP).
    MySQL database connection details.

5. Configure your application server (e.g., Apache Tomcat 9.0.80).

6. Deploy the application to the configured server.

7. Access the web application at http://localhost:8080 (port may vary based on your configuration).