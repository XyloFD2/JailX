<<<<<<< HEAD
<h1><img src="https://github.com/t-starks/JailX/blob/main/icon.png" height="64" width="64" align="left"></img>JailX</h1><br/>
<p><img src="https://github.com/t-starks/Announcer/blob/main/assets/img/screenshot.png" height="100" width="200" align="left"></img>JailX is a plugin for PocketMine-MP that allows server administrators to send players to a virtual jail. Imprisoned players cannot use teleport commands and will see custom messages upon arrest and release. Additionally, the addon allows you to set the jail position, list incarcerated players, and check a player's remaining incarceration time.</p><br/>

</br>

<table border="1">
  <tr>
    <th>Description</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>API</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.api/JailX" alt="API"></a></td>
  </tr>
  <tr>
    <td>Version</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.state/JailX" alt="Version"></a></td>
  </tr>
  <tr>
    <td>Downloads</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.dl.total/JailX" alt="Downloads"></a></td>
  </tr>
</table>

<h2>Usage</h2>

**Installation**

- Download the plugin: Get the `.phar` file of the plugin you want to install from Poggit.
- File Location: Place the `.phar` file in the `plugins` folder of your PocketMine server.
- Restart server: Restart your server so that the plugin is loaded and active.

**Commands**

- `/setjail` - Sets the jail position
  - **Permission**: `jailx.command.setjail`
  - **Usage**: `/setjail`
  
- `/jail <nick> [duration]` - Arrest a suspicious player
  - **Permission**: `jailx.command.jail`
  - **Usage**: `/jail <nick> [duration]`
  
- `/unjail <nick>` - Release a player from jail
  - **Permission**: `jailx.command.unjail`
  - **Usage**: `/unjail <nick>`
  
- `/jaillist` - List players in jail
  - **Permission**: `jailx.command.jaillist`
  - **Usage**: `/jaillist`
  
- `/jailstatus <nick>` - Shows the status of a player in jail
  - **Permission**: `jailx.command.jailstatus`
  - **Usage**: `/jailstatus <nick>`

**Permissions**

- `jailx.command.setjail` - Allows you to set the jail position.
- `jailx.command.jail` - Allows you to arrest a suspicious player.
- `jailx.command.unjail` - Allows you to release a player from jail.
- `jailx.command.jaillist` - Shows the list of players in jail.
- `jailx.command.jailstatus` - Shows the status of a player in jail.

</br>

**🌐 Web Sites:**

- [<img src="https://pocketmineschool.netlify.app/favicon.ico" alt="Pocket Mine School" width="40" height="40"/> Pocket Mine School](https://pocketmineschool.netlify.app/)
- [<img src="https://mcpetools.surge.sh/favicon.ico" alt="MCPETools" width="40" height="40"/> MCPETools](https://mcpetools.surge.sh/)

**Connect with me:**

- [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/sr_shelby02)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@t-starks)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@t.starkofc)
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/t-stark)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/t-starks)

**💰 You can help me by Donating**

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/t.stark)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/tstark)
=======
# JailX ![Icon](https://github.com/t-starks/JailX/blob/cd9fbff2584c11c5b201cd860b30e1893d7fb12d/icon.png)
JailX is a plugin for PocketMine-MP that allows administrators to manage jail cells for players within the server. This plugin offers several useful features for managing players and maintaining discipline on the server.

## 📊 Stats

<table border="1">
  <tr>
    <th>Description</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>API</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.api/JailX" alt="Api"></a></a></td>
  </tr>
  <tr>
    <td>Version</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.state/JailX" alt="Version"></a></td>
  </tr>
  <tr>
    <td>Downloads</td>
    <td><a href="https://poggit.pmmp.io/p/JailX"><img src="https://poggit.pmmp.io/shield.dl.total/JailX" alt="Downloads"></a></td>
  </tr>
</table>

## Requirements

- PocketMine-MP version 5.0.0 or higher.

## Facility

1. Download the JailX plugin from [PocketMine Plugins](https://poggit.pmmp.io/p/JailX) or directly from the PocketMine plugins directory.
2. Place the downloaded file in the `plugins` folder of your PocketMine-MP server.
3. Restart the server to load the plugin.

## Commands

- `/jail <player>`: Jails a player.
- `/unjail <player>`: Release a player from jail.
- `/setjail`: Set the cell point.

##  Permissions
To manage plugin commands and actions, the following permissions are required:

- `jailx.command.jail`:
Default: op
Description: Allows you to imprison a suspicious player.

- `jailx.command.setjail`:
Default: op
Description: Allows you to configure the position of the jail.

- `jailx.command.unjail`:
Default: op
Description: Allows you to free a player from jail.

Be sure to assign these permissions to the appropriate groups on your server so that administrators and moderators can manage jails correctly.

### 🌐 Web Sites:
- [<img src="https://pocketmineschool.netlify.app/favicon.ico" alt="Pocket Mine School" width="40" height="40"/> Pocket Mine School](https://pocketmineschool.netlify.app/)
- [<img src="https://mcpetools.surge.sh/favicon.ico" alt="MCPETools" width="40" height="40"/> MCPETools](https://mcpetools.surge.sh/)

### Connect with me:
- [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/sr_shelby02)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@t-starks)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@t.starkofc)
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/t-stark)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/t-starks)

## 💰 You can help me by Donating
[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/t.stark)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/tstark) 
>>>>>>> ae39fb60dc4cc788647dcd7f972ac58c7b0f241d
