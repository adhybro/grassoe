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

   ## Usage

1. Obtain your user ID from the Getgrass website:

   - Visit [https://app.getgrass.io/dashboard](https://app.getgrass.io/register/?referralCode=TmqOXFVOjMzXujq).
   - Open your browser's developer tools (usually by pressing F12 or right-clicking and selecting "Inspect").
   - Go to the "Console" tab.
   - Paste the following command and press Enter:

     ```javascript
     localStorage.getItem('userId');
     ```

2. To specify proxies, create a file named `proxy.txt` in the project directory and add your desired proxy URLs, following the same new-line >

   ```text
   http://username:password@hostname:port
   socks5://username:password@hostname:port
   ```

3. To run the `getgrass`, execute the following command in your terminal:

   ```bash
   python3 main.py
   ```


   


