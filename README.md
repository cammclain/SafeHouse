
# SafeHouse: Offline-First Smart Home

**SafeHouse** is an offline-first smart home system designed to provide it's users with a high level of privacy.


# UI/UX

Users of devices can interface with the smart home & its functionality using 3 primary methods

1) web dashboard 
2) voice commands 
3) it would be cool to have buttons and or NFC tags that when tapped send an HTTP request to the server to do XYZ

## Features:

- **Open Source From the Ground Up**:
- **Privacy** Focused!

## Software
- **Python**: The application will be primarily written using Python
- [**Langchain**](https://langchain.com) + Integrations
- [Litestar](https://github.com/litestar-org/litestar): for communication across devices

## Hardware

## Single Board Computer
Rather than compete with scalpers for the official [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/) & end up paying over $100 USD per unit, I am going to use the [Le Potato](https://libre.computer/products/aml-s905x-cc/) by [Libre Computer](https://libre.computer/) 
These are typically available for about $30 USD on Amazon, and available in units of 10 making it easy to get enough devices for my house.

![[8.webp]]

We will be running [Debian](https://www.debian.org/) on the [Le Potato](https://libre.computer/products/aml-s905x-cc/)

Other devices we will be using will be running Debian based distros (like laptops and servers)

### Laptops for AI servers
hosting stuff like [Ollama](https://ollama.com) on laptops running Debian
