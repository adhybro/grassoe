# Grassoe
This repository contains the code for getgrass-bot, a bot designed to establish WebSocket connections through various HTTP and SOCKS proxies, specifically aimed at farming for Grass Airdrop Season 2

# Overview
getgrass-bot connects to a specified WebSocket server using both HTTP and SOCKS proxies. It leverages the ws library for WebSocket communication and integrates the https-proxy-agent and socks-proxy-agent libraries for enhanced proxy support. This allows for more versatile and resilient connections, accommodating a wider range of proxy types.

# Register Grass
https://app.getgrass.io/register/?referralCode=TmqOXFVOjMzXujq

## Installation

To install this project, follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/adhybro/grassoe.git
    ```
2. Navigate to the project directory:
    ```bash
    python3 -m venv grassoe
    source grassoe/bin/activate
    pip install -r requirements.txt
    ```
3. To run the getgrass-bot, execute the following command in your terminal:
    ```bash
    python3 main.py
    ```

   


