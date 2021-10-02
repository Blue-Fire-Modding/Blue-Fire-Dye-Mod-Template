# Blue-Fire-Dye-Mod-Template
Template for changing the colour of Umbra's base tunic

Edit the uassets using a uasset editor like [UassetGUI](https://github.com/atenfyr/UAssetGUI) or [SoD asset editor](https://github.com/kaiheilos/Utilities)
For detail, [check out this guide](https://github.com/bananaturtlesandwich/Blue-Fire-Modding-Guide)



How to use this Template:

Download the zip file and open the unreal engine project in Unreal Engine 4.25.4(Obviously extract the zip first)

Edit the colour values in the parameters of Player_Clothes_Basic to change the colours of the tunic

Use Pak file should be already diabled

File>Save All

File>Package Project>Windows(64-bit)

Select the folder you want to package to 

Wait for it to package...




Follow standard modding procedure to produce a pak file and remember to delete all uassets and uexps except the Player_Clothes_Basic uasset and uexp before packaging

The mod should work perfectly now!(remember to add _P at the end of the pak file)

*please don't look at the original parent material it's a fucking mess*

Feel free to add to this if you're a modder and please send a pull request if you do
