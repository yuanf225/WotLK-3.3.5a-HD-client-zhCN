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
  5) BLP texture replacement（such as loading screens and maps）
  6) DBC file localization(enus reads the first column text of DBC language, zhcn needs to read the fifth column)
  
### To do list：
  1)sound file replacement
     - [speech-zhcn\Sound\Creature\Patch1.8_VO_Lines]
