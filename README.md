# Task-8----Elevate-Labs
VPN Analysis and Privacy Testing Report

A comprehensive analysis of VPN functionality, privacy protection, and performance characteristics using ProtonVPN.

## Overview

This project demonstrates how VPN services work by testing IP address masking, DNS leak prevention, and network performance impacts. The analysis includes before/after comparisons of network configurations and detailed privacy testing results.

## What's Included

- **Complete VPN setup process** - From service selection to client installation
- **IP address masking verification** - Shows geographic location spoofing (India → Netherlands)
- **DNS leak testing** - Confirms DNS queries are properly routed through VPN servers
- **Performance analysis** - Documents speed impacts and limitations
- **Security assessment** - Evaluates encryption protocols and privacy protection

## Key Findings

 **IP Address Successfully Masked**: `49.37.132.94` (India) → `185.177.126.71` (Netherlands)

 **No DNS Leaks Detected**: All DNS queries routed through ProtonVPN servers

**WireGuard Protocol**: Modern encryption with good performance characteristics

 **Speed Impact**: ~20-50% reduction in connection speeds

 **Service Compatibility**: Some streaming/banking sites block VPN traffic

## Tech Stack

- **VPN Service**: ProtonVPN (Free tier)
- **Protocol**: WireGuard
- **Testing Tools**: whatismyipaddress.com, DNS leak test services
- **Platform**: Windows client

