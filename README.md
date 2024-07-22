
# SafeHouse: Offline-First Smart Home

**SafeHouse** is an offline-first smart home system designed to provide its users with a high level of privacy.

---

## Table of Contents

- [SafeHouse: Offline-First Smart Home](#safehouse-offline-first-smart-home)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [Pursuing User Privacy](#pursuing-user-privacy)
    - [Transparency \& Disclaimer](#transparency--disclaimer)
      - [Data Obfuscation \& Minimization](#data-obfuscation--minimization)
  - [Closing / Review of Concepts / Conclusion](#closing--review-of-concepts--conclusion)
  - [UI/UX Design](#uiux-design)
  - [Features](#features)
  - [Software](#software)
  - [Hardware](#hardware)
    - [Single Board Computer](#single-board-computer)
    - [Laptops for AI Servers](#laptops-for-ai-servers)
  - [Additional Sections](#additional-sections)
    - [Installation and Setup](#installation-and-setup)
    - [Security Measures](#security-measures)
    - [Future Enhancements](#future-enhancements)

---

## Introduction

`SafeHouse` is an `offline-first` `smart home` & `IoT Platform` system that **aggressively prioritizes** `user privacy`. 

### Pursuing User Privacy

In a world where smart home devices are increasingly connected to the cloud, `SafeHouse` takes a different approach. By keeping all data and processing within the `home network`.

`SafeHouse` makes *extensive* & **aggressive** efforts to **minimize** the amount of user data that is revealed to `3rd Party Services`, `Platforms`, & `organizations` of a *wide variety*. 


### Transparency & Disclaimer
The overall goal of `SafeHouse` is to **MINIMIZE** the amount of `data` that is shared with `third parties`.
This is because if you are using a smart home system, you are likely to be sharing a lot of data with `third parties` already.
If your are putting your actual `safety` and `security` in the hands of a """private""" `smart home system`... LOL


`SafeHouse` is designed to be **transparent** about the fact that it is inevitable some `data` from this platform will leak & that data will be shared with `3rd parties`. We try generally try to minimize this, & obfuscate the data that is shared, but it is impossible to eliminate it entirely.

#### Data Obfuscation & Minimization
 We make efforts to **minimize** the amount of worthwhile & valuable data these `3rd parties` can `extract` by
- **Keeping data local** (within the home network)
- **Storing & Spreading Decoy Data** (to confuse `3rd parties` about what data is relevant, making building an overall advertising profile on you more difficult, and your data less valuable!)
  - false identity with fake identity generation

**Why do I have to share data with 3rd parties?**
the `reasons` for sharing that `data` are that you simply must make requests to the internet if you want to have `real time` & **actually relevant** `data` & `information` for your smart home. 




## Closing / Review of Concepts / Conclusion

`SafeHouse` offers a comprehensive set of features and interfaces designed to provide a seamless and secure smart home experience.

---

## UI/UX Design

Users can interact with the SafeHouse environment through multiple intuitive interfaces:

1. **[Web Dashboard](Dashboard.md)**: A comprehensive web interface for managing settings and monitoring home status.
2. **[Voice Commands](docs/UX/Voice)**: Utilize voice control for hands-free operation and convenience.
3. **Physical Interactions**: Incorporate buttons and NFC tags that trigger predefined actions via HTTP requests to the server.

---

## Features

- **Open Source**: Entirely open-source to ensure transparency and community-driven enhancements.
- **Privacy-Centric**: Designed with privacy as a core principle, ensuring user data is protected and secure within the home network.

---

## Software

- **Primary Language**: Python
- **Frameworks and Tools**:
  - [**Langchain**](https://langchain.com) + Integrations
  - [**Litestar**](https://github.com/litestar-org/litestar): for communication across devices

---

## Hardware

### Single Board Computer

Rather than competing with scalpers for the official [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/) and ending up paying over $100 USD per unit, we will use the [Le Potato](https://libre.computer/products/aml-s905x-cc/) by [Libre Computer](https://libre.computer/). These are typically available for about $30 USD on Amazon and can be purchased in units of 10, making it easy to get enough devices for the entire house.

![Le Potato](https://libre.computer/api/products/aml-s905x-cc/gallery/8.webp)

We will be running [Debian](https://www.debian.org/) on the [Le Potato](https://libre.computer/products/aml-s905x-cc/). Other devices will also run Debian-based distros (like laptops and servers).

### Laptops for AI Servers

Hosting services like [Ollama](https://ollama.com) on laptops running Debian.

---

## Additional Sections

### Installation and Setup

(Here you can provide detailed instructions on how to set up the software and hardware components.)

### Security Measures

(Discuss the security protocols and measures implemented to ensure user data privacy and system integrity.)

### Future Enhancements

(Outline potential future enhancements and features to be added to the SafeHouse project.)

---


