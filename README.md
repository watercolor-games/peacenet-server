# Peacenet Server

This is the multiplayer server software for [The Peacenet](https://github.com/watercolor-games/the-peacenet). This software allows players to connect, authenticate through itch.io, and fight for resources, fame and reputation within the world of The Peacenet using the Peacegate Operating System.

This program uses minimal features of the [Peace Engine](https://github.com/watercolor-games/peace-engine) such as the Dependency Injection framework to allow modular implementation of new features as well as support for server-side mods adding user-created features to the Multiplayer experience.

### Planned Features

These features are all planned for the server software.

 - **Ability to set a maximum player count** to dictate how many people can play on the server at once.
 - **Ability to whitelist players** using their itch.io usernames, only allowing whitelisted players to connect.
 - **Ability to ban** both IP addresses and itch.io users for breaking the rules of your server.
 - **In-game text chat** with an optional "staff" chat for admins and moderators of the server to chat in.
 - **Optional cheat prevention** that can be enabled for servers who want everyone to play fairly.
 - **ACL (Access Control List)** that allows you to grant certain players certain permissions, place players in different groups that have group-wide permissions, etc - much like the PermissionsEx Spigot plugin for Minecraft.
 - **Full LiteDB database** that allows Terminal Commands, mods, and other server-side tools to store any data they want in a safe environment with an easy-to-use API.
 - **Extremely fast and secure TCP protocol**, the likes of which were never before seen in either ShiftOS OR The Peacenet.
 - **SSL support** so nobody can steal your bits & bytes.
 - **Capped server-side user filesystems** that allow admins to set how much drive space each player can have.
 - **Server-side lootables, installables, upgrades, Terminal Commands, hackables, Country Challenges, etc** because it can't be a game without things to do.
 - **Leaderboards** that track reputation, playtime, experience, and other stats about each player because Peacenet multiplayer ain't about peace. It's about competition.
 - **Players can start their own factions** that can be named, described, personalized, and have a reputation value and leaderboard entry (as well as an in-faction leaderboard.)
 - **Procedurally generated NPCs** so that there is always, ALWAYS, another thing to hack and explore.
 - Way, way more.
