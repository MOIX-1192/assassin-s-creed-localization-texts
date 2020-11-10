# 刺客信条字幕文本|assassin-s-creed-localization-texts
ac localization tools and texts

# 简易使用教程：
##### 1.使用Ubisoft_Forge_Tool_By_Delutto工具解包DataPC.forge，得到众多localization文件；
##### 2.使用Ubisoft_DATA_Tool_By_Delutto解包需要的localization文件；
##### 3.使用命令行工具以 aclocexport.exe 0-LocalizationPackage_English_Subtitles.Localization_Package的格式解包出txt文本即可。

# 2020.11.10更新
英灵殿的forge文件结构有变化，需要使用quickbms解包，所需工具已更新至工具文件夹内（使用ac-valhalla脚本），即可解出.data文件。
```
7799.data = 0-LocalizationPackage_Arabe_MTM.Localization_Package
7800.data = 0-LocalizationPackage_Arabe_Subtitles_MTM.Localization_Package
7801.data = 0-LocalizationPackage_Arabic.Localization_Package
7802.data = 0-LocalizationPackage_Arabic_Subtitles.Localization_Package
7803.data = 0-LocalizationPackage_Auditioning(Male).Localization_Package
7804.data = 0-LocalizationPackage_Auditioning(Male)_Subtitles.Localization_Package
7805.data = 0-LocalizationPackage_Brazil.Localization_Package
7806.data = 0-LocalizationPackage_Brazil_Subtitles.Localization_Package
7807.data = 0-LocalizationPackage_Chinese(Simp).Localization_Package
7808.data = 0-LocalizationPackage_Chinese(Simp)_MTM.Localization_Package
7809.data = 0-LocalizationPackage_Chinese(Simp)_Subtitles.Localization_Package
7810.data = 0-LocalizationPackage_Chinese(Simp)_Subtitles_MTM.Localization_Package
7811.data = 0-LocalizationPackage_Chinese(Trad).Localization_Package
7812.data = 0-LocalizationPackage_Chinese(Trad)_MTM.Localization_Package
7813.data = 0-LocalizationPackage_Chinese(Trad)_Subtitles.Localization_Package
7814.data = 0-LocalizationPackage_Chinese(Trad)_Subtitles_MTM.Localization_Package
7815.data = 0-LocalizationPackage_Czech.Localization_Package
7816.data = 0-LocalizationPackage_Czech_MTM.Localization_Package
7817.data = 0-LocalizationPackage_Czech_Subtitles.Localization_Package
7818.data = 0-LocalizationPackage_Czech_Subtitles_MTM.Localization_Package
7819.data = 0-LocalizationPackage_Dutch.Localization_Package
7820.data = 0-LocalizationPackage_Dutch_MTM.Localization_Package
7821.data = 0-LocalizationPackage_Dutch_Subtitles.Localization_Package
7822.data = 0-LocalizationPackage_Dutch_Subtitles_MTM.Localization_Package
7823.data = 0-LocalizationPackage_English.Localization_Package
7824.data = 0-LocalizationPackage_English_Subtitles.Localization_Package
7825.data = 0-LocalizationPackage_French.Localization_Package
7826.data = 0-LocalizationPackage_French(France)_MTM.Localization_Package
7827.data = 0-LocalizationPackage_French(France)_Subtitles_MTM.Localization_Package
7828.data = 0-LocalizationPackage_French_Subtitles.Localization_Package
7829.data = 0-LocalizationPackage_German.Localization_Package
7830.data = 0-LocalizationPackage_German_MTM.Localization_Package
7831.data = 0-LocalizationPackage_German_Subtitles.Localization_Package
7832.data = 0-LocalizationPackage_German_Subtitles_MTM.Localization_Package
7833.data = 0-LocalizationPackage_Italian.Localization_Package
7834.data = 0-LocalizationPackage_Italian_MTM.Localization_Package
7835.data = 0-LocalizationPackage_Italian_Subtitles.Localization_Package
7836.data = 0-LocalizationPackage_Italian_Subtitles_MTM.Localization_Package
7837.data = 0-LocalizationPackage_Japanese.Localization_Package
7838.data = 0-LocalizationPackage_Japanese_MTM.Localization_Package
7839.data = 0-LocalizationPackage_Japanese_Subtitles.Localization_Package
7840.data = 0-LocalizationPackage_Japanese_Subtitles_MTM.Localization_Package
7841.data = 0-LocalizationPackage_Korean.Localization_Package
7842.data = 0-LocalizationPackage_Korean_MTM.Localization_Package
7843.data = 0-LocalizationPackage_Korean_Subtitles.Localization_Package
7844.data = 0-LocalizationPackage_Korean_Subtitles_MTM.Localization_Package
7845.data = 0-LocalizationPackage_Polish.Localization_Package
7846.data = 0-LocalizationPackage_Polish_MTM.Localization_Package
7847.data = 0-LocalizationPackage_Polish_Subtitles.Localization_Package
7848.data = 0-LocalizationPackage_Polish_Subtitles_MTM.Localization_Package
7849.data = 0-LocalizationPackage_Portuguese(Brazil)_MTM.Localization_Package
7850.data = 0-LocalizationPackage_Portuguese(Brazil)_Subtitles_MTM.Localization_Package
7851.data = 0-LocalizationPackage_Russian.Localization_Package
7852.data = 0-LocalizationPackage_Russian_MTM.Localization_Package
7853.data = 0-LocalizationPackage_Russian_Subtitles.Localization_Package
7854.data = 0-LocalizationPackage_Russian_Subtitles_MTM.Localization_Package
7855.data = 0-LocalizationPackage_Spanish(Mexico).Localization_Package
7856.data = 0-LocalizationPackage_Spanish(Mexico)_MTM.Localization_Package
7857.data = 0-LocalizationPackage_Spanish(Mexico)_Subtitles.Localization_Package
7858.data = 0-LocalizationPackage_Spanish(Mexico)_Subtitles_MTM.Localization_Package
7859.data = 0-LocalizationPackage_Spanish(Spain).Localization_Package
7860.data = 0-LocalizationPackage_Spanish(Spain)_MTM.Localization_Package
7861.data = 0-LocalizationPackage_Spanish(Spain)_Subtitles_MTM.Localization_Package
7862.data = 0-LocalizationPackage_Spanish_Subtitles.Localization_Package
```

其余按之前步骤操作即可。

# 存在的问题
  - 简中对话字幕出现大量\<LF>换行符导致缺字。
 

