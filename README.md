# WotLK-3.3.5a-HD-client-zhCN
https://discord.gg/Gyb9Z252vt Add support for zhCN
Copy a data file of enUS, and then modify it to zhCN.


### Completed：
  *Change fonts file（Extract from the patch of the source zhCN for replacement.）
  *Interface translation（interfae/GlueXML/GlueStrings.lua and interface/FrameXML/GlobalStrings.lua）
  *component.wow-enUS.txt change component.wow-zhCN.txt
  *locale-zhCN.mpq-wow.ini revise:
      [WoW Config]
      Version=1
      Country=CN
      Language=zh
      Region=5
  
### To do list：
  *DBC file localization(enus reads the first column text of DBC language, zhcn needs to read the fifth column)
  *BLP texture replacement（such as loading screens and maps）
  *sound file replacement
