# Awesome GOG Galaxy

## Communication
* [GOG Café Discord](https://discord.gg/372vxnZ)

## Utilities

* Alternative clients
   * [MiniGalaxy](https://github.com/sharkwouter/minigalaxy) by @sharkwouter.
* Shortcut Creators
   * [GOG Galaxy 2.0 Shortcut Creator](https://github.com/Megalex42/GOG-Galaxy-2.0-Shortcut-Creator) by @Megalex42
* Integration Updaters
   * [GOG Integration Updater](https://github.com/Slashbunny/gog-galaxy-plugin-downloader) by @Slashbunny
   * [GOG Galaxy 2.0 Integrations Scoop Bucket](https://github.com/borger/scoop-galaxy-integrations) by @Borger
* Data import/export
   * [GOG Galaxy Export Script](https://github.com/AB1908/GOG-Galaxy-Export-Script) by @AB1908

## Resources
* GOG Galaxy Integrations Python API
   * Github repository https://github.com/gogcom/galaxy-integrations-python-api
   * PyPi package https://pypi.org/project/galaxy.plugin.api/
   * Galaxy Utils from @tylerbrawl https://github.com/tylerbrawl/Galaxy-Utils
 * GOG Database https://www.gogdb.org/
 * Unofficial GOG.com API docs https://github.com/Yepoleb/gogapidocs

## Galaxy 2.0 Upcoming features

* Completed
  * Integrations search and management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/20#issuecomment-511233784), [2](https://github.com/gogcom/galaxy-integrations-python-api/issues/49#issuecomment-522331088), [3](https://www.resetera.com/threads/gog-galaxy-2-0-is-a-game-changer.139162/page-3#post-24918760))
  * Game deduplication ([1](https://www.reddit.com/r/gog/comments/d5gzld/i_hope_we_can_get_a_better_solution_for/f0m2cb9/))
  * Adding tags from the API ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/49#issuecomment-522331088))
  * Parametrized game launch ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/52#issuecomment-523540588), [2](https://www.reddit.com/r/gog/comments/d43ab3/suggestion_gog_galaxy_20_mark_games_owned/f0ezmkc/))
* In backlog / In progress
  * Chat and friends list for integrations ([1](https://github.com/gogcom/galaxy-integrations-python-api/commit/223adf6a384c438552be697467c9495dc591c448#commitcomment-34429833))
  * DLC management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/23#issuecomment-512730026))
  * Secret achievements ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/63#issuecomment-532543083))
* Will be considered
  * Custom platforms ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/66#issuecomment-532571531))
  * Game language management ([1](https://github.com/gogcom/galaxy-integrations-python-api/issues/8#issuecomment-510074658))

## Installation and Debugging

* Integrations location
   * Windows: `%LOCALAPPDATA%\GOG.com\Galaxy\plugins\installed`
   * macOS: `~/Library/Application\ Support/GOG.com/Galaxy/plugins/installed`

* Log location
   * Windows: `C:\ProgramData\GOG.com\Galaxy\logs\`
   * macOS: `/Users/Shared/GOG.com/Galaxy/Logs`

## Integrations
Below are the integrations (**43** in total) and its features. Hover over links to see the maintainer.
* ✅ implemented
* ⬜ not implemented
* ❌ unsupported by the platform
* ⚠ works with issues
* ⬛ insufficient information


Service                                           | [In built-in search][fog] | Install & Launch | Achievements | Game Time | Friend Recmd. | Friend Presence
:------------------------------------------------ | --: | ---------------: | -----------: | --------: | ------------: | ---------------:
***Official (2)***
Epic Games Store                                  | ✅  | ✅               | ❌           | ✅       | ✅           | ⬜
Xbox                                              | ✅  | ✅               | ✅           | ✅       | ✅           | ✅
***Community, Stores (18)***
[Amazon][amazon]                                  | ⬜  | ✅               | ⬜           | ⬜       | ⬜           | ⬜
[Battle.net][battlenet]                           | ✅  | ✅               | ⬜           | ⬜       | ⬜           | ⬜
[Bethesda.net][bethesda]                          | ✅  | ✅               | ❌           | ❌       | ❌           | ❌
[Discord][discord]                                | ⬜  | ✅               | ⬜           | ⬜       | ✅           | ⬜
[Fanatical][fanatical]                            | ⬜  | ⬜               | ❌           | ❌       | ❌           | ❌
[Humble Bundle][humble]                           | ✅  | ⚠                | ❌           | ⬜       | ❌           | ❌
[IndieGala][indiegala]                            | ⬜  | ⬜               | ❌           | ❌       | ❌           | ❌
[Itch.io (@Ertego)][itch-1]                       | ⬜  | ⚠                | ❌           | ❌       | ❌           | ❌
[Itch.io (@tauqua)][itch-2]                       | ⬜  | ⚠                | ❌           | ❌       | ❌           | ❌
[Itch.io (@freakrho)][itch-3]                     | ⬜  | ⚠                | ❌           | ❌       | ❌           | ❌
[Origin][origin]                                  | ✅  | ✅               | ✅           | ✅       | ✅           | ⬜
[Paradox][paradox]                                | ✅  | ✅               | ⬜           | ⬜       | ⬜           | ⬜
[PSN][psn]                                        | ✅  | ⬜               | ✅           | ⬜       | ✅           | ✅
[Riot][riot]                                      | ⬜  | ✅               | ⬜           | ✅       | ⬜           | ⬜
[Rockstar Games Launcher][rockstar]               | ✅  | ✅               | ✅           | ⚠        | ✅           | ⬜
[Steam][steam]                                    | ✅  | ✅               | ✅           | ✅       | ✅           | ✅
[Twitch.tv][twitch]                               | ⬜  | ✅               | ⬜           | ⬜       | ⬜           | ⬜
[Uplay][uplay]                                    | ✅  | ✅               | ⬜           | ✅       | ✅           | ⬜
[Wargaming.net][wargaming]                        | ✅  | ✅               | ⬜           | ✅        | ✅           | ✅
***Community, Games (6)***
[Final Fantasy XIV][ffxiv]                        | ✅  | ✅               | ⬜           | ❌       | ✅           | ⬜
[Guild Wars 2][gw2]                               | ✅  | ✅               | ✅           | ✅       | ❌           | ❌
[Minecraft][minecraft]                            | ✅  | ✅               | ⬜           | ⬜       | ⬜           | ⬜
[osu!][osu] (showed as NewEgg)                    | ⬜  | ✅               | ⚠           | ✅       | ✅           | ⚠
[Path of Exile][pathofexile]                      | ✅  | ✅               | ✅           | ⬜       | ⬜           | ⬜
[Touhou Project (thcrap)][touhou] (showed as Test)| ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
***Community, Other (1)***
[Generic importer][generic]                       | ⬜  | ✅               | ⬜           | ✅       | ⬜           | ⬜
***Community, Emulators (16)***
[DosBox][dosbox]                                  | ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
[RetroArch][retroarch]                            | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[ScummVM][scummvm] (showed as Amigo)              | ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
[Nintendo 3DS (Citra)][3ds]                       | ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
[Nintendo 64 (RetroArch)][n64]                    | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Nintendo DS][nds]                                | ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
[Nintendo Entertainment System (Mesen)][nes]      | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Nintendo Gameboy (mGBA)][gameboy]                | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Nintendo GameCube (Dolphin)][ncube]              | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Nintendo Switch (Yuzu)][nswitch]                 | ⬜  | ✅               | ❌           | ⬜       | ❌           | ❌
[Nintendo Wii (Dolphin)][nwii]                    | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Nintendo Wii U (Cemu)][nwiiu]                    | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Super Nintendo Entertainment System (Bsnes)][snes] | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Sony PlayStation Portable][psp]                  | ⬜  | ✅               | ❌           | ⬜       | ⬜           | ⬜
[Sony PlayStation 2 (PCSX2)][ps2]                 | ⬜  | ✅               | ❌           | ✅       | ❌           | ❌
[Sony PlayStation 3 (RPCS3)][ps3] (showed as ColecoVision) | ⬜  | ✅               | ⬜           | ✅       | ❌|        ❌

[fog]: https://github.com/FriendsOfGalaxy "Friends of Galaxy"

[origin]: https://github.com/FriendsOfGalaxy/galaxy-integration-origin "Friends of Galaxy"
[psn]: https://github.com/FriendsOfGalaxy/galaxy-integration-psn "Friends of Galaxy"
[steam]: https://github.com/FriendsOfGalaxy/galaxy-integration-steam "Friends of Galaxy"
[uplay]: https://github.com/FriendsOfGalaxy/galaxy-integration-uplay "Friends of Galaxy"
[paradox]: https://github.com/FriendsOfGalaxy/galaxy-integration-paradox "Friends of Galaxy"
[battlenet]: https://github.com/bartok765/galaxy_blizzard_plugin "Maintained by @bartok765"
[bethesda]: https://github.com/TouwaStar/Galaxy_Plugin_Bethesda "Maintainted by @TouwaStar"
[dosbox]: https://github.com/RoorMakurosu/galaxy-integration-dosbox "Maintained by @RoorMakurosu"
[ffxiv]: https://github.com/RZetko/galaxy-integration-ffxiv "Maintainted by @RZetko"
[gw2]: https://github.com/Mixaill/galaxy-integration-gw2 "Maintainted by @Mixaill"
[humble]: https://github.com/UncleGoogle/galaxy-integration-humblebundle "Maintained by @UncleGoogle"
[indiegala]: https://github.com/burnhamup/galaxy-integration-indiegala "Maintained by @Burnhamup"
[pathofexile]: https://github.com/nyash-qq/galaxy-plugin-poe "Maintainted by @nyash-qq"
[twitch]: https://github.com/nyash-qq/galaxy-plugin-twitch "Maintainted by @nyash-qq"
[wargaming]: https://github.com/Mixaill/galaxy-integration-wargaming "Maintainted by @Mixaill"
[minecraft]: https://github.com/TouwaStar/Galaxy_Plugin_Minecraft "Maintainted by @TouwaStar"
[3ds]: https://github.com/j-selby/galaxy-integration-citra "Maintainted by @j-selby"
[nds]: https://github.com/TBemme/galaxy-integration-nds "Maintainted by @TBemme"
[ncube]: https://github.com/JTNDev/galaxy-integration-gc "Maintainted by @JTNDev"
[nwii]: https://github.com/JTNDev/galaxy-integration-wii "Maintainted by @JTNDev"
[ps2]: https://github.com/AHCoder/galaxy-integration-ps2 "Maintainted by @AHCoder"
[psp]: https://github.com/TBemme/galaxy-integration-psp "Maintainted by @TBemme"
[nwiiu]: https://github.com/LeonardFiedrowicz/galaxy-integration-cemu "Maintained by @LeonardFiedrowicz"
[ps3]: https://github.com/mpm11011/galaxy-integration-rpcs3 "Maintained by @mpm11011"
[itch-1]: https://github.com/Ertego/gog-galaxy-itch.io "Maintained by @Ertego"
[rockstar]: https://github.com/tylerbrawl/Galaxy-Plugin-Rockstar "Maintained by @tylerbrawl"
[touhou]: https://gitlab.com/PookaMustard/thcrap-plugin-for-galaxy-2.0 "Maintained by @PookaMustard"
[nes]: https://github.com/AHCoder/galaxy-integration-nes "Maintained by @AHCoder"
[gameboy]: https://github.com/AHCoder/galaxy-integration-ngameboy "Maintained by @AHCoder"
[snes]: https://github.com/AHCoder/galaxy-integration-snes "Maintained by @AHCoder"
[n64]: https://github.com/Riku55/galaxy-integration-n64-RetroArch- "Maintained by @Riku55"
[discord]: https://github.com/Ertego/gog-galaxy-discord "Maintained by @Ertego"
[nswitch]: https://github.com/LeonardFiedrowicz/galaxy-integration-yuzu "Maintained by @LeonardFiedrowicz"
[retroarch]: https://github.com/jshackles/RetroGOG "Maintained by @jshackles"
[scummvm]: https://github.com/micpp42/gog-galaxy-scummvm "Maintained by @micpp42"
[osu]: https://github.com/UncleGoogle/galaxy-integration-osu "Maintained by @UncleGoogle"
[riot]: https://github.com/urwrstkn8mare/gog-riot-integration "Maintained by @urwrstkn8mare"
[generic]: https://github.com/AndrewDWhite/GalaxyGenericImporterPlugin "Maintained by @AndrewDWhite"
[itch-2]: https://github.com/tauqua/gog-galaxy-itch.io "Maintained by @tauqua"
[itch-3]: https://gitlab.com/freakrho/gog-galaxy-itch-integration "Maintained by @freakrho"
[amazon]: https://github.com/Rall3n/galaxy-integration-amazon "Maintained by @Rall3n"
[fanatical]: https://github.com/nosyn00b/GOG2_Fanatical_Plugin "Maintained by @nosyn00b"
