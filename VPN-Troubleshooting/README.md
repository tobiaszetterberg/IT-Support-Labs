# VPN Troubleshooting – Service Desk Lab

## Scenario
A remote user lost their VPN connection and could no longer access internal company resources.

![VPN ticket](images/vpnsupportticket.png)

## Environment
Simulated service desk environment.

## Problem
VPN disconnected and would not reconnect.

## Business Impact
The user was working remotely and could not access internal resources.

## Troubleshooting Steps
1. Remote to client computer.
   
![VPN ticket](images/remotedesktop.png)
2. Confirmed the issue was related to the VPN connection by checking the client's VPN software.
3. Confirmed the VPN was indeed disconnected, and I was not able to connect.
4. Opened Command Prompt.
5. Ran:

```cmd
ipconfig /flushdns
