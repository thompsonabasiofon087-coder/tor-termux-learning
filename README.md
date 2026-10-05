# Tor + Termux Learning

My hands-on learning project for Tor, Termux, and privacy-focused networking.

## Setup Status

- ✅ Termux installed
- ✅ Tor installed
- ✅ Tor SOCKS5 proxy tested
- ✅ Tor Browser installed
- ✅ Tor connection verified

## Tor Verification

I tested the Tor connection with:

```bash
curl --socks5-hostname 127.0.0.1:9050 https://check.torproject.org/api/ip
The response confirmed that the connection was using Tor:
{
  "IsTor": true
}
I also successfully tested HTTP traffic through the Tor SOCKS5 proxy.
## What I'm Learning

- How Tor works
- How SOCKS5 proxies work
- How `.onion` services work
- Privacy-focused networking
- How to use Tor safely with Termux
