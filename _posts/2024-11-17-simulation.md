---
title: "Simulation recording: sensitive data exposure"
date: 2024-11-18 10:00:00 +0000
categories: [simulation, recording]
tags: simulation, recording    # TAG names should always be lowercase
---

<div style="position:relative; width:100%; height:0px; padding-bottom:49.257%"><iframe allow="fullscreen;autoplay" allowfullscreen height="100%" src="https://streamable.com/e/jxh14t?autoplay=1" width="100%" style="border:none; width:100%; height:100%; position:absolute; left:0px; top:0px; overflow:hidden;"></iframe></div>

## Demonstrating Sensitive Data Exposure with OWASP Juice Shop

In this blog, I will demonstrate a simple example of sensitive data exposure using OWASP Juice Shop.

I set up the OWASP Juice Shop in my VirtualBox environment. The first step I took was to check the `robots.txt` file of the application. In the file, I noticed a disallowed directory: `/ftp`.

Curious, I navigated to the `/ftp` directory. There, I found a sensitive document that should not have been accessible.

This simple exercise highlights how improper configuration or oversight can lead to sensitive data exposure, posing a significant risk to systems and users.


