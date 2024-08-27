# Fail2Ban FortiGate Threat Feed Integration

## Overview
This project provides a server-local extension for Fail2Ban that automates the updating of FortiGate Threat Feeds with IP addresses scraped from Fail2Ban jail logs. Designed to operate via cron or systemd, this extension ensures continuous monitoring and proactive protection at the network's edge.

## Background
The concept for this project was originally validated through a Python prototype, which was rigorously tested over several months on a home network. However, recognizing the limitations of Python for this domain, that codebase will remain private and unpublished. Instead, this project is being reimagined and redeveloped in C++ to provide a more robust, efficient, and maintainable solution.

## Current Features
- **Automatic Updates**: Utilizes cron or systemd for seamless and continuous updates.
- **Network Edge Protection**: Integrates directly with FortiGate to bolster security at the network perimeter.

## Future Enhancements
- **Real-Time Threat Response**: Planned enhancements may include the ability to respond to emerging threats in real-time, potentially unlocking new levels of network security.
- **C++ Codebase**: This pre-release marks the initial stage of the C++ codebase, with ongoing development aimed at adding new features and improving reliability.

## Status
This pre-release represents the initial C++ codebase, with further features and improvements expected in the coming days.

**Coming Soon.**
