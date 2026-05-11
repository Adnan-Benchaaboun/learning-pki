# Learning PKI

## Objective
Understand how a client can trust who they're exchanging 
messages with over the internet.

## Series Roadmap
- **Week 1:** What is encryption? How does encryption keep 
data safe on the internet?
- **Week 2:** What do websites use to keep data safe? How 
does the TLS handshake keep messages safe between the client 
and server? How does it guarantee future session safety if a 
previous session is compromised?
- **Week 3:** How does a client ensure that the server is who 
they say they are? How does a server get a certificate signed 
to verify its authenticity? What are certificate authorities' 
role in keeping the TLS handshake safe for both parties?
- **Week 4:** What problem does certificate transparency solve 
and why wasn't the CA system enough on its own?

## Project
A hands-on implementation of PKI in an isolated network 
environment. Including a working CA, signed certificates, 
TLS handshake, and certificate transparency logging. 
Coming after the presentation series.

## Structure
- `weekly-presentations/` - notes and slides for each week
- `project/` - hands-on PKI implementation (coming soon)