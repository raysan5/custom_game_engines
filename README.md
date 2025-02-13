# CUSTOM GAME ENGINES

A comprehensive list of custom game engines. This list is based on a 2020 article: [custom_game_engines_small_study](https://gist.github.com/raysan5/909dc6cf33ed40223eb0dfe625c0de74)

The list has been moved to a custom repo to allow contributors to improve it! **Additions and improvements are really welcome!!!**

## Introduction

Nowadays lots of companies choose engines like [Unreal](https://www.unrealengine.com/en-US) or [Unity](https://unity.com) for their games (or that's what lot of people think) because developing a custom AAA-level engine requires lots of resources, still, there are many big/small companies or even individuals that choose to create their custom engines for their games. In this page there are some of those engines listed.

Some points to consider:

 - The line between what can be considered an engine or a framework or just a library could be blurry. Note that not all engines have a set of tooling for easy interaction!
 - Most of the engines listed here have been developed along the years with multiple iterations and multiple videogames, those engines have gone through several versions or even complete (or semi-complete) rewrites from scratch, with a consequent engine name change. Also, important to note, most of those engines use numerous middleware for specific functionalities (Platform, Physics, Network, Vegetation, UI, Rendering, Audio...).
 - About the employees count, take it with a grain of salt, it was updated with aproximate numbers from 2020 (checked on the companies websites, Wikipedia or LinkedIn).


## AAA Engines: The BIG Companies

Below list is for **very big corporations**, sometimes with complex corporate structures with several divisions (not only focused on videogames) and various studios/subsidiaries developing games. Some of those companies work with multiple engines, not only custom ones but also licensed ones.

| Company  | Employees | Studios |  Engine(s) |   Notable Games   |
| --- | :---: | :---: | :---: | --- |
| [Activision/Blizzard](https://en.wikipedia.org/wiki/Activision_Blizzard)  | ~9200   | ~9 | *custom engine(s)*  | Warcraft series, Diablo series, Starcraft series, Call of Duty series, Overwatch  |
| [Electronic Arts](https://en.wikipedia.org/wiki/Electronic_Arts) | ~9300  | ~36 | [Frostbite](https://en.wikipedia.org/wiki/Frostbite_(game_engine))  | Star Wars Battlefront II, Anthem, Battlefield 1/V, FIFA 20, Need for Speed series |
| [Ubisoft](https://en.wikipedia.org/wiki/Ubisoft)          | ~16000    | ~54 | [AnvilNext 2.0](https://en.wikipedia.org/wiki/AnvilNext)              | Assassin's Creed series  |
|                  | | | [Disrupt engine](https://watchdogs.fandom.com/wiki/Disrupt_(engine))  | Watch Dogs series |
|                  | | | [UbiArt Framework](https://en.wikipedia.org/wiki/UbiArt_Framework)    | Rayman Legends, Child of Light, Valiant Hearts |
|                  | | | [Snowdrop](https://en.wikipedia.org/wiki/Snowdrop_(game_engine))      | Tom Clancy's The Division 2, The Settlers |
|                  | | | Dunia (CryEngine-based)                                               | FarCry series | 
|                  | | | Silex ([Anvil-based](https://en.wikipedia.org/wiki/Tom_Clancy%27s_Ghost_Recon_Wildlands#Development)) | Ghost Recon Wildlands |
|                  | | | LEAD engine   | Tom Clancy's Splinter Cell series |
|                  | | | *Dunia-based* | The Crew |
| [Capcom](https://en.wikipedia.org/wiki/Capcom)            | +2800     | ~15 | [MT Framework](https://en.wikipedia.org/wiki/MT_Framework)            | Monster Hunter: World                             |                                                  
|                  | | | [RE Engine](https://residentevil.fandom.com/wiki/RE_Engine)           | Resident Evil 7, Devil May Cry 5, RE2:Remake, RE3:Remake  |
| [Konami](https://en.wikipedia.org/wiki/Konami)            | +10000    | ~30 | [Fox Engine](https://en.wikipedia.org/wiki/Fox_Engine)                | Pro Evolution Soccer series, Metal Gear Solid V |
| [Square Enix](https://en.wikipedia.org/wiki/Square_Enix)  | +4600     | ~18 | [Luminous Studio](https://en.wikipedia.org/wiki/Luminous_Studio)      | Final Fantasy XV     | 
| [Nintendo](https://en.wikipedia.org/wiki/Nintendo)        | +6100     | ~8  | *custom engine(s)*      | Zelda: BOTW, Mario Odyssey                   |
| [Riot Games](https://en.wikipedia.org/wiki/Riot_Games)    | ~2500     | ~3  | [Hero Engine](https://en.wikipedia.org/wiki/HeroEngine) (2010+), *custom engine (2009)*         | League of Legends |
| [Rockstar](https://en.wikipedia.org/wiki/Rockstar_Games)  | +2000     | ~9  | [RAGE engine](https://en.wikipedia.org/wiki/Rockstar_Advanced_Game_Engine) | GTA V, Red Dead Redemption 2 |
| [CD Projekt](https://en.wikipedia.org/wiki/CD_Projekt)    | +1100     | ~4  | [REDEngine 3](https://witcher.fandom.com/wiki/REDengine)          | The Witcher 3 |
| [Epic](https://en.wikipedia.org/wiki/Epic_Games)          | +1000     | ~11 | [Unreal Engine 4](https://en.wikipedia.org/wiki/Unreal_Engine)        | Fortnite |

## AA Engines: Middle-size Studios

Here we have the medium-small companies that decided to create their custom technology for their titles.

| Company  | Employees | Engine   |   Notable Games   |
| --- | :---: | :---: | --- |
| [Creative Assembly](https://en.wikipedia.org/wiki/Creative_Assembly)      | +650  | [Warscape Engine](https://gpuopen.com/anatomy-total-war-engine-part) | Total War series                  |
| [Bungie](https://en.wikipedia.org/wiki/Bungie)                            | ~600  | [Tiger Engine](https://www.gdcvault.com/play/1022106/Lessons-from-the-Core-Engine) | Destiny series       |
| [Infinity Ward](https://en.wikipedia.org/wiki/Infinity_Ward)              | +500  | [IW 7.0](https://en.wikipedia.org/wiki/IW_engine)                     | Call of Duty: Infinite Warfare    |
| [Eidos-Montréal](https://en.wikipedia.org/wiki/Eidos-Montr%C3%A9al)       | ~500  | [Dawn Engine](https://fr.wikipedia.org/wiki/Dawn_Engine) (Glacier2-based) | Deus Ex: Mankind Divided      |
| [Bethesda](https://en.wikipedia.org/wiki/Bethesda_Game_Studios)           | ~400  | [Creation Engine](https://en.wikipedia.org/wiki/Creation_Engine)      | Skyrim, Fallout 4, Fallout 76                     |    
| [Valve Corp.](https://en.wikipedia.org/wiki/Valve_Corporation)            | ~360  | [Source 2](https://en.wikipedia.org/wiki/Source_2)                    | Dota 2, Half-Life: Alyx                           |
| [Crystal Dynamics](https://en.wikipedia.org/wiki/Crystal_Dynamics)        | ~350  | [Foundation Engine](https://en.everybodywiki.com/Foundation_Engine)   | Rise/Shadow of the Tomb Raider                    |
| [Avalanche Studios](https://en.wikipedia.org/wiki/Avalanche_Studios_Group) | ~320 | Apex engine | Just Cause series, Renegade Ops, Mad Max, RAGE 2        | 
| [Naughty Dog](https://en.wikipedia.org/wiki/Naughty_Dog)                  | +300  | Naughty Dog Game Engine   | Uncharted series, Last of Us              |
| [Rebellion Developments](https://en.wikipedia.org/wiki/Rebellion_Developments) | ~300  | Asura engine         | Alien vs. Predator series, Sniper Elite series |
| [Techland](https://en.wikipedia.org/wiki/Techland)                        | ~300  | [Chrome Engine 6](https://en.wikipedia.org/wiki/Chrome_Engine)        | Dying Light | 
| [Crytek](https://en.wikipedia.org/wiki/Crytek)                            | ~290  | [CryEngine V](https://en.wikipedia.org/wiki/CryEngine)                | The Climb, Hunt:Showdown                          |
| [From Software](https://en.wikipedia.org/wiki/FromSoftware)               | +280  | Dark Souls engine         | Bloodborne, Dark Souls III, Sekiro
| [Remedy](https://en.wikipedia.org/wiki/Remedy_Entertainment)              | +250  | [Northlight Engine](https://www.remedygames.com/northlight)          | Quantum Break, Control                            |       
| [Guerrilla Games](https://en.wikipedia.org/wiki/Guerrilla_Games)          | +250  | [Decima](https://en.wikipedia.org/wiki/Decima_(game_engine))          | Killzone Shadow Fall, Until Dawn, Horizon Zero Dawn |
| [Larian Studios](https://en.wikipedia.org/wiki/Larian_Studios)            | +250  | Divinity Engine           | Divinity series |
| [Platinum Games](https://en.wikipedia.org/wiki/PlatinumGames)             | ~250  | Platinum Engine           | NieR Automata, Bayonetta, Vanquish        |
| [Santa Monica Studio](https://en.wikipedia.org/wiki/SIE_Santa_Monica_Studio)  | +200 | *custom engine*        | God Of War series    |
| [id Software](https://en.wikipedia.org/wiki/Id_Software)                  | +200  | [idTech 6/7](https://en.wikipedia.org/wiki/Id_Tech)                   | Doom, Doom Eternal, Wolfenstein series            |
| [Sucker Punch](https://en.wikipedia.org/wiki/Sucker_Punch_Productions)    | +200  | [*custom engine*](https://www.suckerpunch.com/iss-engine-gdc2014)     | Infamous Second Son, Ghost of Tsushima?           |
| [Insomniac Games](https://en.wikipedia.org/wiki/Insomniac_Games)          | ~180  | [Insomniac Engine](https://blog.us.playstation.com/2018/09/06/insomniac-interview-the-tech-behind-marvels-spider-man)     | Rachet&Clank series, Marvel's Spider-Man |     
| [Quantic Dreams](https://en.wikipedia.org/wiki/Quantic_Dream)             | ~180  | [*custom engine*](https://www.gamepur.com/news/dev-detroit-become-human-on-ps4-to-be-powered-by-a-new-graphics-engine)    | Detroit: Become Human |
| [IO Interactive](https://en.wikipedia.org/wiki/IO_Interactive)            | ~170  | [Glacier2](https://fr.wikipedia.org/wiki/Glacier_Engine) | Hitman series |
| [Asobo Studio](https://en.wikipedia.org/wiki/Asobo_Studio)                | +140  | [Zouna](https://news.ycombinator.com/item?id=22966499)                | A Plague Tale         |
| [Ready At Dawn](https://en.wikipedia.org/wiki/Ready_at_Dawn)              | ~120  | *custom engine*    | The Order: 1886, Lone Echo                       |
| [Mercury Steam](https://en.wikipedia.org/wiki/MercurySteam)               | ~110  | *custom engine*    | Spacelords, Castlevania:Lords of Shadow series   |
| [Monolith Productions](https://en.wikipedia.org/wiki/Monolith_Productions) | +100 | [LithTech](https://en.wikipedia.org/wiki/LithTech)                    | F.E.A.R. series, Condemned series, Shadow of Mordor/War |
| [11 Bit Studios](https://en.wikipedia.org/wiki/11_Bit_Studios)            | ~100  | [Liquid Engine](https://en.wikipedia.org/wiki/Frostpunk#Development)  | Frostpunk | 
| [Frozenbyte](https://en.wikipedia.org/wiki/Frozenbyte)                    | ~100  | [Storm3D](https://www.moddb.com/engines/storm3d)                      | Trine series, Shadowgrounds                       |
| [Kylotonn](https://en.wikipedia.org/wiki/Kylotonn)                        | ~100  | [KtEngine](https://www.kylotonn.com/en/technology)                   | WRC series, TT Isle of Man series, V-Rally 4      |
| [TaleWorlds Entertainment](https://en.wikipedia.org/wiki/TaleWorlds_Entertainment)    | ~100 | *custom engine* | Mount & Blade II: Bannerlord |
| [Daedalic Entertainment](https://en.wikipedia.org/wiki/Daedalic_Entertainment) | ~90  | [Visionaire Studio](https://www.visionaire-studio.net)           | The Whispered World, Deponia series               |
| [Media Molecule](https://en.wikipedia.org/wiki/Media_Molecule)            |  ~80  | [Bubblebath Engine](https://www.gamesradar.com/dreams-uses-the-bubblebath-engine-and-other-fun-factoids-about-media-molecules-next-game) | Dreams |
| [Paradox Development Studio](https://en.wikipedia.org/wiki/Paradox_Development_Studio)  | ~80  | [Clausewitz Engine](https://en.wikipedia.org/wiki/Paradox_Development_Studio#Game_engines) |  Imperator: Rome, Stellaris, Europa Universalis series  |
| [Deck13](https://en.wikipedia.org/wiki/Deck13)                            |  ~70  | [Fledge](https://www.makinggames.biz/%25category%25/building-your-own-engine-part-1-getting-ready-for-the-next-generation6305.html)  |  Lords of the Fallen, The Surge, The Surge 2, Atlas Fallen |
| [Nihon Falcom](https://en.wikipedia.org/wiki/Nihon_Falcom)                |  ~60  | Yamaneko Engine    | Ys VII, Ys VIII, Ys IX |
| [Croteam](https://en.wikipedia.org/wiki/Croteam)                          | +40   | [Serious Engine](https://en.wikipedia.org/wiki/Croteam#Serious_Engine) | The Talos Principle, Serious Sam series

## AA Engines: Small-size Studios (Indie Studios)

Here we have some really small studios that also choose to develop a custom engine for their games. Note that most of those engines rely on other libraries/frameworks for certain parts of the game, the common choices we find are [SDL](https://www.libsdl.org) (cross-platform graphics/input), [OGRE](https://www.ogre3d.org) (rendering engine), [MonoGame](https://www.monogame.net) (cross-platform game framework, also relies on [SDL, SharpDX, OpenTK, OpenAL-Soft...](https://github.com/MonoGame/MonoGame.Dependencies)).

| Company  | Employees | Engine   |   Notable Games   |
| --- | :---: | :---: | --- |
| [Runic Games](https://en.wikipedia.org/wiki/Runic_Games)          | ~40 | *OGRE-based* | [Hob](https://store.steampowered.com/app/404680/Hob) (2017), [Tochlight II](https://store.steampowered.com/app/200710/Torchlight_II) (2012) |
| [Klei Entertainment](https://en.wikipedia.org/wiki/Klei_Entertainment) | 35 | *custom engine* | [Invisible, Inc.](https://store.steampowered.com/app/243970/Invisible_Inc) (2016), [Don't Starve Together](https://store.steampowered.com/app/322330/Dont_Starve_Together) (2016), Shank series
| [Shiro Games](http://shirogames.com)                              | ~30 | [Heaps.io](https://heaps.io/) | [Northgard](https://store.steampowered.com/app/466560/Northgard) (2018), [Evoland](https://store.steampowered.com/app/233470/Evoland) (2013), [Evoland II](https://store.steampowered.com/app/359310/Evoland_2) (2015) |
| [Hello Games](https://en.wikipedia.org/wiki/Hello_Games)          | ~25 | [No Man's Sky Engine](https://en.wikipedia.org/wiki/Development_of_No_Man%27s_Sky#Game_engine)    | [No Man's Sky](https://store.steampowered.com/app/275850/No_Mans_Sky) (2016) |
| [Frictional Games](https://en.wikipedia.org/wiki/Frictional_Games)| ~25 | [HPL engine](https://en.wikipedia.org/wiki/Frictional_Games#HPL_Engine) | [SOMA](https://store.steampowered.com/app/282140/SOMA) (2015), Amnesia series |
| [DrinkBox Studios](https://en.wikipedia.org/wiki/DrinkBox_Studios)| ~25 | *custom engine*  | [Guacamelee](https://store.steampowered.com/app/214770/Guacamelee_Gold_Edition) (2013), [Guacamelee! 2](https://store.steampowered.com/app/534550/Guacamelee_2) (2018), [Severed](http://www.severedgame.com) (2016) |
| [Supergiant Games](https://en.wikipedia.org/wiki/Supergiant_Games)| ~20 | *Forge-based* (2019+) , *MonoGame-based* | [Hades](https://store.steampowered.com/app/1145360/Hades) (2019), [Pyre](https://store.steampowered.com/app/462770/Pyre) (2017), [Transistor](https://store.steampowered.com/app/237930/Transistor) (2014) |
| [Wube Software](https://factorio.com)                             | ~20 | [*Allegro/SDL-based*](https://www.factorio.com/blog/post/fff-230) | [Factorio](https://en.wikipedia.org/wiki/Factorio) (2019) |
| [Chucklefish](https://en.wikipedia.org/wiki/Chucklefish)          | ~20 | [Halley Engine](https://github.com/amzeratul/halley) | [Wargroove](https://store.steampowered.com/app/607050/Wargroove) (2019), [Starbound](https://store.steampowered.com/app/211820/Starbound) (2016) |
| [Ronimo Games](https://en.wikipedia.org/wiki/Ronimo_Games)        | ~17 | [RoniTech Engine](https://www.youtube.com/watch?v=41CCE3BFiqA) (SDL)  | [Awesomenauts](https://store.steampowered.com/app/425541/Awesomenauts__Starter_Pack) (2017)  |
| [Lab Zero Games](https://labzerogames.com)                        | ~17 | [Z-Engine](https://www.reddit.com/r/IAmA/comments/3rk1x9/were_lab_zero_games_makers_of_skullgirls_ama) | [Indivisible](https://store.steampowered.com/app/421170/Indivisible) (2019), [Skullgirls](https://store.steampowered.com/app/245170/Skullgirls) (2013) |
| [Introversion Software](https://en.wikipedia.org/wiki/Introversion_Software) | ~14 | SystemIV (SDL) | [Prison Architect](https://store.steampowered.com/app/233450/Prison_Architect) (2015) |
| [Exor Studios](https://www.exorstudios.com)                       | ~14 | *OGRE-based* [Schmetterling](https://www.gamasutra.com/view/pressreleases/304164/XMORPHtrade_DEFENSE__SCHMETTERLING_ENGINE_FEATURESVIDEO.php) | [The Riftbreaker](https://store.steampowered.com/app/780310/The_Riftbreaker) (2020), [X-Morph: Defense](https://store.steampowered.com/app/408410/XMorph_Defense) (2017) |
| [Tribute Games](https://en.wikipedia.org/wiki/Tribute_Games)      | ~11 | *MonoGame-based* | [Flinthook](https://store.steampowered.com/app/401710/Flinthook) (2017), [Mercenary Kings](https://store.steampowered.com/app/218820/Mercenary_Kings_Reloaded_Edition) (2014) |
| [Thekla Inc.](http://the-witness.net/news) (Jonathan Blow)        | ~10 | [*custom engine*](https://en.wikipedia.org/wiki/The_Witness_(2016_video_game)#Funding_and_development) | [The Witness](https://store.steampowered.com/app/210970/The_Witness) (2016) |
| [Numantian Games](http://www.numantiangames.com/)                 | ~10 | *custom engine*  | [They Are Billions](https://store.steampowered.com/app/644930/They_Are_Billions) (2019), [Lords of Xulimia](https://store.steampowered.com/app/296570/Lords_of_Xulima) (2014) |
| [Nysko Games Ltd.](https://www.nyskogames.com/)                   | ~10 | *custom engine*  | [The Dwarves of Glistenveld](https://store.steampowered.com/app/805520/The_Dwarves_of_Glistenveld) (2019) |
| [Passtech Games](https://www.passtechgames.com/)                  |  10 | OEngine | [Curse of the Dead Gods](https://store.steampowered.com/app/1123770/Curse_of_the_Dead_Gods) (2020) |
| [Terrible Toybox](https://thimbleweedpark.com) (Ron Gilbert)      |   9 | [*custom engine*](https://en.wikipedia.org/wiki/Thimbleweed_Park#Game_engine_and_tools) (SDL) | [Thimbleweed Park](https://store.steampowered.com/app/569860/Thimbleweed_Park) (2017) | 
| [Radical Fish Games](https://www.radicalfishgames.com/)           |   8 | *Impact-based (JS)* | [CrossCode](https://store.steampowered.com/app/368340/CrossCode/) (2018) |
| [Maddy Makes Games](http://www.mattmakesgames.com) (Madeline Thorson)  |  ~7 | *MonoGame-based* | [Celeste](https://store.steampowered.com/app/504230/Celeste) (2018), [TowerFall Ascension](https://store.steampowered.com/app/251470/TowerFall_Ascension) (2014) |
| [Coilworks](https://coilworks.se)                                 |  ~7 | *custom engine*  | [Super Cloudbuilt](https://store.steampowered.com/app/463700/Super_Cloudbuilt) (2017), [Cloudbuilt](https://store.steampowered.com/app/262390/Cloudbuilt) (2014) |
| [Lo-fi Games](https://lofigames.com) (Chris Hunt)                 |   6 | *OGRE-based*     | [Kenshi](https://store.steampowered.com/app/233860/Kenshi) (2018) |
| [D-Pad Studio](http://www.dpadstudio.com)                         |   6 | *MonoGame-based* | [Owlboy](https://store.steampowered.com/app/115800/Owlboy) (2016) |
| [BitKid, Inc.](https://bitkidgames.com)                           |   6 | *MonoGame-based* | [CHASM](https://store.steampowered.com/app/312200/Chasm) (2020) |
| [Nolla Games](https://nollagames.com/)                            |  ~6 | [Falling Everything Engine](https://nollagames.com/fallingeverything/) | [Noita](https://noitagame.com/) (2020) |
| [Double Damage Games](http://doubledamagegames.com)               |   5 | *OGRE-based*     | [Rebel Galaxy Outlaw](https://www.epicgames.com/store/en-US/product/rebel-galaxy-outlaw/home) (2019), [Rebel Galaxy](https://store.steampowered.com/app/290300/Rebel_Galaxy) (2015) |
| [Almost Human Games](http://www.grimrock.net)                     |   4 | *custom engine*  | [Legend of Grimrock](https://store.steampowered.com/app/207170/Legend_of_Grimrock) (2012), [Legend of Grimrock 2](https://store.steampowered.com/app/251730/Legend_of_Grimrock_2) (2014) |
| [Wolfire Games](https://en.wikipedia.org/wiki/Wolfire_Games)      |   4 | Phoenix Engine   | [Overgrowth](https://store.steampowered.com/app/25000/Overgrowth) (2017) |
| [Nuke Nine](http://nukenine.com/)                                 |   3 | *custom engine*  | [Vagante](https://store.steampowered.com/app/323220/Vagante) (2019) |
| [Mega Crit Games](https://www.megacrit.com/)                      |   3 | *custom engine*  | [Slay the Spire](https://store.steampowered.com/app/646570/Slay_the_Spire) (2017) |

## One-person custom engines

Games developed by 1-2 people with custom game engines, engines mostly coded by one person! Respect.

| Company/Developer  | People | Engine | Notable Game(s) |
| --- | :---: | :---: | --- |
| [Lizardcube](https://www.lizardcube.com) (Ben Fiquet and Omar Cornut) | 2 | *custom engine* | [Wonder Boy: The Dragon's Trap](https://store.steampowered.com/app/543260/Wonder_Boy_The_Dragons_Trap) (2017) |
| Guard Crush Games (Jordi Asensio and Cyrille Lagarigue) | 2 | [*MonoGame-based*](https://twitter.com/Guard_Crush/status/1208050181062692867) | [Streets of Rage 4]() |
| [Pocketwatch Games](http://www.pocketwatchgames.com) (Andy Schatz) | 2? | *MonoGame-based* | [Tooth and Tail](https://store.steampowered.com/app/286000/Tooth_and_Tail) (2017) |
| Justin Ma and Matthew Davis   | 2 | [*custom engine*](https://www.reddit.com/r/ftlgame/comments/1kocwg/how_was_ftl_made) | [FTL: Faster Than Light](https://store.steampowered.com/app/212680/FTL_Faster_Than_Light) (2012) |
| Ed Key and David Kanaga       | 2 | [*custom engine*](https://blog.evilwindowdog.com/post/45664340244/indeviews-ep1) | [Proteus](https://store.steampowered.com/app/219680/Proteus) (2013) |
| [Mountain Sheep](http://www.mountainsheep.net) | 2 | *custom engine* | [Hardland](https://store.steampowered.com/app/321980/Hardland) (2019) |
| [Flying Oak Games](http://www.flying-oak.com) (Thomas Altenburger and Florian Hurtaut) | 2 | *MonoGame-based* | [Neuro Voider](https://store.steampowered.com/app/400450/NeuroVoider) (2016), [ScourgeBringer](https://store.steampowered.com/app/1037020/ScourgeBringer)(2020) |
| Marc Flury and Brian Gibson   | 2 | [*custom engine*](https://en.wikipedia.org/wiki/Thumper_(video_game)#Development)  | [Thumper](https://store.steampowered.com/app/356400/Thumper) (2016) |
| Jochum Skoglund and Niklas Myrberg | 2 | *custom engine* | [Heroes of Hammerwatch](https://store.steampowered.com/app/677120/Heroes_of_Hammerwatch) (2018), [Hammerwatch](https://store.steampowered.com/app/239070/Hammerwatch) (2013) |
| [Villa Gorilla](https://villa-gorilla.com/) (Jens Andersson and Mattias Snygg) | 2 | *custom engine* | [Yoku's Island Express](https://store.steampowered.com/app/334940/Yokus_Island_Express/) (2018) |
| [Two Mammoths](http://twomammoths.com/) (Piotr Turecki and Marcin Turecki) | 2 | *custom engine* | [Archaica: The Path of Light](https://store.steampowered.com/app/550590/Archaica_The_Path_of_Light) (2017) |
| [Bare Mettle Entertainment](https://www.baremettle.com) (Madoc Evans) | 1? | *custom engine* | [Exanima](https://store.steampowered.com/app/362490/Exanima) (2015) |
| [Lucas Pope](https://dukope.com/) | 1 | *OpenFL-based*   | [Papers, Please](https://store.steampowered.com/app/239030/Papers_Please) (2013) |
| Terry Cavanagh                | 1 | *custom engine*  | [Super Hexagon](https://store.steampowered.com/app/221640/Super_Hexagon) (2012) |
| Francisco Tellez              | 1 | *SDL-based*      | [Ghost 1.0](https://store.steampowered.com/app/463270/Ghost_10) (2016), [UnEpic](https://store.steampowered.com/app/233980/UnEpic) (2014) |
| [Grid Sage Games](https://www.gridsagegames.com) (Josh Ge) | 1 | *SDL-based*      | [Cogmind](https://store.steampowered.com/app/722730/Cogmind) (2017) |
| Luke Hodorowicz               | 1 | [*custom engine*](https://www.reddit.com/r/Banished/comments/1fj1ur/developer_question_engine_choice) | [Banished](https://store.steampowered.com/app/242920/Banished) (2014) |
| Thomas Happ                   | 1 (5 years) | *MonoGame-based* | [Axiom Verge](https://store.steampowered.com/app/332200/Axiom_Verge) (2015) |
| James Silva                   | 1 | *MonoGame-based* | [Salt and Sanctuary](https://store.steampowered.com/app/283640/Salt_and_Sanctuary) (2016) |
| Eric Barone                   | 1 (4 years) | *MonoGame-based* | [Stardew Valley](https://store.steampowered.com/app/413150/Stardew_Valley) (2016) |
| Tolga Ay                      | 1 | *SFML-based*     | [Remnant of Naezith](https://naezith.com) (2018) |
| Nick Gregory                  | 1 (5 years) | *MonoGame-based* | [Eagle Island](https://store.steampowered.com/app/681110/Eagle_Island) (2019) | 
| [bitBull Ltd.](http://www.bitbull.com) (James Closs)    | 1 (4 years) | *MonoGame-based* | [Jetboard Joust](https://store.steampowered.com/app/1181600/Jetboard_Joust__Scourge_of_the_Mutants) (2020) |
| Benjamin Porter               | 1 (8 years) | *SFML-based* | [MoonQuest](https://store.steampowered.com/app/511540/MoonQuest) (2020) |
| Randall Foster                | 1 (7 years) | *custom engine* | [Kid Baby: Starchild](https://store.steampowered.com/app/559630/Kid_Baby_Starchild) (2019) | 
| [Dennis Gustafsson](http://www.tuxedolabs.com) | 1 | *custom engine* | [Teardown](https://store.steampowered.com/app/1167630/Teardown) (2020) |
| [Christian Whitehead](https://en.wikipedia.org/wiki/Christian_Whitehead) | 1 | [Star Engine](https://en.wikipedia.org/wiki/Star_Engine) | [Sonic Mania](https://store.steampowered.com/app/584400/Sonic_Mania) (2017) |
| [Positech Games](http://www.positech.co.uk/about.shtml) (Cliff Harris) | 1 | *custom engine* | [Production Line](https://store.steampowered.com/app/591370/Production_Line__Car_factory_simulation) (2019), [Democracy 3](https://store.steampowered.com/app/245470/Democracy_3) (2013), [Gratuitous Space Battles](https://store.steampowered.com/app/344840/Gratuitous_Space_Battles_2) (2015) | 
| [Frank Lucas](https://www.angeldu.st/en) | 1 | *custom engine* | [Angeldust](https://store.steampowered.com/app/488440/Angeldust) (2019) |
| [Zachtronics](https://en.wikipedia.org/wiki/Zachtronics) (Zach Barth) | 1 | *custom engine* | [MOLEK-SYNTEZ](https://store.steampowered.com/app/1168880/MOLEKSYNTEZ) (2019), [EXAPUNKS](https://store.steampowered.com/app/716490/EXAPUNKS) (2018), [SHENZHEN I/O](https://store.steampowered.com/app/504210/SHENZHEN_IO) (2016), [Opus Magnum](https://store.steampowered.com/app/558990/Opus_Magnum/) (2017) |
| [Lunar Ray Games](http://www.lunarraygames.com/) (Bodie Lee) | 1 | *custom engine* | [Timespinner](https://store.steampowered.com/app/368620/Timespinner) (2018) |
| [sebagamesdev](https://sebagamesdev.github.io/) | 1 | *custom engine* | [Fight And Rage](https://store.steampowered.com/app/674520/FightN_Rage) (2017) |
| Loïc Dansart                  | 1 | *custom engine* | [Melody's Escape](https://store.steampowered.com/app/270210/Melodys_Escape) (2016) |
| Billy Basso                   | 1 | [*custom engine*](https://www.gamedeveloper.com/art/creature-feature-the-surreal-pixel-art-and-animation-of-animal-well) | [Animal Well](https://store.steampowered.com/app/813230/ANIMAL_WELL/) (2024) |

`TODO: Add below entries to the above lists`

There are some other remarkable games using custom engines that worth mentioning: [Minecraft](https://en.wikipedia.org/wiki/Minecraft) (2011), [Braid](https://store.steampowered.com/app/26800/Braid) (2009), [Super Meat Boy](https://store.steampowered.com/app/40800/Super_Meat_Boy) (2010), [Terraria](https://store.steampowered.com/app/105600/Terraria) (2011), [Dustforce](https://store.steampowered.com/app/65300/Dustforce_DX) (2012), [Sword and Sorcery EP](https://store.steampowered.com/app/204060/Superbrothers_Sword__Sworcery_EP) (2012), [FEZ](https://store.steampowered.com/app/224760/FEZ) (2013), [Dust: An Elysian Tail](https://store.steampowered.com/app/236090/Dust_An_Elysian_Tail) (2013), [Rogue Legacy](https://store.steampowered.com/app/241600/Rogue_Legacy) (2013), [Dyad](https://store.steampowered.com/app/223450/Dyad) (2012), [SpaceChem](https://store.steampowered.com/app/92800/SpaceChem) (2013), [Darkest Dungeon](https://store.steampowered.com/app/262060/Darkest_Dungeon) (2016), [Scrap Mechanic](https://store.steampowered.com/app/387990/Scrap_Mechanic) (2016), [Battle Brothers](https://store.steampowered.com/app/365360/Battle_Brothers) (2015), [Renowned Explorers](https://store.steampowered.com/app/296970/Renowned_Explorers_International_Society) (2015), [Yuppie Psycho](https://store.steampowered.com/app/597760/Yuppie_Psycho) (2019), [Surviving Mars](https://store.steampowered.com/app/464920/Surviving_Mars/) (2018), [The End Is Nigh](https://store.steampowered.com/app/583470/The_End_Is_Nigh) (2017), [The Binding of Isaac: Afterbirth](https://store.steampowered.com/app/401920/The_Binding_of_Isaac_Afterbirth) (2017), [The Binding of Isaac: Rebirth](https://store.steampowered.com/app/250900/The_Binding_of_Isaac_Rebirth) (2014), [BattleBlock Theater](https://store.steampowered.com/app/238460/BattleBlock_Theater) (2013), [Full Metal Furies](https://store.steampowered.com/app/416600/Full_Metal_Furies) (2017), [Binding of Isaac](https://store.steampowered.com/app/113200/The_Binding_of_Isaac) (2011), [Rusted Warfare](https://store.steampowered.com/app/647960/Rusted_Warfare__RTS) (2017).

## Final Words

Feedback and improvements are welcome! :)
