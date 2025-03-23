# Vendetta Auto Bot

Automation bot for completing quests in the Vendetta game to earn points and improve your rank on the leaderboard. Supports HTTP, HTTPS, SOCKS4, and SOCKS5 proxies.


## Prerequisites

- Node.js (v16 or higher recommended)
- NPM or Yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/zainarain279/Vendetta-Bot.git
```

2. Navigate to the project directory:
```bash
cd Vendetta-Bot
```

3. Install dependencies:
```bash
npm install
```

4. Create a `.env` file in the root directory with your wallet addresses:
```
WALLETS=["0xWALLETADDRESS1","0xWALLETADDRESS2"]
```

5. (Optional) Create a `proxies.txt` file with your proxies (one per line):
```
http://username:password@host:port
socks5://username:password@host:port
host:port
host:port:username:password
```

## Proxy Support

The bot supports various proxy formats:

- Standard URL format: `protocol://username:password@host:port`
- Host:port format: `host:port`
- Host:port:username:password format: `host:port:username:password`

Supported protocols:
- HTTP
- HTTPS
- SOCKS4
- SOCKS5

If no protocol is specified, HTTP is used by default.

## Usage

Run the bot:

```bash
npm start
```

