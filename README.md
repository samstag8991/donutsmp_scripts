# donutsmp_scripts
Minescript scripts for DonutSMP: \marketmaker and \anchorfinder.

READ EVERYTHING VERY IMPORTANT! 
High chances of getting banned with \marketmaker speed set on: FAST, but on MEDIUM maybe lower chances.
Really low likelihood of getting banned for using \anchorfinder
 
# PREREQUISITES
Minecraft Java 26.3 with:
- A launcher that supports mods (Prism Launcher is ideal)
- Fabric Loader
- Fabric API
- Minescript mod, version 5 (pick the latest)

Put the scripts in the minescript folder of your instance (minecraft/minescript).

# STARTING AND STOPPING
Start a script by typing \marketmaker or \anchorfinder in chat.
Stop it by typing the same command again.
If it ever hangs, type \jobs to list the running scripts, then \killjob <number> (usually \killjob 1).

# EARLY GAME - \anchorfinder (about 1-2M/h)
Low ban risk, but use it at your own risk.
A client-side finder for respawn anchor clusters in the Overworld. It marks spots where several anchors sit close together with glowing boxes you can see through walls, and labels bigger groups as hotspots. It runs only on your own client, so the server isn't involved.
Meta gear: ender pearls, and always a totem, feather falling, blast protection and aqua affinity.

# MID-GAME - \marketmaker (about 3-5M/h)
You can get banned with this one. Use it at your own risk.
It buys items cheaply through /orders and sells them for more on the auction house. It only buys when the profit is worth it, re-bids if you get outbid, and never undercuts other sellers or sells below cost. It works in rounds, shows a live HUD, and is controlled from an in-game menu.
Good items to add: golden apples (64x or 128x) and end crystals (64x or 128x). Run Scan spreads first, because prices change quickly.

# \yes \no \auto
When a MARKETMAKER round finishes, the script waits 15 seconds for your answer in chat:
- \yes starts the next round now, and asks again after every round.
- \no stops the script, so no new round starts.
- \auto starts the next round now and stops asking, so every following round continues on its own.
If you type nothing, it continues by itself after 15 seconds.
Keep yes.pyj, no.pyj and auto.pyj in the same folder, or these commands won't exist.
