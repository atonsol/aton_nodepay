# Nodepay Automate with Proxies | Bypass Version!
Automate farming Nodepay Network using proxies. Please use the bypass version. I found Nodepay's real IP host to make farming easier without being blocked by Cloudflare protection.
### Tools and components required
1. Nodepay Account | Register: https://app.nodepay.ai/register?ref=dcqoItKejQYYMSy (Please use this link instead! xD)
2. VPS (OPTIONAL) and Python3
# Setup Tutorial
- Open [Nodepay](https://app.nodepay.ai/register?ref=dcqoItKejQYYMSy) and login to dashboard
- Press F12 or CTRL + SHIFT + I
- Select Console
- At the console, type ```allow pasting``` and press enter
- image
- Then type ``localStorage.getItem('np_token')`` and press enter
- image
- The text that appears is your nodepay token and copy the text
### Component installation
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix:
```bash
apt install python3 python3-pip -y
```
- Install requirements: 
```bash
pip install -r requirements.txt
```
### Run the Bot
- Replace the proxies example in ```proxy_list.txt``` to your own proxies, please use only 10 proxies with proxies http only.
- Replace the token in ```token_id.txt```, please use only 1 token.
#### Run command
- Run for original server:
```bash
python run.py
```
- Run for bypass server:
>Use this script if you getting errors like ```Error during API call: 403 Client Error: Forbidden for url``` 
```bash
python run-bypass.py
```
- Press Enter then insert your nodepay token
# Operating status
If the following log appears, it means it is running successfully.
```bash
2024-07-30 04:37:18.263 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 88}}
2024-07-30 04:37:48.621 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 90}}
2024-07-30 04:38:18.968 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 94}}
2024-07-30 04:38:59.338 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 98}}
```
# Notes
- Run this bot, and one account only can connect with 10 Proxies.
- Feel free to enjoy and recode or create new bots using the Nodepay API with direct IP that I found.
