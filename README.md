# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## ARAC - All Races All Classes
# ![ARAC icon](https://raw.githubusercontent.com/azerothcore/mod-arac/master/icon.png)
- Latest build status with AzerothCore: [![Build Status](https://github.com/azerothcore/mod-arac/actions/workflows/core-build.yml/badge.svg)](https://github.com/azerothcore/mod-arac/actions)

## Screenshot

![arac](https://raw.githubusercontent.com/azerothcore/mod-arac/master/images/screen1.png)

![arac](https://raw.githubusercontent.com/azerothcore/mod-arac/master/images/screen2.png)


# Usage

- Make a backup of your database before using this module.
- Apply [the SQL query](https://github.com/heyitsbench/mod-arac/blob/master/data/sql/db-world/arac.sql) to your `world` database.
- Update your DBC files (client and server) contained in the release, so add [**Patch-A.MPQ**](https://github.com/heyitsbench/mod-arac/blob/master/Patch-A.MPQ) to your WoW/Data/ directory and update the DBC files in your server/data/dbc/ directory with the ones contained in [the DBFilesClient directory](https://github.com/heyitsbench/mod-arac/tree/master/patch-contents/DBFilesClient).

# Auto-updater

Is not a requirement to use this module to compiled with the core, the SQL and DBC files enough on their own, if you wish to have auto-updater, you would need to add `mod-arac` under your AzerothCore's `modules`, you can read more on [official page](https://www.azerothcore.org/wiki/installing-a-module).

# Need help?

If you encounter a bug, please [open an issue](https://github.com/azerothcore/mod-arac/issues/new).


## Credits

* [iThorgrim](https://github.com/iThorgrim)

AzerothCore: [Repository](https://github.com/azerothcore) - [Website](http://azerothcore.org/) - [Discord chat community](https://discord.gg/PaqQRkd)
