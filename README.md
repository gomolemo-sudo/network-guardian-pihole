# network-guardian-pihole
A home lab project using Pi-hole to block ads, protect privacy, and learn Linux networking.

# Network Guardian – Pi-hole Home Lab

Network Guardian is a home lab project where I built and deployed a Pi-hole DNS server to block ads, improve privacy, and better understand Linux networking and DNS fundamentals.

This project was done using an old laptop running Ubuntu Server and tested from a Windows 11 client.

---

## What I Built

- A working Pi-hole DNS server
- Network-wide ad and tracker blocking
- DNS traffic monitoring via the Pi-hole dashboard
- Router and client DNS configuration
- Hands-on Linux command-line experience

---

## Tech Stack

- Pi-hole
- Ubuntu Server
- Linux CLI
- DNS
- Home network router
- Windows 11 (client testing)

---

## How It Works

1. Pi-hole runs as the network DNS server  
2. All DNS requests pass through Pi-hole  
3. Ads and trackers are blocked before they load  
4. Traffic and stats are visible on the web dashboard  

---

## Challenges Faced

- USB installer not booting at first
- DNS not resolving correctly on initial setup
- No blocked queries showing due to misconfigured DNS
- Learned how to properly assign the server IP as DNS

Each issue helped me better understand networking and troubleshooting.

---

## Results

- Ads successfully blocked across devices
- DNS queries clearly visible in the dashboard
- Improved network privacy
- Stronger confidence with Linux and networking concepts

---

## Future Improvements

- Add Unbound for encrypted DNS
- Run Pi-hole in Docker
- Add monitoring dashboards
- Configure a VPN to use Pi-hole outside the home network

---

## Documentation

Full build documentation is available here:  
📄 `docs/Network_Guardian_Building_Pi-hole.pdf`

---

## Why This Project Matters

This project strengthened my real-world troubleshooting skills and gave me hands-on experience with DNS, Linux servers, and home lab environments — all essential for IT support and cloud roles.
