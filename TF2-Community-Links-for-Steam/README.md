# TF2 Community Links for Steam
A user script that adds various links to TF2 competitive leagues and TF2/Steam community sites to a Steam Community Profile page for quick and easy access.
* User script only functions on steam profile pages
* Removes padding from below user status and badges for a more compact viewing experience with added links.
   * Note: does not remove padding from below profile links, groups, and friends for better user visibility.
* Ability to disable specific site links by clicking on your respective script manager icon and then clicking on `TF2CLS Options`.
   * By default all sites are enabled.
   * Saving options will automatically refresh the page to display newly selected options.

## Install Instructions
   - Before installing the userscript, please ensure you have a script manager installed in your browser, a list can be found [here](https://github.com/l-Aad-l/userscripts/blob/master/README.md).
   - Install a script directly from GitHub by clicking on the "Install" link in the table below.
   - View the source code directly on GitHub by clickong on the "Source" link in the table below.
   - Install a script from [GreasyFork](https://greasyfork.org/en/users/576570-l-aad-l) (GF) from the userscript site page **or** install the script from [OpenUserJS](https://openuserjs.org/users/Aad/scripts) (OU).

|   Direct Install   |     Source Code      | GreasyFork  | OpenUserJS  |
| :-------------------: | :---------------------: | :-------------: | :-------------: |
| [Install][tf2cls-raw] | [Source][tf2cls-source] |  WIP | [OU][tf2cls-ou] |

<!-- Wiki -->

[tf2cls-wiki]: https://github.com/l-Aad-l/userscripts/wiki/TF2-Community-Links-for-Steam

<!-- RAW -->

[tf2cls-raw]: https://raw.githubusercontent.com/l-Aad-l/userscripts/master/TF2-Community-Links-for-Steam/TF2-Community-Links-Steam.user.js

<!-- Source code -->

[tf2cls-source]: https://github.com/l-Aad-l/userscripts/blob/master/TF2-Community-Links-for-Steam/TF2-Community-Links-Steam.user.js

<!-- Greasyfork -->

<!-- [tf2cls-gf]: -->

<!-- OpenUserJS -->

[tf2cls-ou]: https://openuserjs.org/scripts/Aad/TF2_Community_Links_for_Steam


## Supported Site Links
### Steam Community Sites
[SteamRep](https://steamrep.com)

[SteamDB](https://steamdb.info)

[SteamID](https://steamid.uk)

[VACBanned](http://vacbanned.com)

[](http://)

### TF2 Community Sites
[Rep.TF](https://rep.tf)

[Backpack.tf](https://backpack.tf)

[Petrol.tf SourceBans](https://petrol.tf/sb/index.php)

[Creators.tf SourceBans](https://bans.creators.tf/index.php)

### TF2 Competitive League Sites
[RGL.gg](https:///rgl.gg)

[UGC](https://ugcleague.com)

[ESEA](https://play.esea.net)

[ETF2L](https://etf2l.org)

[ozfortress](https://warzone.ozfortress.com)

[Respawn League](https://respawnleague.com)

[FACEIT](https://faceit.com)

### TF2 Competitive Communtiy Sites
[Logs.tf](https://logs.tf)

~~[SizzlingStats](https://sizzlingstats.com)~~

[Trends.tf](https://trends.tf)

[Demos.tf](https://demos.tf)

[HLPugs.tf](https://hlpugs.tf)

[TF2Center](https://tf2center.com)

## Screenshots
### Full Profile 
![TF2CLS Full Profile](https://github.com/l-Aad-l/userscripts/raw/master/TF2-Community-Links-for-Steam/tf2cls_full_profile_example.png)

### Script Manager Menu
![TF2CLS Script Manager Menu](https://github.com/l-Aad-l/userscripts/raw/master/TF2-Community-Links-for-Steam/tf2cls_script_manager_menu.png)

### Options Menu
![TF2CLS Options Menu](https://github.com/l-Aad-l/userscripts/raw/master/TF2-Community-Links-for-Steam/tf2cls_options_menu.png)

### Padding Examples
#### Steam Default Padding
![Steam Default Padding](https://github.com/l-Aad-l/userscripts/raw/master/TF2-Community-Links-for-Steam/tf2cls_steam_padding.png)

#### TF2CLS Padding
![TF2CLS Padding](https://github.com/l-Aad-l/userscripts/raw/master/TF2-Community-Links-for-Steam/tf2cls_steam_padding_removed.png)

## Change Log
### v0.1.9 - August 25, 2022
* Removed Sizzlingstats(defunct)
* Added Trends.tf
* Removed HLPugs.tf
* Removed deprecated RGL.gg regions
### v0.1.8 - June 10, 2020
* Added Steam icon to userscript
* Updated include regex to only run script on profile pages
### v0.1.7 - June 8, 2020
* HTTPS support for RGL.gg
* Renamed Competitive to Community
### v0.1.6 - June 7, 2020
* Added [Creators.tf SourceBans](https://bans.creators.tf/index.php) link
* Added license information to user script
* Added auto page refresh on MonkeyConfig save to display new settings
* Added options to disable RGL.gg or HLPugs.tf from their respective dropdown menus
* Removed padding from below user status and badges
### v0.1.5 - June 7, 2020
* Changed options name
* Added images for wiki/examples
### v0.1.4 - June 7, 2020
* Updated downloadURL & updateURL
### v0.1.3 - June 7, 2020
* Swapped from [SteamID Parser](https://github.com/mukunda-/steamidparser) to JavaScript module version of [SteamID for Node.js](https://github.com/DoctorMcKay/node-steamid) to handle incorrect SteamID64 instances
* Fixed incorrect SteamID64 instances
    * [Wrong SteamID instance](https://github.com/discord/discord-api-docs/issues/271)
    * [Users having multiple SteamIDs, bug or a new feature?](https://www.reddit.com/r/Steam/comments/acnvfj/users_having_multiple_steamids_bug_or_a_new/)
### v0.1.2 - May 30, 2020 (pre-public release)
* Added [Petrol.tf SourceBans](https://petrol.tf/sb/index.php) link
* Updated metadata block for public release
### v0.1.1 - January 17, 2019 (pre-public release)
* Added MonkeyConfig options to hide potentially unnecessary links
### v0.1.0 - January 15, 2019 (pre-public release)
* Added links to prominent Steam Community, TF2 Competitive and TF2 Community sites