---
{"dg-publish":true,"permalink":"/modding-tools/sorting-plugin-load-order/mlox/index/","title":"mlox","tags":["mlox","Load-order"]}
---

![Tools_mlox_icon.png|-side](/img/user/Assets/Modding%20Tools/mlox/index/Tools_mlox_icon.png)
mlox is a mini "expert system" for advising you on your set of plugins.

Use mlox to check for plugin dependencies and conflicts, and to sort your plugins into an optimal load order.

>[!abstract]- Pages contained within this folder 
>
>This article is part of a series on [[Modding Tools/Sorting Plugin Load Order/Mlox/index\|mlox]]
> 
>* [[Modding Tools/Sorting Plugin Load Order/Mlox/Contributing to mlox Rules\|Contributing to mlox Rules]] -- How to contribute to the rule-base of mlox 
>* [[Modding Tools/Sorting Plugin Load Order/Mlox/Tutorial - How to Add Rules to the mlox-rules Repository\|Tutorial - How to Add Rules to the mlox-rules Repository]]
>* [[Modding Tools/Sorting Plugin Load Order/Mlox/mlox Rule Guidelines\|mlox Rule Guidelines]] -- Guidelines for Editors of the mlox rule-base
>* [[Modding Tools/Sorting Plugin Load Order/Mlox/Building mlox\|Building mlox]] -- Creating your own build of mlox
>* [[Modding Tools/Sorting Plugin Load Order/Mlox/mlox History\|mlox History]] -- A brief history of the development of mlox 

# About
mlox is designed to help people manage large collections of plugins for popular Elder Scrolls games from Bethesda Softworks.

The program sorts plugins based on a very simple set of ordering rules that comprise a partial order over the set of plugins using a standard topological sort.

It also provides advice on plugin conflicts, missing pre-requisites, and general information of interest based on the user's particular set of plugins.

# Features
* Creates an optimal load order.
* Warns about missing pre-requisites.
* Warns about plugin conflicts.
* Gives useful, but often overlooked information about installed mods.
* Customizable via a rules file.
* runs on Windows or Linux
* can check someone else's load list from a file:  
        `mlox.py -wf Morrowind.ini`  
        `mlox.py -wf someones_load_order_posting.txt`  
    or just paste the list of plugins into the Active plugins pane of the GUI. (mlox understands output of Wrye Mash and Reorder Mods++)

**Note**: mlox does not tell you if you have missing Meshes or Textures, it is only a load order tool, and does not report problems with resources!

![Tools_mlox_gui_1.png](/img/user/Assets/Modding%20Tools/mlox/index/Tools_mlox_gui_1.png)

# Downloading
The latest stable version of mlox can be found [here](https://github.com/rfuzzo/mlox/releases), and the source code can be found on [github](https://github.com/rfuzzo/mlox).

Unpack the mlox application archive in your Morrowind directory. You should see an mlox directory in the same directory as Morrowind.exe.

If Mlox does not run you may need the [Microsoft Visual C++ 2008 Redistributable Package (vcredist_x86.exe)](http://www.microsoft.com/downloads/details.aspx?FamilyID=9b2da534-3e03-4391-8a4d-074b9f2bc1bf&displaylang=en).
