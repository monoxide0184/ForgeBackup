# ForgeBackup v0.3.1 #

ForgeBackup is a simple mod that sits and backs up your server or single player worlds as you play. No more corrupted worlds due to issues with mods or other issues with your computer, just restore a backup and most of your work will still be saved even if disaster should strike.

## Installation: ##

Just download MinecraftForge and the appropriate version of this mod for your version of Minecraft from below and place this mod in your mods folder.

## Downloads: ##

I still consider this mod somewhat beta quality code, however I use this mod regularly myself as do several of my testers.

*1.4.6/1.4.7*

* [forgebackup-universal-1.4.7-0.3.1.22.jar][b22]

## Features: ##

* Perform automatic backups of SMP and SSP worlds.
* Perform manual backups using the /backup command. This command can be used by command blocks if you allow it in the config.
* Basic permissions support to allow anyone or only ops to run backups manually.
* ForgeBackup is only required to be downloaded on the server or SMP worlds. The same download is used for both the client (SSP) and the server.
* Ability to store backups anywhere via the configuration file.
* Automatically clean up old backups (disabled by default).
* Disable certain dimensions from being backed up. Don't backup large dimensions that you don't need or want to.
* Ability to totally configure what gets backed up. Backup mods, configuration and your world, or any other files or folders you may wish to.

## Bug Reports: ##

Always happy to receive them, but I can't help you if you don't help me. If you
can't provide a log, then I probably can't help you. Please provide the console
output as well as the ForgeModLoader.log (typically either ForgeModLoader-client-0.log
or ForgeModLoader-server-0.log) from your minecraft folder. Please
[post issues on GitHub][gh-issues] if you are able. I'm also usually available on
[EsperNet IRC][irc] as monoxide.

## Permissions: ##

[ForgeBackup is an open source mod][gh]. It is released under [the MIT license][license].

  [b22]: http://bit.ly/12XW7gy
  [gh]: https://github.com/monoxide0184/ForgeBackup
  [gh-issues]: https://github.com/monoxide0184/ForgeBackup/issues
  [license]: https://github.com/monoxide0184/ForgeBackup/blob/master/LICENSE.md
  [irc]: http://esper.net/publicirc.php

