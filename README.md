# BHAPI-Mod-Template

A template mod for [BHAPI](https://github.com/paulevsGitch/BHAPI). It contains only basic imports and gradle setup. You can use it to create mods for BHAPI.

### How to setup:
1. Replace **modid** with your mod id in these files:
	- **gradle.properties**
	- **fabric.mod.json**
2. Rename **modid** folder in *src/main/resources/assets/* to your mod id
3. Update **bhapi_version** in **gradle.properties** if necessary (BHAPI version, can be version number like **1.0.0** or commit name like **fb1f351**)
4. Update **mappings** in **gradle.properties** if necessary (BH Mappings version, can be version number like **1.0.0** or commit name like **9e4003b**)
5. Update information in **fabric.mod.json**:
	- Replace **Mod Name** with your mod name
	- Replace **Mod Description** with your mod description
	- Fill **authors** list
	- Fill **contact** list (link to your mod issue tracker and sources, if mod is closed source - remove sources entry)
	- Replace **Your License** with your license
	- Change **"depends"** if necessary (for example you can specify BHAPI version)
6. Replace mod icon in *src/main/resources/assets/<your_mod_id>/icon.png* with your mod icon
7. Open Command Line/Terminal and execute command **gradle genSources idea** (or **gradle genSources eclipse** if you are using eclipse)

Basic setup done!