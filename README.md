# VM-Laboratory-3-Web

# Laboratory 3

> A simple web app made in Linux...

---

## Frameworks used

- Flask

---

## Any issues encountered and solutions

- **Networking** – Could not connect the host to the web. Switched network adapter from NAT to Bridged Adapter.  
- **Commands** – Certain commands cannot be defined like flask (Command 'flask' cannot be found). Worked around the issue by updating and installing flask (sudo apt install python3-flask) 
- **Coding** - Trying to add a simple CSS with less experience. I studied for a while to get it run as how i envisioned it in my mind. 
---

## How to Run the Web App

> Run theses codes in the terminal (Ubuntu)

1. cd ~/my_flask_app
2. python3 app.py

> From here there should be an address running on http://192.168.18.9:5000. Run this address on the host's browser.


## What challenges did you face during the deployment process?:
While following the procedures, I had issues following in between steps. There are steps where you are to create templates under nano commands before I could actually do the coding. I also had networking issues, when I tried connecting via NAT I could not open the web from the host, then I tried switching to a Bridged Adapter and it worked.    

## What did you learn about configuring Linux servers for hosting web apps?:
Linux is a bit complex because I have to do most things via commands, especially when certain commands don't work but when you get the hang of it gets easier. Unlike my experience with other methods, I think this is easier, but since the design and the functions are basic I could not say for sure. Connection was quick with a few struggles to get it to work.

## Which framework did you find easiest to use and why?:
Flask was very straightforward and basic, aything else goes down to the coding experience. Styling with .css is easy when you have experience in JAVA and also .jsp to create the very HTML. Most of these I understood because of my experience with JAVA. So i sticked with it for the whole web application.

## How does deploying in a VM simulate real-world cloud hosting?
When I delploy in a VM It closely simulates real world cloud hosting because I can share IP through linux to have the host computer join just like how cloud hosting would. Changes can also be only applied via edits or changes within the terminal from linux just like cloud hosting would when updates are made.   

---
