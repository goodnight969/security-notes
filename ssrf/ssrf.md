# What I understand about SSRF

SSRF is a web vulnerability that allows an attacker to induce a server-side application to make requests to other systems and access sensitive data.

# Successful SSRF attack

A successful SSRF attack can result in unauthorized actions or access to internal data.

# SSRF attack in practice

An attacker induces the web application to make a request to the server that hosts the application itself.  
This is usually done via the loopback network interface.

The loopback network interface uses the IP address 127.0.0.1 or the hostname localhost.

