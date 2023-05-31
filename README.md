<img src="https://github.com/MirkokriM/42_Common_Core/blob/main/README.FILE/MirkokriM_github42_Minitalk.png">

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)

## Introduction

Minitalk 42 is a client-server application that enables communication between two processes, a sender and a receiver, using signals. The communication is performed in real-time and allows for the exchange of text messages.

The sender and receiver can be executed on the same machine or different machines connected over a network. The Minitalk 42 project provides a simple and efficient way to exchange data between processes without the need for complex network configurations.

## Features

- Real-time communication between two processes using signals.
- Efficient and lightweight implementation.
- Supports communication between processes on the same machine or over a network.
- Text-based communication, allowing for the exchange of messages.

## Requirements

To run the Minitalk 42 project, you need the following requirements:

- Unix-like operating system (e.g., Linux, macOS)
- C compiler (e.g., gcc)

## Installation

To install and use the Minitalk 42 project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/MirkokriM/Minitalk.git
```

2. Change to the project directory:

```bash
cd Minitalk
```

3. Build the project:

```bash
make
```
<img src="https://github.com/MirkokriM/Minitalk/blob/main/README.FILE/Mini-Make-re-talk.gif">
## Usage

To use the Minitalk 42 application, follow these steps:

1. Start the receiver process:

```bash
./server
```

2. Start the sender process with the receiver's PID (Process ID) as an argument with the message you want to send:

```bash
./client <server_pid> <"Message">
```

3. Press Enter to send the message to the receiver.

4. The receiver process will display the received message, while in the sender process you will see a message confirming receipt of the message.

5. To terminate the application, press Ctrl+C in both the sender and receiver processes.

## Example
<img src="https://github.com/MirkokriM/Minitalk/blob/main/README.FILE/Minitalk%20is%20SUS.gif">
