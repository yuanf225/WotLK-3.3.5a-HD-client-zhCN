# WotLK-3.3.5a-HD-client-zhCN
https://discord.gg/Gyb9Z252vt Add support for zhCN
Copy a data file of enUS, and then modify it to zhCN.


### Completed：
  1) Change fonts file（Extract from the patch of the source zhCN for replacement.）
  2) Interface translation（interfae/GlueXML/GlueStrings.lua and interface/FrameXML/GlobalStrings.lua）
  3) component.wow-enUS.txt change component.wow-zhCN.txt
  4) locale-zhCN.mpq-wow.ini revise:
      [WoW Config]
      Version=1
      Country=CN
      Language=zh
      Region=5
  
### To do list：
  1) DBC file localization(enus reads the first column text of DBC language, zhcn needs to read the fifth column)
  2) BLP texture replacement（such as loading screens and maps）
     #patch-enus\Interface\WorldMap\Hallso
     #patch-enus\Interface\WorldMap\TheCullingofStratholme
     #patch-enus\Interface\WorldMap\TheNexus
     #patch-enus\Interface\WorldMap\TheOculus
     #
     #
     #
     #
     #
     #
  4) sound file replacement
     #
     #
     #
     #
