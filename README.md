# Centic Auto Claim Tasks
![banner](image.png)

This script automates claim tasks to earn the Centic Points (CTP)

## Features

- **Auto Claim Quest**
- **Auto Claim Daily Reward**
- **Support multiple accounts**
- **Support Proxy usage**

## Prerequisites

- Node.js installed on your machine
- `tokens.txt` file containing token apikey from centic platform follow instruction below to get:
- Open centic platform [https://centic.io/quests/](https://centic.io/quests/daily?refferalCode=eJwFwQEBACAIA7BKgKgQ53jJYHw3eShrp_kAkcJlJ3FTJYydjdi4CJ31AQtpDFY=)
- Login With your wallet
- inspect or just F12, and find Application
- in local storage find `apiKey_` and copy all value.
![Apikey](image-1.png)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Zlkcyber/centicBot.git
    cd centicBot
    ```

2. Install the required dependencies:
    ```sh
    npm install
    ```
3. Input your centic apikey in `tokens.txt` file, one user per line;
    ```sh
    nano tokens.txt
    ```
4. optionally you can use proxy: 
- paste proxy in `proxy.txt` format `http://username:password@ip:port` 
    ```sh
    nano proxy.txt
    ```
5. Run the script:
    ```sh
    npm run start
    ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
