                                                                                      
                     ____            _           __   _                               
                    |  _ \          | |         / _| (_)                              
                    | |_) |   __ _  | |   ___  | |_   _   _ __    ___                 
                    |  _ <   / _` | | |  / _ \ |  _| | | | '__|  / _ \                
                    | |_) | | (_| | | | |  __/ | |   | | | |    |  __/                
                    |____/   \__,_| |_|  \___| |_|   |_| |_|     \___|                
                                                                                      
                                                                                      
                               ___   ___   _    ___    ___                            
                              / __| / __| (_)  / __|  / _ \                           
                             | (__  \__ \  _  | (_ | | (_) |                          
                              \___| |___/ (_)  \___|  \___/                           
                                                                                      
                                     _           __   _                               
                          __   ___  (_)  _ _    / _| (_)  __ _                        
                         / _| / _ \ | | | ' \  |  _| | | / _` |                       
                         \__| \___/ |_| |_||_| |_|   |_| \__, |                       
                                                         |___/                        
                                                                                      
You need a **monospaced font** to show this config correctly. If you you use windows choose: "Consolas".<br>
 **Disable line breaks** in your editor.<br> 
I highly recommend using an editor which supports text highlighting.<br> 
Notepad++ text highlight for CSGO .cfg files can be found here: [https://github.com/k3nnyfr/csgo#csgo-npp-language](https://github.com/k3nnyfr/csgo#csgo-npp-language "github.com/k3nnyfr/csgo#csgo-npp-language")<br> 
I am using Sublime Text with: [github.com/aronj/CFGGameConfigurationSyntax](https://github.com/aronj/CFGGameConfigurationSyntax "github.com/aronj/CFGGameConfigurationSyntax") 
 
**Be caureful** when first using this conifg, read through it, disable/enable or change what you dont like.<br> 
The config might do lots of unexpected stuff to your game.<br> 
Don't use it if you're not willing to read thourgh it. Otherwise it might ruin the game for you! 
 
I consider this config to **still be in beta**:<br> 
I did some testing, but I couln't be botherd to try all combinations, etc.<br> 
Please let me know if anything is not working or missing. (via github) <br>
The preconfigured version is optimized for a german keyboard layout - unfortunately valve doesn't make an 
 international layout easy for me. (check: [redd.it/3f826h](https://redd.it/3f826h "redd.it/3f826h")) 
 
The conifg is splittet and all custiomization can be achieved by editing files in this folder: 
 `...\Counter-Strike Global Offensive\csgo\cfg\customize\ `

(for me: `\Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg\customize\`) 
 
When you first install it please follow the next few steps.<br>
They are here to make futer upadtes of this config easy and painless. (Without compromising your changes)

1. **Backup your: autoexec.cfg, crosshair, radar** if you changed any of this.
   
2. Copy the "cfg" directory to the following directory:<br>
   `...\Counter-Strike Global Offensive\csgo\`<br>
(for me: `\Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\`) 
 
3. If you want hidden radio commands (radio menu) copy the "resource" directory to the following directory:<br>
`...\Counter-Strike Global Offensive\csgo\`<br> 
(check: [steamcommunity.com/sharedfiles/filedetails/?id=187002729](https://steamcommunity.com/sharedfiles/filedetails/?id=1)) 
 
4. Make sure that the following file is not write protected:<br> 
`...\Counter-Strike Global Offensive\csgo\cfg\config.cfg` 
 
5. Copy all files from:<br> 
`...\Counter-Strike Global Offensive\csgo\cfg\customize\empty\`<br> 
or (if you want to use the preconfigured version)<br> 
`...\Counter-Strike Global Offensive\csgo\cfg\customize\preconfigured_german\`<br> 
to:<br> 
`...\Counter-Strike Global Offensive\csgo\cfg\customize\`<br> 
 
6. Customize the config to your needs. <br>
You can accomplish this by editing the files in the the folder:<br> 
`...\Counter-Strike Global Offensive\csgo\cfg\customize\` <br>
After you are done backup this folder.
 
If you want to **update** just follow steps 2 to 4<br> 
If you want to **reinstall** just follow steps 2 to 4 then copy your backed up customize folder to:<br> 
 `...\Counter-Strike Global Offensive\csgo\cfg\customize\` <br>
 
For a simple start only edit level1 files. Type **helpresources** in game console to get help.<br>
folder: `...\Counter-Strike Global Offensive\csgo\cfg\customize\` <br>
 
The most important config files are:

* **`level1_bindstatic.cfg`** - Using **dynamic binds** or `mode_[?]` from this config**?** Put your static binds here. 
* **`level1_configsettings.cfg`** - Setting related to this config can be changed in here.
* **`level1_gamesettings.cfg`** - Here you put all the stuff that normally would be in the autoexec.cfg
It's important to do this to be able to update easily. 
 
For the rest check out the files in the preconfigured folder, they are commented:
 `...\Counter-Strike Global Offensive\csgo\cfg\customize\preconfigured\` 

**Modes** (`mode_default`; `mode_demo`; `mode_training`) are ment to change your configuration (especially binds) optimized for the different ways you use the game (normal play, overwatch/demo, training) <br>
**Dynamic binds** are there to allow you multiple uses of one key. (As long as a modifiere key (for me: ALT) is pressed key binds will change to something else.<br>
**Variable binds** are there to toggle the bind of one key to something else with another key. 

---------

There are different levels of configuration:<br>
* level1 - game setting, config settings, static key binds<br>
* level2 - advanced game settings (crosshair, radar)<br>
* level3 - dynamic key binds<br>
* level4 - low level config changes (radar zooom, crosshair nade)<br>
* level5 - high level conifg changes<br>

`mode_[?]` config files

* levelA - `mode_[?]` static key binds<br>
* levelB - `mode_[?]` dynamic key binds<br>
* levelC - `mode_[?]` configuration <br>
 
To explain how the dynamic binds and the `mode_[?]` system in this config works i made this diagram:            
                                                                                                                    
      ╔═════════════╗                                                                                               
      ║ Start CS:GO ║▒                                                                                              
      ╚══╤══════════╝▒                                                                                              
       ▒▒│▒▒▒▒▒▒▒▒▒▒▒▒                                                                                              
         └┐                                                                                                         
        ┌─┴────────────┐                                                                                            
        │ autoexec.cfg │                                                                                            
        └───┬──────────┘                                                                                            
          ┌─┴──────────────────────────────┐                                                                        
          │ balefire/resources.cfg         │                                                                        
          │ customize/level5_resources.cfg │                                                                        
          └─┬──────────────────────────────┘                                                                        
          ┌─┴───────────────────────────────────┐                                                                   
          │ customize/level1_gamesettings.cfg   │                                                                   
          │ customize/level1_configsettings.cfg │                                                                   
          │ customize/level1_bindstatic.cfg     │                                                                   
          └─┬───────────────────────────────────┘                                                                   
          ┌─┘               ╔══════════════╗  ┌───────────────────────────────────┐                                 
          │               ┌─╢ ALT pressed  ╟──┤ customize/level3_+binddynamic.cfg │                                 
        ╔═╧════════════╗  │ ║(+binddynamic)║  └───────────────────────────────────┘                                 
        ║ mode_default ╟──┤ ╚══════════════╝                                                                        
        ╚═╦════════════╝  │ ╔══════════════╗  ┌────────────────────────────────────┐                                
          ║               └─╢ ALT released ╟──┤ customize/level3_-bindsdynamic.cfg │                                
          ║                 ║(-binddynamic)║  └────────────────────────────────────┘                                
          ╠═╤═══╗           ╚══════════════╝                                                                        
          ║ │ ┌─╨────────────────────────────────────────┐                                                          
          ║ │ │ customize/levelC_mode_demo_on.cfg        │                                                          
          ║ │ │ customize/levelA_demo_bindstatic_add.cfg │                                                          
          ║ │ └─┬────────────────────────────────────────┘                                                          
          ║ │   │              ╔══════════════╗  ┌─────────────────────────────────────────────┐                    
          ║ │   │            ┌─╢ ALT pressed  ╟──┤ customize/level3_+binddynamic.cfg           │                    
          ║ │ ╔═╧═════════╗  │ ║(+binddynamic)║  │ customize/levelB_demo_binddynamic_add_+.cfg │                    
          ║ │ ║ mode_demo ╟──┤ ╚══════════════╝  └─────────────────────────────────────────────┘                    
          ║ │ ╚═╤═════════╝  │ ╔══════════════╗  ┌─────────────────────────────────────────────┐                    
          ║ │   │            └─╢ ALT released ╟──┤ customize/level3_-bindsdynamic.cfg          │                    
          ║ │   │              ║(-binddynamic)║  │ customize/levelB_demo_binddynamic_add_-.cfg │                    
          ║ │   │              ╚══════════════╝  └─────────────────────────────────────────────┘                    
          ║ │ ┌─┴──────────────────────────────────┐                                                                
          ║ │ │ customize/levelC_mode_demo_off.cfg │                                                                
          ║ │ │ customize/level1_bindstatic.cfg    │                                                                
          ║ │ └─┬──────────────────────────────────┘                                                                
          ║ └─<─┘                                                                                                   
          ║                                                                                                         
          ╚═╤═══╗                                                                                                   
            │ ┌─╨────────────────────────────────────────────┐                                                      
            │ │ customize/levelC_mode_training_on.cfg        │                                                      
            │ │ customize/levelA_training_bindstatic_add.cfg │                                                      
            │ └─┬────────────────────────────────────────────┘                                                      
            │   │                  ╔══════════════╗  ┌─────────────────────────────────────────────────┐            
            │   │                ┌─╢ ALT pressed  ╟──┤ customize/level3_+binddynamic.cfg               │            
            │ ╔═╧═════════════╗  │ ║(+binddynamic)║  │ customize/levelB_training_binddynamic_add_+.cfg │            
            │ ║ mode_training ╟──┤ ╚══════════════╝  └─────────────────────────────────────────────────┘            
            │ ╚═╤═════════════╝  │ ╔══════════════╗  ┌─────────────────────────────────────────────────┐            
            │   │                └─╢ ALT released ╟──┤ customize/level3_-bindsdynamic.cfg              │            
            │   │                  ║(-binddynamic)║  │ customize/levelB_training_binddynamic_add_-.cfg │            
            │   │                  ╚══════════════╝  └─────────────────────────────────────────────────┘            
            │ ┌─┴──────────────────────────────────────┐                                                            
            │ │ customize/levelC_mode_training_off.cfg │                                                            
            │ │ customize/level1_bindstatic.cfg        │                                                            
            │ └─┬──────────────────────────────────────┘                                                            
            └─<─┘                                                                                                   
                                                                                                                    

##Contact:
 github: [github.com/SirBalefire/cs-go-config](https://github.com/SirBalefire/cs-go-config "github.com/SirBalefire/cs-go-config")

 steam:  [https://steamcommunity.com/id/balefire/](https://steamcommunity.com/id/balefire/ "steamcommunity.com/id/balefire/")

##Credits:                                                                                                       
[bitbucket.org/DonSanchez/dons-l4d2-autoexec](https://bitbucket.org/DonSanchez/dons-l4d2-autoexec "bitbucket.org/DonSanchez/dons-l4d2-autoexec")
[cs.ingame.de/counter-strike-uebersicht/counter-strike-global-offensive/csgo-skill-groups](https://cs.ingame.de/counter-strike-uebersicht/counter-strike-global-offensive/csgo-skill-groups/)                   
[csgo.gamebanana.com/scripts](https://csgo.gamebanana.com/scripts/)                   
[csgohelp.com/aliases-toggles-binds](https://csgohelp.com/aliases-toggles-binds/)                   
  ^use: [web.archive.org/web/20150315004502/http://csgohelp.com/aliases-toggles-binds](https://web.archive.org/web/20150315004502/http://csgohelp.com/aliases-toggles-binds/)                   
[en.wikipedia.org/wiki/Box-drawing_character](https://en.wikipedia.org/wiki/Box-d)                   
[steamcommunity.com/sharedfiles/filedetails/?id=187002729](https://steamcommunity.com/sharedfiles/filedetails/?id=1)                   
[patorjk.com/software/taag](https://patorjk.com/software/taag/)                   
[twowordbird.com/articles/csgo-console-commands-variable-reference](https://twowordbird.com/articles/csgo-console-commands-variable-reference/)                   
[wiki.multiplay.co.uk/CSGO/Bot_Commands](https://wiki.multiplay.co.uk/CSGO/B)                   
[www.gamerconfig.eu/commands/counter-strike-global-offensive](https://www.gamerconfig.eu/commands/counter-strike-global-offensive/)                   
[www.nmlgaming.co.uk/index.php/updates/59-autoexec-help.html](https://www.nmlgaming.co.uk/index.php/updates/59-autoexec-help.h)

**I'm sorry that these are incomplete!** - When I started this config it was 3 Lines long ;)
