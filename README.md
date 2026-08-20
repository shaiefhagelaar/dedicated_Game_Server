# Dedicated_Game_Server

I usually take my time to set up a server so I know for certain everything is configured with regards to best practices. Since people are in a rush I skipped a few steps along the line which is something I will never do again. Also I should configure more servers and spin them up more often, I have a Dell Optiplex laying around which I could use as a dedicated game server connected to a switch. I'll make a repo in the near future (time of writing = 21/08/2026 00:16).

Securing server takes time, yes I could just write a script and automate it but doing thing manually and on the fly makes it more of a challenge and builds skills and knowlegde. If I'm skilled enough I will automate the process to reduce operation cost even more.

## Disclaimer

This is a documented project for educational purposes. Use at your own discretion.

## To do list
- {DONE} Choose a cloud provider = Hostinger
- {PENDING} Set up secure log in to the of the server
- {PENDING} Check all the server settings for potential leaks
- {DONE} Ensure back up capabilities for the server
- (DONE} Choose the game that will be hosted on the server (Project Zomboid)
- {PENDING} Add an Administrator
- {PENDING} Secure Administrator
- {PENDING} Pick the mods
- {PENDING} Check and test the mods
- {PENDING} Set up secure access to the server for players to join
- {PENDING} Make sure console can run only for the mods

### Dedicated game server hosted on Hostinger

We'll be using Hostinger to host a secured dedicated game server. Why Hostinger? It's easy  to set up the server and you can give easy access to the secured server.

    https://www.hostinger.com/vps/game-server-hosting

### Requirements of the server

Depending on how many people will play on the server and the type of mods you use will define how much vCPU's, RAM and Storage (NVMe SSD). Backups take quite a lot of space

vCPU's: 2
RAM: 8 GB
Storage: 100 GB
