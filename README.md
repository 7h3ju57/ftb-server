Feed The Beast

Based off of: jaysonsantos/minecraft-ftb-skyfactory3

Available Enviroment variables:
OPS = Elevate specified user to ops privileges on first start. (username)
MODPACK = Which modpack server to download.(the name must match what is listed at https://www.feed-the-beast.com/modpacks, ie: FTB Presents SkyFactory 3)
LEVEL = World name of your choosing.
UPDATE = Whether or not the server should look for an update on start. (yes|no)
MOTD = This message shows up in the MC server listings.
JVM_OPTS = default is "-Xms2048m -Xmx2048m".

/data is your volume

Quick start
docker run --name FTB -p 25565:25565 -e "MODPACK=FTB Presents Direwolf20 1.12" 7h3ju57/ftb-server
