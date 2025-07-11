<h1 align="center">
  <img src="https://raw.githubusercontent.com/WorldBoxOpenMods/ModLoader/master/resources/logo.png" alt="logo" width="200">
  <br/>
  NeoModLoader
</h1>

<p align="center">
  <a href="https://github.com/WorldBoxOpenMods/ModLoader/blob/master/README.cz.md"><img alt="zh" src="https://img.shields.io/badge/切换语言-简体中文-red.svg"></a>
  <a href="https://github.com/WorldBoxOpenMods/ModLoader/blob/master/README.md"><img alt="en" src="https://img.shields.io/badge/Change Language-English-green.svg"></a>
<br/>
      <a href="https://github.com/WorldBoxOpenMods/ModLoader/blob/master/README.cz.md">中文介绍</a>
    |
  <a href="https://github.com/WorldBoxOpenMods/ModLoader/blob/master/README.md">README in English</a>
<br/>
    <small><small>The logo is generated by Image Creator on 2023/10/13. Inform the remedy if there is infringement.</small></small>
</p>

A new mod loader for [Worldbox](http://www.superworldbox.com/) after [NCMS](https://denq04.github.io/ncms/), called NML
for short. Detailed introduction look [Gitbook](https://worldboxopenmods.gitbook.io/mod-tutorial-en).

<h2 align="center"> Overview </h2>

<h3 align="center">
    How to install
</h3>

### Automatic install

The installer is available for both Linux and Windows.  
Click the links below to download:
* [Linux Installer](https://github.com/gmBlahaj/nml-installer/releases/download/nml/nml-setup-linux)
* [Windows Installer](https://github.com/gmBlahaj/nml-installer/releases/download/nml/nml-setup-win.exe)

</br>

### Downgrade Tool

If you're trying to play mods that aren't compatible with the latest version of Worldbox, you can use **Worldbox Rewind** to downgrade to an older version:
* [Download Worldbox Rewind](https://gmblahaj.xyz/pages/rewind)


</br>

### Manual install

1. Download NeoModLoader.dll (and NeoModLoader.pdb) in "releases" at the right of the page and put it in
   GAMEPATH/worldbox_Data/StreamingAssets/mods folder
2. Delete NCMS_memload.dll (They can be installed together but not suggested)
3. Start the game with experimental mode enabled

It is recommended to subscribe to the NML item on the Steam Workshop to receive automatic updates

<h2 align="center">Others</h2>
<h3 align="center">
<a href="https://github.com/WorldBoxOpenMods/ModLoader/issues/new?assignees=&labels=bug&projects=&template=bug-report-en.yaml&title=%5BBug%5D%3A+">
Report BUG</a>
</h3>
<h3 align="center">
<a href="https://worldboxopenmods.gitbook.io/mod-tutorial-en/make-mod/start">Make mod</a>
</h3>
<p align="center">
    You can contribute to accelerate the <a href="https://github.com/WorldBoxOpenMods/Documentation-en">English Version</a>
</p>
<h3 align="center">
    How to compile NML
</h3>

#### Compile with IDE

1. clone
2. Open NeoModLoader.csproj with IDE(VS/Rider/others) and click "Build"

#### Compile with command

1. clone
2. Download and install [.NET Core SDK](https://dotnet.microsoft.com/download)
3. cd path-to-folder-of-NeoModLoader.csproj
4. Run `dotnet build NeoModLoader.csproj`

<h3 align="center">
    How to contribute
</h3>

All contributions are welcome. But to avoid time wasted, follow the below steps.

For small fixes:

1. Fork
2. Coding
3. Pull request
4. Wait for result

New features or code reconstruction:

1. New issue about what you want to do and simple reasons about it
2. After discussion, do it as small fixes.

<h3 align="center">
    Future roadmap
</h3>

1. Auto layout window
2. Mod one-click install for various platforms
3. Manage vanilla tab buttons
4. Assembly-CSharp mod support(modify game code)
