# 開放粵語字典

## 說明

本項目提供[開放詞典網](http://kaifangcidian.com/han/yue)[粵語字典](http://kaifangcidian.com/han/yue)的完整數據，並以繁簡兩種字體、耶魯、粵拼等11種粵語拼音方案、以及TSV、CSV、MD等多種文檔格式發佈，以便於人與機器皆能讀取、利用數據創造出衍生作品。

## 特色

* 按照[描寫語言學](https://zh.wikipedia.org/wiki/描写语言学派)的原則編寫的粵語字典
* 以粵語母語者實際講的粵音為標準
* 著重於現代粵語而非古音（即現代語言為主，古代語言為副）
* 主要收錄書面語的字音（口語詞可參考開放詞典的粵語詞典資料庫）
* 完全開源/開放授權的語料數據

## 數據格式

繁體 | 簡體 | 拼音 | 詞例 | 定義 | 又作
--- | --- | --- | --- | --- | ---
撢 | 掸 | daan5 | 撢子，撢土，撢衣服，雞毛撢子 | 拂塵用具，以雞毛或不條作成；用撢子掃去灰塵 | 撣
浚 | 浚 | jeun3 | 浚河，浚渠，浚井，疏浚 | 疏通，挖深 | 濬

## 支援拼音方案

[原數據](yyzd.txt)採用耶魯拼音標音，此外一共11種拼音版本（如粵拼）分別在`dist/tsv`等子目錄裡可找到。

* 耶魯
  * （數字）如：jeun3、yeun3、seung3、cha4、chaam4、chaang4
  * （調符）如：jeun, yeun, seung, chàh, chàahm, chàahng
* 粵拼
  * 如：zeon3, jeon3, soeng3, caa4, caam4, caang4
* 教院
  * 如：dzoen3, joen3, soeng3, tsaa4, tsaam4, tsaang4
* 黃錫凌
  * （數字）如：dzœn³, jœn³, sœŋ³, tsa⁴, tsam⁴, tsaŋ⁴
  * （調符）如：¯dzœn, ¯jœn, ¯sœŋ, ˌtsa, ˌtsam, ˌtsaŋ
* 劉錫祥
  * 如：jun³, yun³, seung³, cha⁴, chaam⁴, chaang⁴
* 國際音標
  * 如：tsɵn˧, jɵn˧, sœːŋ˧, tsʰaː˨˩, tsʰaːm˨˩, tsʰaːŋ˨˩
* 廣州拼音
  * 如：zên3, yên3, sêng3, ca4, cam4, cang4
* 粵語拼音字
  * （數字）如：jont3, yont3, seong3, ca4, cam4, cang4
  * （調符）如：jônt, yônt, seông, ca, cam, cang

## 實現示例

* 國粵消歧義字譜
* 國粵字音對照表

## 另見

* [粵語拼音轉換表](https://github.com/kfcd/pingyam)
* 開放粵語詞典

## 版權

© 2009-2020 [開放詞典](http://www.kaifangcidian.com)

本倉庫所含數據皆依照共享創意（創用CC/知識共享）姓名標示（署名）協議發佈。

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />本著作係採用<a rel="license" href="http://creativecommons.org/licenses/by/3.0/">創用 CC 姓名標示 3.0 未本地化 授權條款</a>授權。
