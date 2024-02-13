<p align="center">
  <br>
  <img width="200" src="./assets/logo.svg" alt="logo of awesome-tee repository">
  <br>
  <br>
</p>

## Awesome Teeworlds / DDraceNetwork

> A curated list of awesome things related to Teeworlds / DDraceNetworks

- [Сommunities](#communities)
  - [Teeworlds](#communities-teeworlds)
  - [DDraceNetwork](#communities-ddnet)
  - [King of Gores (KoG)](#communities-kog)
  - [Unique ](#communities-unique)
  - [Other](#communities-other)
- [Projects](#projects)
- [Libraries](#libraries)
  - [Rust](#libraries-rust)
  - [Ruby](#libraries-ruby)
  - [Python](#libraries-python)
  - [JavaScript / TypeScript](#libraries-js-ts)
      - [AngularJS](#libraries-angularjs)
  - [C#](#libraries-csharp)
- [Clients](#clients)
- [Mods](#mods)
  - [Client-server modifications](#mods-client-server)
  - [Server-side modifications](#mods-server)
- [Blog Posts](#blog-posts)
- [Documentation](#docs)
- [Archives](#archives)
- [Assets](#assets)
- [Tutorials](#tutorials)
- [Content Makers](#content-makers)
    - [Youtube Channels](#content-makers-yt)

<!-- md-parser-start -->

## Сommunities

### Teeworlds <a id="communities-teeworlds"></a>

- [Teeworlds](https://www.teeworlds.com/)
- [Teeworlds - Official Forum](https://www.teeworlds.com/forum/)
- [Teeworlds - GitHub](https://github.com/teeworlds)
- [Teeworlds - Steam](https://store.steampowered.com/app/380840/Teeworlds/)
- [Teeworlds - Discord](https://discord.gg/teeworlds)
- [Teeworlds - IRC](https://webchat.quakenet.org/?channels=teeworlds)

### DDraceNetwork <a id="communities-ddnet"></a>

- [DDraceNetwork](https://ddnet.org/)
- [DDraceNetwork - Official Forum](https://forum.ddnet.org/)
- [DDraceNetwork - GitHub](https://github.com/ddnet)
- [DDraceNetwork - Steam](https://store.steampowered.com/app/412220/DDraceNetwork/)
- [DDraceNetwork - Discord](https://ddnet.org/discord)
- [DDraceNetwork - Wiki](https://forum.ddnet.org/)

### King of Gores (KoG) <a id="communities-kog"></a>

- [King of Gores](https://kog.tw/)
- [King of Gores - Discord](https://discord.kog.tw/)

### Unique <a id="communities-unique"></a>

- [Unique](https://uniqueclan.net/)
- [Unique - GitHub](https://github.com/unique-clan)
- [Unique - Discord](https://discord.gg/gbgEs7m6kK)

### Other <a id="communities-other"></a>

- [tee.community](https://tee.community/)
- [tee.community - Discord](https://tee.community/discord)

## Projects

- [skins.tw](https://skins.tw/) / [teedata.net](https://teedata.net/) ([GitHub](https://github.com/Teeskins/), [Discord](https://discord.gg/mTVQuEDzzc))  - Teedata is a web-based database for Teeworlds. Browse through Teeworlds graphics, Tools and more.
- [db.ddstats.org](https://db.ddstats.org/) - Datasette instance of the official DDNet record database.
- [ddstats.org](https://ddstats.org/) ([GitHub](https://github.com/edg-l/ddstats)) - A DDraceNetwork / Teeworlds fancy information frontend.
- [DDStats](https://ddstats.org/) ([GitHub](https://github.com/ddstats-tw)) - A website showing various statistics related to DDNet.
- [DDNet-Team-Searcher](https://github.com/DDNet-Team-Searcher) - Website where weirdos can find another weirdos to play with each other.
- [skinprox](https://skins.scrumplex.net/) ([Source code](https://codeberg.org/Scrumplex/skinprox)) - Opinionated proxy for querying skins for DDraceNetwork.
- [teeobserver](https://observer.ddstats.org/) ([GitHub](https://github.com/edg-l/teeobserver)) - This tool continuously fetches the DDNet master server and observes the changes, broadcasting the events and providing a API.
- [trashmap.ddnet.org](https://trashmap.ddnet.org/) ([GitHub](https://github.com/ddnet/ddnet-trashmap)) - DDNet Trashmap is a service for mappers who can't host their own servers. You can create a testing server here and test your map alone or with other players.
- [Teerank.io](https://teerank.io/) ([GitHub](https://github.com/needs/teerank)) - Teerank is a simple and fast ranking system for Teeworlds.
- [Teeworlds Web Editor](https://tw.thissma.fr/) ([GitHub](https://github.com/k2d222/twwe)) - Teeworlds / DDraceNetwork map editor. Online and collaborative, just like the game.
- [ddnet url generator](https://ddnet.org/connect-to/?addr=127.0.0.1:8303/) ([GitHub](https://github.com/ddnet/ddnet-web/tree/247b045ca8045620bd2b70e81ded9c7a7bf45048/www/connect-to)) - Share server ips as https links
- [KoG-Stats](https://riemelt.github.io/KoG-Stats/) ([GitHub](https://github.com/Riemelt/KoG-Stats)) - KoG map record holders.

## Libraries

### Rust <a id="libraries-rust"></a>

- [libtw2](https://github.com/heinrich5991/libtw2) - Some Teeworlds stuff in Rust.
- [twmap](https://gitlab.com/Patiga/twmap) - A Rust library for parsing, editing and saving Teeworlds and DDNet maps.
- [twgpu](https://gitlab.com/Patiga/twgpu) - Renderer for Teeworlds and DDNet maps.
- [tw-mastersrv](https://github.com/teeworlds-utilities/tw-mastersrv) - Parsing Teeworlds master server.
- [teeconfig](https://github.com/edg-l/teeconfig) - A DDraceNetwork / Teeworlds configuration parser.
- [teestatus](https://github.com/edg-l/teestatus) - Library to retrieve information from teeworlds servers and related mods.
- [teeint](https://github.com/edg-l/teeint) - A teeworlds variable int packer/unpacker in Rust.
- [teerender](https://github.com/edg-l/teerender) - A blazingly fast tee skin renderer web service, with custom colors.
- [teemasterparser](https://github.com/edg-l/teemasterparser) - Command line tool to parse and analyze data from https://ddnet.tw/stats/master/
- [ddnet-map-gen](https://github.com/edg-l/ddnet-map-gen) - DDNet Map generator made in Rust using twmap.
- [ddnet-map-diff](https://github.com/edg-l/ddnet-map-diff) - A DDNet map diff tool made in Rust using twmap.

### Ruby <a id="libraries-ruby"></a>

- [huffman-tw](https://github.com/ChillerDragon/huffman-tw) - The Teeworlds C++ huffman compression code wrapped as a ruby gem.
- [teeworlds_network](https://github.com/ChillerDragon/teeworlds_network) - Teeworlds 0.7 Client and Server network library

### Python <a id="libraries-python"></a>

- [twmap-py](https://gitlab.com/Patiga/twmap-py) - Python bindings for the crate twmap.
- [twmap-blender](https://gitlab.com/Patiga/twmap-blender) - Blender add-on that allows you to import Teeworlds / DDNet maps.
- [twnet_parser](https://gitlab.com/teeworlds-network/twnet_parser) - A teeworlds network protocol library, designed according to sans I/O (http://sans-io.readthedocs.io/) principles


### JavaScript / TypeScript <a id="libraries-js-ts"></a>

- [teeworlds-utilities](https://github.com/teeworlds-utilities/teeworlds-utilities) - Teeworlds asset utilities used at teedata.net.
- [teeworlds-server-status](https://github.com/edg-l/teeworlds-server-status) - Get information about DDraceNetwork / Teeworlds servers.
- [tw-chatonly](https://gitlab.com/swarfey/teeworlds-client/) - Library to connect a bot to a Teeworlds server.
- [TeeAssembler-2.0](https://github.com/AlexIsTheGuy/TeeAssembler-2.0) ([Demo](https://teeassembler.developer.li/)) - TeeAssembler 2.0 is a script used for coloring a Teeworlds skin image the same way Teeworlds does and rendering the image in your browser using HTML, CSS and JavaScript.

##### AngularJS <a id="libraries-angularjs"></a>

- [NgTeeAssembler](https://github.com/k-i-o/NgTeeAssembler) (TeeAssembler 3.0) - fork of [TeeAssembler 2.0](https://github.com/AlexIsTheGuy/TeeAssembler-2.0) reimplemented as AngularJS package.

### C\# <a id="libraries-csharp"></a>

- [Teeditor](https://github.com/michailowski/Teeditor) - Map editor for a retro multiplayer shooter TeeWorlds.
- [TeeSharp](https://github.com/Matodor/TeeSharp) - Teeworlds / DDraceNetwork modding platform in .NET.

## Clients

- [TaterClient](https://github.com/sjrc6/TaterClient-ddnet) - Modification of DDNet teeworlds client.
- [chillerbot-ux](https://github.com/chillerbot/chillerbot-ux) - DDNet based client with password manager, block warlist and chat automation.

## Mods

### Client-server modifications <a id="mods-client-server"></a>

- [MineTee](https://gitlab.com/Tardo/MineTee) - Server / Client Mod for Teeworlds v0.6.x.
- Nodes - Build a base with your team to withstand enemy attacks and prepare yourself well for counterattack. For this purpose you can build weapon dispensers, automatic guns, teleporters, defense shields and more.
  + 0.7 remake [website](https://nodes.teeworlds.dev/) and [code](https://github.com/teeworldsnetwork/nodes)
  + 2010 [original forum post](https://www.teeworlds.com/forum/viewtopic.php?id=5409)

### Server-side modifications <a id="mods-server"></a>

- [opengores](https://github.com/teemods/opengores) ([maps](https://github.com/teemods/opengores-maps)) - A open-source version of Gores mod, forked from ddnet.

## Blog Posts

- [UI Code in DDraceNetwork](https://edgarluque.com/blog/ui-code-ddnet/)
- [Parsing compressed files efficiently with Rust (DDNet master server files)](https://edgarluque.com/blog/zstd-streaming-in-rust/)
- [An intro to the DDraceNetwork game source code](https://edgarluque.com/blog/intro-to-ddnet/)
- [Code conventions in DDraceNetwork](https://edgarluque.com/blog/code-conventions-in-ddnet/)
- [Implementing a chat command in DDraceNetwork](https://edgarluque.com/blog/chat-command-ddracenetwork/)

## Documentation

- [The Teeworlds / DDNet network protocol](https://chillerdragon.github.io/teeworlds-protocol/)
- [DDNet Skeleton](https://github.com/teemods/ddnet-skeleton-readme?tab=readme-ov-file#ddnet-skeleton) - README containing information about Skeleton changes & How DDNet code and flags works.

## Archives

- [[MAPS] Map collection](https://heinrich5991.de/teeworlds/maps/) - by heinrich5991.
- [[MAPS] Map collection (mirror)](https://tee.world/teeworlds/) - by noby.
- [[OTHER] DDNet daily master server stats backups](https://ddnet.org/stats/master/)
- [OTHER] Raw list of all DDNet ranks, team ranks and maps
  - [CSV](https://ddnet.org/stats/ddnet-stats.zip)
  - [SQL](https://ddnet.org/stats/ddnet-sql.zip)
  - [SQLite](https://ddnet.org/stats/ddnet.sqlite.zip)
- [OTHER] Raw data of players since 2014-12-21
  - [By country (CSV)](https://ddnet.org/status/csv/bycountry)
  - [By mod (CSV)](https://ddnet.org/status/csv/bymod)
- [CHAT] Teeworlds chat logs
  - [Discord](https://archive.strct.cc/teeworlds/)
  - [IRC](https://ddnet.org/irclogs/teeworlds/)
- [CHAT] DDNet chat logs
  - [Discord ](https://archive.strct.cc/ddnet/) ([events](https://archive.strct.cc/ddnet-events/), [info](https://archive.strct.cc/ddnet-info/), [testlogs](https://ddnet.org/testlogs/))
  - [IRC](https://ddnet.org/irclogs/)
- [[CHAT] KoG Discord server chat logs](https://archive.strct.cc/kog/)
- [[CHAT] Teeworlds Data Discord server chat logs](https://archive.strct.cc/teeworlds-data/) ([events](https://archive.strct.cc/teeworlds-data-events/), [info](https://archive.strct.cc/teeworlds-data-info/))

## Assets

- [TeeworldsDB/mapres](https://github.com/TeeworldsDB/mapres) - A sorted collection of teeworlds mapres.
- [TeeworldsDB/skins](https://github.com/TeeworldsDB/skins) - A collection of 0.6 and 0.7 teeworlds skins that aims to be complete. Quantity over quality.
- [TeeworldsDB/images](https://github.com/TeeworldsDB/images) - A collection of free to use and edit images for other art work. No actual game skins.
- [ddnet-data-svg](https://github.com/ddnet/ddnet-data-svg) - ddnet community effort to recreate teeworlds assets as SVG's.

## Tutorials

- [Beginner Gores Tutorial](https://www.youtube.com/watch?v=5fU25R5xLmE)
- [A Guide to Teeworlds: Teeworlds in All of its Difficultees (copyright free)](https://www.youtube.com/watch?v=ErmocbgAgE8) - Teeworlds gameplay intro by ResamVi on YouTube

## Content Makers

### Youtube Channels <a id="content-makers-yt"></a>

- [David Villa - Teeworlds](https://www.youtube.com/@David-Villa-Teeworlds)
- [Beautemps](https://www.youtube.com/@BeautempsTW)
- [TeeworldsEasy](https://www.youtube.com/@TeeworldsEasy)
- [JuKKi](https://www.youtube.com/@jukkitw)
- [Teero](https://www.youtube.com/@Teero777)
- [M1H40S](https://www.youtube.com/@M1H40S)
- [Brokecdx-](https://www.youtube.com/@Brokecdx)
- [Gazebr](https://www.youtube.com/@Gazebr)
- [Aoe](https://www.youtube.com/@AoeTeeworlds)

<!-- md-parser-end -->
<br/>
<br/>
<br/>

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
