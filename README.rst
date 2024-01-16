# What Happens When...

This repository is an attempt to answer the age-old interview question "What happens when you type google.com into your browser's address box and press enter?" Except instead of the usual story, we're going to try to answer this question in as much detail as possible. No skipping out on anything.

This is a collaborative process, so dig in and try to help out! There are tons of details missing, just waiting for you to add them! So send us a pull request, please!

This is all licensed under the terms of the Creative Commons Zero license.

Read this in 简体中文 (simplified Chinese), 日本語 (Japanese), 한국어 (Korean) and Spanish. NOTE: these have not been reviewed by the alex/what-happens-when maintainers.

## Table of Contents
- [DNS Enhancements](#dns-enhancements)
- [Browser Caching](#browser-caching)
- [TCP/IP Enhancements and Variations](#tcpip-enhancements-and-variations)
- [Load Balancing and CDNs](#load-balancing-and-cdns)
- [SSL/TLS Handshake Process](#ssltls-handshake-process)
- [Websocket Communication](#websocket-communication)
- [HTTP/2 and HTTP/3](#http2-and-http3)
- [Browser Rendering Engine](#browser-rendering-engine)
- [Web Application Firewalls (WAFs)](#web-application-firewalls-wafs)
- [API Requests](#api-requests)
- [Mobile vs Desktop Browsing](#mobile-vs-desktop-browsing)
- [Cross-Origin Resource Sharing (CORS)](#cross-origin-resource-sharing-cors)
- [Browser Extensions](#browser-extensions)
- [Privacy and Tracking](#privacy-and-tracking)
- [Web Accessibility](#web-accessibility)
- [Progressive Web Apps (PWAs)](#progressive-web-apps-pwas)
- [Server-Side vs Client-Side Rendering](#server-side-vs-client-side-rendering)
- [Browser Security Features](#browser-security-features)
- [Network Protocols Beyond HTTP](#network-protocols-beyond-http)
- [Evolution of Web Standards](#evolution-of-web-standards)

### DNS Enhancements
#### DNS over HTTPS (DoH)
DNS over HTTPS (DoH) is a protocol for performing remote Domain Name System (DNS) resolution via the HTTPS protocol. It enhances privacy and security by preventing eavesdropping and manipulation of DNS data.

#### DNSSEC
DNSSEC (Domain Name System Security Extensions) adds a layer of security to the DNS lookup and response process by enabling DNS responses to be validated. It's designed to protect against redirection to fraudulent websites.

#### Role of DNS Servers
The hierarchical structure of DNS includes root, top-level domain (TLD), and authoritative servers. These servers have specific functions in the DNS resolution process like managing TLD zones, responding to lookup requests, etc.

### Browser Caching
#### ETag Headers and Cache-Control Directives
ETag headers and cache-control directives help browsers determine whether to fetch content from the network or use the cached version.

#### Browser Cache Validation Process
The browser cache validation process includes freshness validation and conditional requests. This allows the browser to validate if a cached resource is still up to date.

### TCP/IP Enhancements and Variations
#### QUIC Protocol
The QUIC protocol is a multiplexed and secure transport layer protocol designed to reduce connection and transport latency and improve congestion control.

#### TCP Fast Open
TCP Fast Open is a mechanism that reduces latency by enabling data exchange during the initial TCP handshake for a TCP connection.

### Load Balancing and CDNs
#### Role of Load Balancers
Load balancers distribute network or application traffic across multiple servers. This increases capacity and reliability of applications.

#### Content Delivery Networks (CDNs)
CDNs provide high availability and performance by distributing services spatially relative to end-users.

### SSL/TLS Handshake Process
The SSL/TLS handshake process establishes a secure communication channel by enabling key exchange, certificate validation, and session cipher negotiation between client and server.

### Websocket Communication
WebSockets provide full-duplex communication channels over a single TCP connection, enabling real-time data transfer between clients and servers.

### HTTP/2 and HTTP/3
#### HTTP/2
HTTP/2 introduced major enhancements over HTTP/1.1 like header compression, multiplexing, and server push for better performance.

#### HTTP/3
HTTP/3 focuses on new features like use of QUIC for transport to improve security and performance over HTTP/2.

### Browser Rendering Engine
The browser rendering engine parses HTML, CSS, and JavaScript to construct the DOM and CSSOM trees before generating the layout and rendering the page.

### Web Application Firewalls (WAFs)
WAFs protect web applications by monitoring, filtering, and blocking HTTP traffic to defend against attacks.

### API Requests
RESTful APIs and GraphQL play a big role in modern web applications. Browsers handle the requests to these APIs similar to traditional HTTP requests.

### Mobile vs Desktop Browsing
Mobile and desktop browsing differs in aspects like responsive design, touch events, network latency, and resource constraints.

### Cross-Origin Resource Sharing (CORS)
CORS allows resources to be requested from another domain. It is crucial for web security and resource access management between domains.

### Browser Extensions
Browser extensions can modify or enhance website loading process through features like ad-blocking, security, and customization.

### Privacy and Tracking
Cookies, tracking pixels, and other technologies are used to track users and enable personalization. Browsers manage these to protect user privacy.

### Web Accessibility
Web accessibility involves making content accessible by adhering to guidelines like WCAG and adding ARIA labels.

### Progressive Web Apps (PWAs)
PWAs provide an app-like experience on websites with added benefits over traditional web apps. Browsers support features to enable this.

### Server-Side vs Client-Side Rendering
Server-side rendering (SSR) and client-side rendering (CSR) impact performance, SEO, and user experience differently. Browsers handle the rendering accordingly.

### Browser Security Features
Built-in browser security features include sandboxing, mixed content blocking, phishing and malware protection.

### Network Protocols Beyond HTTP
Other network protocols involved in web communication include WebSocket, FTP, and SMTP.

### Evolution of Web Standards
Web standards have evolved over time under organizations like the W3C, impacting web browsing and development.
