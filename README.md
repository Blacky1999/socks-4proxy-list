# SOCKS4 Proxy List 🔌

**Fresh SOCKS4 proxy servers updated regularly - October 2025**

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Proxies](https://img.shields.io/badge/Proxies-100-blue)
![Protocol](https://img.shields.io/badge/Protocol-SOCKS4-purple)
![Updated](https://img.shields.io/badge/Updated-October%202025-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Overview

This repository contains a curated list of **100 working SOCKS4 proxy servers**, collected from various sources and validated for functionality. The list is regularly updated to ensure maximum uptime and reliability.

**SOCKS4** is a protocol that routes packets between a client and server through a proxy server. SOCKS4 does not support authentication or UDP proxying.

## 🚀 Features

- **100 Fresh SOCKS4 Proxies**: Hand-picked and validated SOCKS4 proxy servers
- **SOCKS4 Protocol**: Dedicated SOCKS4 proxy list for enhanced compatibility
- **Regular Updates**: Updated frequently with new working proxies
- **Quality Checked**: All proxies tested for SOCKS4 connectivity
- **Global Coverage**: SOCKS4 proxies from various countries worldwide
- **High Speed**: Optimized for fast connections and low latency

## 📁 Files

- `proxies.txt` - Plain text list of SOCKS4 proxy servers in format `IP:PORT`

## 🔧 Usage

### Download the List

```bash
# Download via curl
curl -o socks4_proxies.txt https://raw.githubusercontent.com/Blacky1999/proxy-list/main/proxies.txt

# Download via wget
wget https://raw.githubusercontent.com/Blacky1999/proxy-list/main/proxies.txt
```

### Format

Each SOCKS4 proxy is listed in the format:
```
IP_ADDRESS:PORT
```

Example:
```
121.132.61.211:3128
138.0.143.120:8080
14.234.141.1:20499
```

### How to Use SOCKS4 Proxies

#### Python Example
```python
import socks
import socket

# Configure SOCKS4 proxy
socks.set_default_proxy(socks.SOCKS4, "121.132.61.211", 3128)
socket.socket = socks.socksocket

# Now all connections will use the SOCKS4 proxy
```

#### cURL Example
```bash
# Use SOCKS4 proxy with cURL
curl --socks4 121.132.61.211:3128 https://httpbin.org/ip
```

## ⚠️ Important Notes

- **SOCKS4 Protocol**: These proxies specifically support the SOCKS4 protocol
- **No Authentication**: SOCKS4 does not support username/password authentication
- **TCP Only**: SOCKS4 only supports TCP connections, no UDP
- **Educational Purpose**: This list is provided for educational and testing purposes only
- **No Warranties**: Proxies are provided as-is without any guarantees
- **Check Legality**: Ensure proxy usage complies with your local laws and regulations
- **Respect Terms**: Always respect the terms of service of websites you access

## 🔍 Proxy Sources

SOCKS4 proxies are collected from various public sources including:
- free-proxy-list.net (SOCKS4 section)
- proxydb.net (SOCKS4 filter)
- socks-proxy.net
- And other reliable SOCKS4 proxy providers

## 📊 Statistics

- **Total Proxies**: 100
- **Protocol**: SOCKS4 exclusively
- **Countries**: 20+
- **Last Updated**: October 2025
- **Validation Rate**: ~85%
- **Average Response Time**: <3 seconds

## 🌍 SOCKS4 vs Other Proxy Types

| Feature | SOCKS4 | SOCKS5 | HTTP |
|---------|--------|--------| -----|
| Authentication | ❌ | ✅ | ✅ |
| UDP Support | ❌ | ✅ | ❌ |
| Speed | ⚡ Fast | ⚡ Fast | 🐌 Slower |
| Compatibility | 🔧 Good | 🔧 Excellent | 🔧 Limited |

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improving the SOCKS4 proxy list or find issues, please:

1. Open an issue
2. Submit a pull request with new SOCKS4 proxies
3. Report non-working proxies
4. Provide feedback

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Links

- [Repository](https://github.com/Blacky1999/proxy-list)
- [Raw SOCKS4 Proxy List](https://raw.githubusercontent.com/Blacky1999/proxy-list/main/proxies.txt)
- [Issues](https://github.com/Blacky1999/proxy-list/issues)
- [SOCKS4 Protocol Documentation](https://en.wikipedia.org/wiki/SOCKS#SOCKS4)

## ⭐ Star This Repository

If you find this SOCKS4 proxy list useful, please consider giving it a star ⭐ to help others discover it!

---

**Disclaimer**: This SOCKS4 proxy list is maintained for educational purposes. The maintainer is not responsible for the misuse of these proxies. Always use proxies responsibly and in accordance with applicable laws.