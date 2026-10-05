# VPN Troubleshooting – Service Desk Lab

## Scenario
A remote user lost their VPN connection and could no longer access internal company resources.

## Environment
Simulated service desk environment.

## Problem
VPN disconnected and would not reconnect.

## Business Impact
The user was working remotely and could not access internal resources.

## Troubleshooting Steps
1. Confirmed the issue was related to the VPN connection.
2. Opened Command Prompt.
3. Ran: cmd
ipconfig /flushdns
