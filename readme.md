\# Minecraft Server on Debian with systemd and screen



This repo shows how to run a vanilla Minecraft server on a Debian server using:



\- `/opt/minecraft` as the server directory

\- `screen` so you can attach to the console

\- `systemd` so the server auto starts on boot and stops cleanly



This is done assuming you already have a Minecraft server jar (from Mojang) and a basic Debian system (for example on Google Cloud).



---



\## Requirements



\- Debian or Ubuntu based server

\- A user account that will own and run the server (example: `minecraft`)

\- Java (OpenJDK 17 or 21 recommended)

\- `screen`



---



\## Directory layout



The server lives in:



```text

/opt/minecraft/

&nbsp; minecraft\_server.jar

&nbsp; eula.txt

&nbsp; server.properties

&nbsp; world/

&nbsp; logs/

&nbsp; libraries/

&nbsp; versions/



