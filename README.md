# A NetRose and EVMGames boilerplate for Unity

This is a boilerplate project. It includes EVMGames/NetRose and all the required dependencies, and will be tagged with local or specific versions of those dependency packages.

Unity version
-------------

The current status is meant to be used in Unity 2020.3 or better. The upper version is not yet determined, and lower versions are not supported (i.e. it may work, but with no responsibilities from the development side).

Dependencies versioning and status
----------------------------------

So far this project relies on a set of packages that I could consider, at best, in beta status. These packages are not officially released and they are tagged 0.0.1 or alike (mostly in experimental status). The referenced packages must be cloned individually besides this boilerplate (i.e. as a sibling directory). They are:

 - com.alephvault.unity.support: [Clone it - 0.0.2](https://github.com/AlephVault/unity-support/tree/0.0.2).
 - com.alephvault.unity.support.generic: [Clone it - 0.0.1](https://github.com/AlephVault/unity-support-generic/tree/0.0.1).
 - com.alephvault.unity.boilerplates: [Clone it - 0.0.1](https://github.com/AlephVault/unity-boilerplates/tree/0.0.1).
 - com.alephvault.unity.layout: [Clone it - 0.0.1](https://github.com/AlephVault/unity-layout/tree/0.0.1).
 - com.alephvault.unity.menuactions: [Clone it - 0.0.1](https://github.com/AlephVault/unity-menu-actions/tree/0.0.1).
 - com.alephvault.unity.camjam: [Clone it - 0.0.1](https://github.com/AlephVault/unity-camjam/tree/0.0.1).
 - com.alephvault.unity.soundaround: [Clone it - 0.0.1](https://github.com/AlephVault/unity-soundaround/tree/0.0.1).
 - com.alephvault.unity.spriteutils: [Clone it - 0.0.4](https://github.com/AlephVault/unity-spriteutils/tree/0.0.4).
 - com.alephvault.unity.textureutils: [Clone it - 0.0.1](https://github.com/AlephVault/unity-textureutils/tree/0.0.1).
 - com.alephvault.unity.binary: [Clone it - 0.0.2](https://github.com/AlephVault/unity-binary/tree/0.0.2).
 - com.alephvault.unity.meetgard: [Clone it - 0.0.3](https://github.com/AlephVault/unity-meetgard/tree/0.0.3).
 - com.alephvault.unity.meetgard.auth: [Clone it - 0.0.3](https://github.com/AlephVault/unity-meetgard-auth/tree/0.0.3).
 - com.alephvault.unity.meetgard.scopes: [Clone it - 0.0.3](https://github.com/AlephVault/unity-meetgard-scopes/tree/0.0.3).
 - com.alephvault.unity.remotestorage: [Clone it - 0.0.2](https://github.com/AlephVault/unity-remotestorage/tree/0.0.2).
 - com.gamemeanmachine.unity.backpack: [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-backpack/-/tree/0.0.1).
 - com.gamemeanmachine.unity.gabtab: [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-gabtab/-/tree/0.0.1).
 - com.gamemeanmachine.unity.windrose: [Clone it - 0.0.6](https://gitlab.com/gamemeanmachine/unity-windrose/-/tree/0.0.6).
 - com.gamemeanmachine.unity.windrose.biomes: [Clone it - 0.0.4](https://gitlab.com/gamemeanmachine/unity-windrose-biomes/-/tree/0.0.4).
 - com.gamemeanmachine.unity.windrose-backpack: [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-windrose-backpack-plugin/-/tree/0.0.1).
 - com.gamemeanmachine.unity.windrose-gabtab: [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-windrose-gabtab-plugin/-/tree/0.0.1).
 - com.gamemeanmachine.unity.windrose.spriteutils: [Clone it - 0.0.4](https://gitlab.com/gamemeanmachine/unity-windrose-spriteutils/-/tree/0.0.4).
 - com.gamemeanmachine.unity.windrose.neighbourteleports [Clone it - 0.0.3](https://gitlab.com/gamemeanmachine/unity-windrose-neighbourteleports/-/tree/0.0.3).
 - com.gamemeanmachine.unity.windrose.cubeworlds [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-windrose-cubeworlds/-/tree/0.0.1).
 - com.gamemeanmachine.unity.windrose.refmapchars [Clone it - 0.0.4](https://gitlab.com/gamemeanmachine/unity-windrose-refmapchars/-/tree/0.0.4).
 - com.gamemeanmachine.unity.windrose.lpcbiomes [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-windrose-lpcbiomes/-/0.0.1).
 - com.gamemeanmachine.unity.netrose [Clone it - 0.0.3](https://gitlab.com/gamemeanmachine/unity-netrose/-/tree/0.0.3).
 - com.gamemeanmachine.unity.netrose.storage [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-netrose-storage/-/tree/0.0.1).
 - com.gamemeanmachine.unity.netrose.refmapchars [Clone it - 0.0.1](https://gitlab.com/gamemeanmachine/unity-netrose-refmapchars/-/tree/0.0.1).
 - com.alephvault.unity.ipfs [Clone it - 0.0.1](https://github.com/AlephVault/unity-ipfs/tree/0.0.1).
 - com.alephvault.unity.evmgames [Clone it - 0.0.1](https://github.com/AlephVault/unity-evmgames/tree/0.0.1).
 - com.alephvault.unity.evmgames.auth [Clone it - 0.0.1](https://github.com/AlephVault/unity-evmgames-auth/tree/0.0.1).
 - com.alephvault.unity.evmgames.livecache [Clone it - 0.0.1](https://github.com/AlephVault/unity-evmgames-livecache/tree/0.0.1).

You can run the attached scripts to clone the dependencies after cloning this project:

 - Windows: clone-all.sh
 - Unix-based (bash): clone-all.bat
 
If you have these repositories already cloned for another boilerplate and version, you can just go inside and checkout the proper (remote, typically) tags instead.

Licenses
--------

Pay attention to license notices in the readme for the following packages:

 - com.gamemeanmachine.unity.windrose.lpcbiomes
 - com.gamemeanmachine.unity.windrose.refmapchars

As a general rule of thumb, NEVER use any asset included in any of the Samples/ directory (in any package), since most of them were generated with tools that DO NOT allow free distribution.

Plugins
-------

In order to use this boilerplate, as described in the documentation for com.alephvault.unity.evmgames, 6 compiled DLL files are needed in the `Plugins/` directory.

These files can be found as part of a compressed file available in this boilerplate: `evmgames-plugins.zip`. That file contained the required DLL files, which must be placed directly into the `Plugins/` directory.

