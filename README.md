# ElevateLabsDay8
Task 8: Working with VPNs

What is a VPN?
A Virtual Private Network (VPN) is a secure service that creates a private tunnel between your device and the internet. It hides your IP address, encrypts your data, and protects your identity and online activity from hackers, ISPs, and even governments.

Why Use a VPN?
To enhance privacy by hiding your IP and browsing activity.
To access blocked content in different countries.
To stay safe on public Wi-Fi (e.g., in airports or cafés).
To prevent data tracking by advertisers and ISPs.
To secure remote work and sensitive communications.

How a VPN Works:
You connect to a VPN server located anywhere in the world.
Your real IP address is replaced by the VPN server's IP.
Your internet traffic is encrypted, making it unreadable to outsiders.
Websites see the VPN’s IP, not yours.
This adds a layer of anonymity and protects your digital footprint.

Common VPN Security Protocols
Protocol	Features
OpenVPN	Open-source, strong encryption, stable
WireGuard	Fast, modern, lightweight
IKEv2/IPSec	Great for mobile users, stable reconnecting
L2TP/IPSec	Layered tunneling with basic encryption
SSTP	Secure but Windows-only

Key VPN Features
AES-256 encryption (military-grade protection)
No-log policy (VPN does not store your data)
Kill switch (blocks internet if VPN disconnects)
Split tunneling (only route certain traffic through VPN)
DNS leak protection (prevents ISP from seeing visited sites)

Practical Steps – Monitor VPN Behavior
Step-by-Step: Verify IP Address Change

Before VPN Connection:

![image](https://github.com/user-attachments/assets/935a60b6-d869-4b1b-920b-7c4bc15a299e)


Visit https://www.whatismyipaddress.com
Note your current IP address and location.
Connect to the VPN Server:
Open your VPN app and select any server (preferably closest for speed).
Wait for the VPN to establish a secure connection.

After VPN Connection:
Refresh https://www.whatismyipaddress.com
You should now see a different IP address and location, confirming traffic is routing through the VPN.

![image](https://github.com/user-attachments/assets/2cefe0b1-c32f-4a21-b553-7d8e7962b767)


Browse Securely:
Visit secure websites (HTTPS) and ensure the lock icon appears.
You’re now browsing with encrypted traffic and hidden IP.

![image](https://github.com/user-attachments/assets/d1e07b26-fc5a-45d7-ab0a-2d8ac829744f)

Step-by-Step: Run Internet Speed Test (Using Ookla)
Open your browser and go to https://www.speedtest.net
Click “Go” to start the test.
Wait for the test to measure:
Ping (latency)
Download speed
Upload speed
Record the values while connected to VPN.
Now, disconnect the VPN and repeat the speed test.
Compare the results to see how VPN affects performance.
With VPN:

![image](https://github.com/user-attachments/assets/a8003fba-d3a9-47dc-a0cc-69d188d646e9)

Without VPN:

![image](https://github.com/user-attachments/assets/fa79cba0-b983-49fc-9120-0833803316e8)

Why This Matters:
VPNs may slightly reduce speed due to encryption and rerouting, especially if the server is far from your location.

VPN Benefits
Hides your IP address and device location
Encrypts your internet traffic for data security
Allows access to geo-blocked websites and apps
Protects your data on public Wi-Fi
Prevents ISP tracking and bandwidth throttling

VPN Limitations
May reduce internet speed slightly
Free VPNs might collect and sell user data
Limited servers or data caps on free versions
Doesn’t protect against viruses or malware
Not 100% anonymous – browser fingerprinting and cookies can still track you
