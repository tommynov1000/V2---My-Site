---
date: '2021-07-15'
title: 'Airplane ticket deal finder'
cover: 'demo.png'
github: 'https://github.com/tommynov1000/Flight-Deal-Finder'
external: 'https://github.com/tommynov1000/Flight-Deal-Finder'
tech:
  - Python
  - RESTful API (Tequila)
  - Windows server 2016
  - Proxmox
showInProjects: true
---

Simple flight deal finder made with Python. Utilizing the Tequila API, it checks for cheap flights in the next 6 months from a provided list of cities, and if the price fails below a certain minimum, it will send an alert via email. This script is scheduled to run every day at 9 AM EST on a windows server 2016 VM, virtualized on Proxmox.
