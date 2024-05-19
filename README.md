# LAN-Multiplayer-Game

## Introduction

This project represents a foray into the integration of computer networking and game development, aiming to create a LAN-based gaming platform. The platform enables two players to engage in classic games like Connect 4, Tic Tac Toe, and Hangman. The implementation leverages a client-server architecture to facilitate real-time interaction and gameplay synchronization.

## Features

- **Classic Games:** Play Connect 4, Tic Tac Toe, and Hangman.
- **Client-Server Architecture:** Real-time interaction and synchronized game states.
- **Secure Authentication:** Ensures verified player access before game sessions.

## Architecture Overview

### Client-Server Model

- **Client:** Each player acts as a client, connecting to the central server.
- **Server:** Coordinates game sessions, manages player authentication, and maintains consistent game states across clients.

### Authentication System

- A secure authentication system verifies player access before game sessions begin, adding an essential layer of security and integrity to the gaming experience.

## Technical Implementation

### Networking

- **Protocol:** Utilizes TCP/IP for reliable communication.
- **Synchronization:** Ensures real-time updates and consistent game states across all clients.

### Game Logic

- **Connect 4, Tic Tac Toe, Hangman:** Implemented with robust game logic to handle various gameplay scenarios.
- **Turn-based System:** Manages player turns and enforces game rules.

### User Interface

- **Design:** User-friendly interfaces for each game.
- **Feedback:** Real-time feedback on game progress and outcomes.
