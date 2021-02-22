# ProxyTest

Velocity and Bungeecord preformance tests.

Both preformance tests where made possbile using [LambdaAttack](https://github.com/games647/LambdaAttack/pull/53) -s 1.16.5 pull request.

All bots where sent from **my** home adress to **my** server. TCPShield was used in both cases.

All bots where fowarded to a limbo server with most packets removed after joining. 

The limbo server: [Click Here](https://github.com/Nan1t/NanoLimbo).

# Velocity:

- Version: [Velocity 1.1.4](https://velocitypowered.com/downloads)
- Player count: [525](http://prntscr.com/103lwy9)
- Fowarding method: Modern
- Online mode: false
- JVM flags: ```java -Xms512M -Xmx512M -XX:+UseG1GC -XX:G1HeapRegionSize=4M -XX:+UnlockExperimentalVMOptions -XX:+ParallelRefProcEnabled -XX:+AlwaysPreTouch -XX:MaxInlineLevel=15 -jar velo.jar ```
- Velocity Config: https://paste.lucko.me/J5T0vJhliq
- Spark Sampler: https://spark.lucko.me/#e6hqYyJBfU

Video: https://youtu.be/TpxxtFcIcp8

# BungeeCord:

- Version: [git:BungeeCord-Bootstrap:1.16-R0.5-SNAPSHOT:4f23b49:1548](https://ci.md-5.net/job/BungeeCord/)
- Player count: [525](http://prntscr.com/103o4x2)
- Fowarding method: Legacy/Bungee
- Online mode: false
- JMV flags: ```java -Xmx512M -Xms512M -jar BungeeCord.jar```
- BungeeCord Config: https://paste.lucko.me/dmWa6G18Wf
- Spark Sampler: https://spark.lucko.me/#utizEtTF7q

Video: https://youtu.be/TYUxoeKtPuw

# Interesting tests:

nload with 525 players using 
- Velocity: http://prntscr.com/103oqci
- BungeeCord: http://prntscr.com/103o9hx

htop with 525 players using
- Velocity: http://prntscr.com/103ophn
- BungeeCord: http://prntscr.com/103ocye
