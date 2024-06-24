
# SafeHouse: Offline-First Smart Home

**SafeHouse** is an offline-first smart home system designed to provide its users with a high level of privacy.

---

## Table of Contents

1. [Introduction](#introduction)
2. [UI/UX Design](#uiux-design)
3. [Features](#features)
4. [Software](#software)
5. [Hardware](#hardware)
    - [Single Board Computer](#single-board-computer)
    - [Laptops for AI Servers](#laptops-for-ai-servers)

---

## Introduction

**SafeHouse** is an offline-first smart home system that prioritizes user privacy. It offers a comprehensive set of features and interfaces designed to provide a seamless and secure smart home experience.

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


