# Total War Script Highlighting

Adds support for syntax highlighting of the scripting language / data format used in [Rome Total War](https://store.steampowered.com/app/885970/Total_War_ROME_REMASTERED/) and [Medieval 2 Total War](https://store.steampowered.com/app/4700/Total_War_MEDIEVAL_II__Definitive_Edition/). The extension is featured in Rome Total War Remastered's [official github documentation for modding support](https://github.com/FeralInteractive/romeremastered?tab=readme-ov-file#third-party-resources) as a useful third party tool by the devs at Feral Interactive ! It is available in the [microsoft marketplace](https://marketplace.visualstudio.com/items?itemName=RenatoPereira.total-war-script-highlighting) and can be installed as usual through the vscode extension interface.

Supported files at this momment are:  

1. Campaign Scripts (inside descr_strat.txt or standalone)
2. Data in descr_strat.txt
3. Data in export_descr_buildings.txt

scripts:  

![feature X](img/scripts.png)  

descr_strat.txt:

![feature X](img/strat.png)

export_descr_buildings.txt:

![feature X](img/edb.png)

# Known Issues

If you are using scripts inside descr_strat.txt (like vanilla)
and not a separate campaign script file then to get correct script
highlighting you must enter ";#script" above the "script" keyword. That
will activate highlighting for scripts inside descr_strat.txt
