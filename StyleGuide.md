# Nepali Language Style Guide - LibreOffice Localization 
## LibreOffice Localization Sprint  
### Introduction: 
तपाईँले **LibreOffice** लाई नेपालीमा समायोजन गर्नुको मुख्य उद्देश्य भनेको तपाईँ-हामीजस्तै नेपाली प्रयोगकर्ताले, तपाईँको परिवार र साथीभाइले, आफ्नै भाषामा सजिलैसँग प्रयोग गर्न सकून् भन्ने हो । LibreOffice धेरैखाले व्यक्तिहरूले प्रयोग गर्नुहुन्छ, जस्तै सरकारी कर्मचारी, गाउँ गाउँका विद्यालयका शिक्षक, विद्यार्थी र कर्मचारी, पसले, पत्रकार, लेखक, आदि । तसर्थ, सकेसम्म बुझिने गरेर सरल भाषामा शुद्ध तरिकाले समायोजन गर्नु सबैको जिम्मेवारी हो । समायोजन जति राम्रो भयो त्यति नै प्रयोगकर्तालाई सजिलो हुने भएकाले निम्नानुसारका नियमहरू सबैले पालना गरिदिनुहोस् । यसो गर्दा तपाईँले गर्नुभएको योगदानबाट प्रयोगकर्ताहरूले राम्रोसँग फाइदा लिन सक्नुहुन्छ। ।
### General information
If you have any suggestions or enhancements on this guidelines please add a pull request or merge request to it. 
### Language Guidelines:    
* Honorifics

For verbs or strings being used in the context of commands, in the past versions of LibreOffice, we have been following the honorific form applicable for the pronominal form “तपाईँ”, for example,
Edit →सम्पादन गर्नुहोस्

I think we will have to continue with this practice this time as well.
* Gender

Gender system in Nepali works only in human female nouns, but this confusion can be avoided by using honorific term. However, if the subject of the sentence is non-human, we can use normal form, ie., verb ending with यो, ए, आदि
* Tone
  * Use of passive tone
⠀Example
| English source string | Nepali target translation string |
|-----------------------|----------------------------------|
| She did it.           | उहाँले गर्नुभयो।                        |
| She does it           | उहाँले गर्नुहुन्छ।                        |
* Tense
  * Use of Past Tense

⠀Example
| English source string | Nepali target translation string |
|-----------------------|----------------------------------|
| Translation completed | अनुवाद सकियो                         |
| Download Complete     | डाउनलोड गरियो                        |
* Punctuations

⠀Example
| English Punctuation | Nepali Punctuation |
|---------------------|--------------------|
| .                   | ।                  |
Rest of the Punctuation symbols are similar.
* Trade Names
We should respect other’s trade names and their trademarks. We do not translate their trade names unless we are sure that they have a trade names in Nepali. 

⠀Example
| English source string | Nepali target translation string |
|-----------------------|----------------------------------|
| Google Drive          | Google ड्राइभ                       |
| Microsoft Office      | Microsoft Office                 |
* Technical Words (Leave them untranslated in English if very short and rarely used else transliterate in Nepali)
| English source string                      | Nepali target translation string      |
|--------------------------------------------|---------------------------------------|
| TCP/IP                                     | TCP/IP                                |
| Ethernet                                   | इथरनेट                                 |
| API                                        | API                                   |
| PDF                                        | पिडिएफ                                  |
| System variables of the form “_variables_” | “_variables_” are written as they are |
### Brand voice and tone 
This section should define the LibreOffice brand voice and tone, and how it should be reflected in the localized content.
### Writing style
* सकेसम्म सरल र बोलीचालीको भाषा प्रयोग गर्नुहोस् ।

⠀  जस्तै: "यो मद्दत सन्देश प्रदर्शित गर्नुहोस्" को सट्टा "यो सहायता सन्देश देखाउनुहोस्”
          "शेल कार्वान्वयन गर्नुहोस्" को सट्टा "शेल प्रोग्राम चलाउनुहोस्" वा "shell प्रोग्राम खोल्नुहोस्"
* Keep technical terms and program's names as is: 

For example:
"यो सन्देश पछि, तपाईँ एउटा बउर्न-शेल क्लोन, 'ash' चलाउनु हुनेछ ।" can be "तपाईँ यो सन्देशपछि Bourne-shellको हुवहु प्रोग्राम 'ash' चलाउनुहुनेछ ।"
* Add more information to make the user aware of the context. For example:

⠀"The root file system is a RAM disk." can be translated to
"मूल फाइल प्रणाली RAM डिस्क हो ।" but "यो सिस्टमको root फाइल प्रणाली RAM डिस्क हो ।" makes more sense.
* Please do not copy the exact punctuations from english. We’ve seen excessive use of comma.
* For button texts like "cancel" and "continue" use the phrases  "रद्द गर्नुहोस्" and "जारी राख्नुहोस्"
* Please do not add more than one space between words. Never add space between empty tags or between >, <, / and the words. For example:

⠀```”<text>something</text>" should be "<text>केहि कुरा</text>", not "< text> something </ text>"```
 or such.
* Don't translate the keyboard keys. Use the same symbol that appears on the keyboard. For example: ENTER, Ctrl, Alt, F1, F10. We sometime see people translating F1 to f1 or even एफ १. Please don't do that.
* People have gotten used to words like save, update, etc. Don't complicate things by translating "save file" to "पाठ वचत गर्नुहोस्". You can use "फाइल सेभ गर्नेुहोस्”. We never hear anyone ask  "मेरो फोन अङ्क तपाईँको फोनमा बचत गर्नुभएको छ?" 

Placeholders

⠀
| Sentence in English |
| By [User_name] |
| from %s |
| Sentence in Nepali |
| [User_name] द्वारा |
| %s बाट |

## Nepali Spelling 

### **पूर्णविरामको प्रयोग**
  1 पूर्णविराम चिह्न यो हो - "।" जुन रोमन युनिकोड किबोर्डमा अङ्ग्रेजीको fullstop थिचेर टाइप गर्न सकिन्छ ।
  2 पूर्णविरामको सट्टा पाइप क्यारेक्टर - "|" वा अङ्ग्रेजीको सानो L वा ठुलो i प्रयोग गर्नु गलत हो ।
  3 पूर्णविरामको **अगाडि एउटा खाली स्पेस** छोड्नुपर्छ ।  जस्तै: *"बन्द गर्नुहोस्।"* गलत हो । सही तरिका *"बन्द गर्नुहोस् ।"* हो ।
* **प्राय प्रयोग हुने शब्दहरू**
**1** **तपाईँ :** तपाईँ शब्द यसरी बन्छ: **त ‌+ पा + ई + ँ** । गलत प्रयोगहरू: तपाई, तपाइँ, तपाँइ, तपाइं ।
* **ह्रस्व-दीर्घ**
**१** **शुद्ध लेख्ने तरिका:** तपाईँलाई कुनै शब्दमा प्रयोग हुने इकार-उकारहरूको सही प्रयोग थाहा छैन भने कृपया एकपटक शब्दकोश पल्टाएर वा अनलाइन सर्च गरेर पक्का गर्नुहोस् । ह्रस्व-दीर्घसम्बन्धि नेपालीका साधारण नियमहरू छन्, जसको पालना गरेमा भाषामा निकै राम्रो सुधार हुन्छ । यी लिङ्कहरू क्लिक गरेर ती नियमहरू एकपटक हेर्नुहोस् । 
१: ~[सामान्य नियमहरू](http://nepalibhashabyakaran.blogspot.com/2013/06/blog-post_9429.html)~

**२** **छिटो गर्ने तरिका:** *"Someone should review this translation"* लेखेको बाकसलाई Tick लगाएर छोड्नुभयो भने पछि अरु योगदानकर्ताहरूले तपाईँले गर्नुभएको गल्ती सच्याउन सक्छन् ।
* **शब्दहरू जोड्ने वा नजोड्ने ?** हिन्दी र नेपालीमा एउटा महत्वपूर्ण फरक छ; हिन्दीमा छुट्टएर लेखिने धेरै शब्दहरू नेपालीमा जोडेर लेखिन्छन् !
**1** **-ले, -हरूले, -लाई, हरूलाई, -को, -की, -का, -हरूको/की/का, द्वारा, हरूद्वारा,** आदि जोड्ने ।
**2** **पनि, चाहिँ गर्दा, गर्ने, गर्छ,** आदि नजोड्ने । 
**3** **-अगाडि, -पछाडि, -पछि, -अघि, -सँग, -सित, -नेर, -तिर, -वर, -पर, -भित्र, -बाहिर, माथि, तल,** आदिलाई जो्डने ।
* **अर्धविराम (Comma)को प्रयोग:**
**1** **वाक्यांश छुट्याउँदा धेरै प्रयोग नगर्ने:** अङ्ग्रजीमा *"If you want xyz, do abc"* छ भने *"यदि तपाईं xyz चाहनुहुन्छ भने abc गर्नुहोस्"* लेख्ने हो । अर्धविराम आवश्यक छैन ।
**2** **लामो वाक्यलाई बुझ्ने बनाउन प्रयोग गर्ने:** यदि कुनै वाक्य धेरै लामो छ भने, अथवा दुईभन्दा धेरै वाक्यांश छन् भने यो वाक्यमा प्रयोग भएजस्तै गरि अर्धविराम प्रयोग गरेर पढ्न सजिलो बनाउन सक्नुहुन्छ ।
* **काल (Tense) र सन्दर्भ (Context) मिलाउने:**
* अङ्ग्रेजी वाक्य जुन कालमा लेखिएको छ, त्यही कालमा अनुवाद गर्नुपर्छ । साथै, अनुवाद गरिसकेपछि एकपटक अङ्ग्रेजी र नेपाली दुवैको अर्थ एउटै छ कि छैन भनेर जाँच गर्नुपर्छ । 
* सन्दर्भ अनुसार एउटै वाक्य वा वाक्यांशको फरक फरक अर्थ आउन सक्छ, तसर्थ अहिले अनुवाद गरिरहेको वाक्यको अगाडि वा पछाडि कस्ता वाक्यहरू छन् भनेर विचार गरेर सोहिअनुसारको अनुवाद गर्नुपर्छ । जस्तै "Messaging" शब्दको अर्थ "सन्देश पठाउँदै..." हुन्छ तर त्यही शब्द एउटा Appको नामको रूपमा प्रयोग भएको हुन सक्छ, जुन बेला "सन्देश" मात्र हुन्छ । 
* बटनमा र अन्य ठाउँमा प्रयोग हुँदा फरक तरिकाले अनुवाद गर्नुपर्छ । जस्तै "Go back" भन्ने बटनमा "पछाडि जाने" ठीक हुन्छ भने "You can go back to the previous menu" भन्ने सन्देश छ भने "पछाडिको मेनुमा फर्कन सक्नुहुन्छ" हुन्छ । 
* **शब्द-शब्द उल्था मात्र नगरी वाक्यको अर्थ बुझाउने:**
* अनुवाद गर्दा वाक्यको शब्द शब्दको उल्था लेख्ने होइन । अङ्ग्रेजी वाक्यमा प्रयोग भएका सबै शब्द नेपाली वाक्यमा पनि हुनै पर्छ भन्ने पनि छैन । सरल भाषामा अर्थ बुझ्ने गरि अनुवाद गर्ने हो ।
* प्राय नेपाली उबुन्टु प्रयोगकर्ताहरूले पहिले नै अन्य प्रणालीहरू र मोबाइल फोन प्रयोग गर्ने गरेको हुनाले साधारण अङ्ग्रेजी शब्दहरू जस्तै: app, save, number, hard disk, screen, computer, आदि शब्दहरू बुझ्छन् । तीनलाई "अनुप्रयोग, वचत गर्ने, अङ्क, साह्रो भाँडो, पर्दा, सुशाङ्क" लगायतका बुझ्दै नबुझिने र उस्तै परे अनर्थ लाग्ने गरि उल्था नगर्नुहोस् ।

**Google Translate / Bing Translate जस्ता यान्त्रिक अनुवाद** स् सुविधाहरू प्रयोग गर्दा छिटो र सजिलो हुन्छ, तर तीमार्फत गरिएका अनुवाद प्राय शब्द‍-शब्दको उल्था वा अन्य धेरै कारणर र  भाषाबाट प्रभावित हुने भएकाले जस्ताको तस्तै कपी-पेस्ट नगर्नुहोस् ।

* नेपाली वर्णविन्यास नियमहरू : नेपाली बृहत शब्दकोशमा आधारित भएर काम गर्दा सबैभन्दा सजिलो हुन्छ।
* पञ्चम वर्णको नियम : संस्कृत शब्दहरूमा लागू हुन्छ
* आगन्तुक शव्दहरूका नियमहरू : आगन्तुक शब्दहरूमा नेपाली नियम अनुसार गर्ने
### Terminology
* उपलब्ध भएसम्म नेपाली शब्दकोष या Weblate  मा उपलब्ध शब्द संग्रह प्रयोग गर्नुहोस्।
* [Mozilla Transvision](https://transvision.mozfr.org/?recherche=Nepal&repo=all_projects&sourcelocale=en-US&locale=ne-NP&search_type=strings) को पनि प्रयोग गर्न सकिन्छ 

### Formatting
This guide details the content of the UI and Help files regarding the elements that have or have not to be translated, such as variables or xml elements used in the ```.po``` files.
### Unique terms
Some words have to be unique in your translation files otherwise it will break the product or risk data loss for the user. These terms are:
* **Style names** such as those that you can find in the ```*sw/source/ui/utlui.po*``` file
* **Function names** in Calc (such as ```STRLIST_FUNCTION_NAME```) that you can find in the ```*formula/source/core/resource.po* ```file
* **Math symbols** that you can find in the ```*starmath/source.po* ```file. Note also that **Math symbols** must not contain spaces. For example the ```*perthousand* ```math symbol must not be translated *per thousand* or ```*noelement*``` must not be translated *no element*.
* **Index entries** in the online help such as ```*<bookmark_value\>Editing;Help Files\<\/bookmark_value\>*```, even if they are not in the same files, as it will break the display of the index entry.
* **the | symbol** in Windows installer strings

### Variables and symbols in the UI files
While it is hard to state any hard rules about variables and symbols in the UI files, as LibreOffice uses a mix of technologies in different parts of the source code, this is an attempt at writing down some rules.
* Some files contain a **|** at the end of the strings. This sign is mandatory, as a runtime error in the installer will occur if it is left out. Here is an example from ```instsetoo_native/inc_openoffice/windows/msi_languages.po```:

Up one level|
Create New Folder|

* **$** and **%** most of the time introduce a variable that will be replaced in the user interface, and the word or number following the $ or % must not be translated. Examples:

⠀%PRODUCTNAME                 ''This will display the name of the product''
Change object title of %1    ''%1 will be replaced by the name of the object''
Internal error $(ARG1).      ''$(ARG1) will be replaced by the internal error number''
If **$** is used as a currency as in the following string, though, it is not a variable, and the currency can freely be translated if appropriate in the situation:
 Returns the price per $100 face value of a security with an odd last period
* **\n** indicates a new line in the UI. You should try to organize the string in your translation to fit the line break but do not remove it or the string will be truncated in the dialog box. Example:

#1 Verify Impress is running \n
#2 For Bluetooth user, enable "Preferences"-"LibreOffice Impress"-"General"-"Enable remote control"\n
#3 For WiFi user, tick "Preferences"-"LibreOffice"-"Advanced"-"Enable Experimental Features" \n
* **{x}**, where 'x' is a number, is a variable used in the Impress Remote app. It must not be changed.
* **<X>**, where X is a word in UPPERCASE letters, is *in most cases* a variable which should **not** be translated. Some examples are <FIELD>, <FIELDNAME>, <LOGICOPERATOR> and <VALUE>. Ask on the l10n@global.libreoffice.org mailing list about the specific case if you are in doubt.
* **[n]**, where n is a number, indicates a parameter which value will be expanded in the final string. The number must not be changed or translated.
* **[x]**, where x is a word (perhaps with a digit in the end), *often* indicate a parameter whose value will be expanded in the final string and whose name must not be touched or translated (e.g. [ProductName]), but *sometimes* it is a string that should in fact be translated (e.g. the [M] and [T] in the user interface of the auto-correct settings). Ask on the l10n@global.libreoffice.org mailing list about the specific case if you are in doubt.
* **{xxx}**, where xxx is a string, marks a part of a string which will be omitted if the [parameter] values inside them have no values at the time of display.

Example:
 The file [2][3] is being held in use {by the following process: Name: [4], ID: [5], Window Title: 
 [6]}. Close that application and retry.
In this case, if either the variables [5] or [6] has no value at the time of display, the substring "by the following process: Name: [4], ID: [5], Window Title: [6]" will be left out and not displayed. In that case the final string would not make sense, but that is a different issue. :-)
## XML elements in Help files
The help files contain many XML elements in them that makes it difficult to translate for newcomers. We detail them here, so you have no questions when you do your translation. Be aware, that sometimes elements are nested in other elements. The element contains also attributes that we mention in the description of each element.
The best way to treat these elements is to copy and paste them into your translation, so you make sure that you do not forget a part of them or make a typo. Then you translate the content between the two flags, taking into account the nested elements too.
```
**<ahelp></ahelp>**
```
This is an element that is present in the help directory. However, the information it contains is displayed in the UI as an extended tooltip when it is activated in LibreOffice options tab. This element is ```**<ahelp>the extended tooltip</ahelp>**. ```Example:
```
<ahelp hid=\".\">This menu contains commands for editing the contents of the current document.</ahelp>
```
This element has two attributes that you do not have to translate:
* **hid** (as in the example above)
```
* **visibility**
  ```

```
⠀**<alt></alt>**
```
This element gives an alternative text to a graphic. It is often nested into the [<image>](https://wiki.documentfoundation.org/UI_and_Help_files_Content_Guide#%3Cimage%3E%3C/image%3E) element, example:
<alt id=\"alt_id3159119\">Icon</alt>
* Here you have to translate the word *Icon*, nothing else.
* It also contains **xml-lang=\"en-US\"** for localized graphics, where you have to replace the *en-US* by your language's ISO code.

⠀**<bookmark_value></bookmark_value>**
This element is used for the index entries of the online help. The first word is the main entry, separated by a semicolon. The second word represent the second level entry, for example:
<bookmark_value>page styles; headers</bookmark_value><bookmark_value>page styles;footers</bookmark_value>
<bookmark_value>headers; defining</bookmark_value><bookmark_value>footers; defining</bookmark_value>
<bookmark_value>file names in headers/footers</bookmark_value><bookmark_value>changing;dates,automatically</bookmark_value>
<bookmark_value>dates;updating automatically</bookmark_value><bookmark_value>automatic date updates</bookmark_value>
* Sometimes it happens that the word in the sources has a different meaning in English but not in your language, like *header* and *title*. If you find such entry like <bookmark_value>Header;Title</bookmark_value>, you can just remove it from your translation, as it will have no effect.
* Most of the times several entries are grouped in the same paragraph.
* There should not be two similar entries in the help directory because it will break the index display in the help UI.

```
⠀**<caseinline></caseinline>**
```
This element allows to switch the content depending on the platform (Windows, Linux or Mac). The text displayed will then be different. It is often nested in ```<switchinline>``` or ```<defaultinline>``` elements. Example:
Press ```<switchinline select=\"sys\"> <caseinline select=\"MAC\">Command</caseinline><defaultinline>Ctrl</defaultinline></switchinline>```
and click the tab of the sheet where you want to insert the contents.
* in this example you only have to translate the string *Command* between the two ```*caseinline*``` tags. If you use a different key than ```*Ctrl*``` on your keyboard in your language, you should additionally change it as well (like in German, where the keyboard key is labelled ```"Strg"```) however it belongs to the ```<defaultinline>``` tags.
* this element has one attribute: ```**select**``` as in the example above. This attribute do not have to be translated.

```
⠀**<defaultinline></defaultinline>**
```
This element contains the default text that will be displayed, when there is a possible switch of content depending on the platform. As seen in the previous element, it is often nested with ```<switchinline> and <caseinline>``` elements. Example:
```
Press <switchinline select=\"sys\"> <caseinline select=\"MAC\">Command</caseinline><defaultinline>Ctrl</defaultinline></switchinline>

```
 and click the tab of the sheet where you want to insert the contents.
* this element has no attribute.

```
⠀**<embedvar></embedvar>**
```
This element has no content that needs localization between its tags. But it may be nested too. Example:
```
<embedvar href=\"text/scalc/00/00000004.xhp#optional\"/>
```
* this element has one attribute: **href** as in the example above

```
⠀**<emph></emph>**
```
This element allows to emphasize the string between its tags, so you always have to translate the content in between. Example:
Choose <emph>Format - Merge Cells - Merge and Center Cells</emph>
* this element has no attribute

```
⠀**<image></image>**
```
This element is for the pictures embedded in the files. By itself, it does not contain localizable content, but other elements such as [<alt>](https://wiki.documentfoundation.org/UI_and_Help_files_Content_Guide#%3Calt%3E) that contains localizable strings are always nested in it. Example:
```
<image id=\"img_id3153714\" src=\"sc/res/sf01.png\" width=\"0.1665in\" height=\"0.1665in\"><alt id=\"alt_id3153714\">Icon</alt></image>
```
In this example, you see the <alt></alt> element nested where **Icon** has to be translated.
This element has four attributes that are not to be translated:
* **id** indicates the reference of the picture
* **src** indicates the picture location
* **width** indicates the width of the picture, the metric used can be different (cm for example) but it has no effect on the picture display
* **height** indicates the height of the picture, the metric used here can also be different

```
⠀**<item></item>**
```
This element describes a special formatting applied to the content between its tags.
Examples:
To accept the completion, press ```<item type=\"keycode\">Enter</item>``` or a cursor key.
In this example, you see that the special formatting is applied to emphasize a keyboard entry.
```
In <item type=\"menuitem\"><switchinline select=\"sys\"><caseinline select=\"MAC\">
%PRODUCTNAME - Preferences</caseinline><defaultinline>Tools - Options</defaultinline>
```
```</switchinline> - $[officename] - General </item>```you can set from which year a two-digit number entry is recognized as 20xx.
In this more complex example, you can see that the special formatting is used to emphasize a menu entry.
* **type** is the only attribute of this element. It determines the type of entry to emphasize.

```
⠀**<link></link>**
```
This element indicates a link to another help file or to the web. Examples:
```
<variable id=\"datedif\"><link href=\"text/scalc/01/func_datedif.xhp\">DATEDIF</link></variable>
```
In this example, the content that will be displayed is located in the scalc/01/func_datedif.xhp. You only need to translate DATEDIF.
```
<link href=\"text/scalc/main0210.xhp\" name=\"Page View Object Bar\">Page View Object Bar</link>

```
In this example, the content after the **name** attribute has also to be translated.
This element has four attributes:
* **href** is the reference to the file. It has no localizable content.
* **name** is a completely unused attribute. Localizing it will have no effect whatsoever.
* **target** is the target when it is about a web content. It has no localizable content.
* **type** is the type of content to be displayed. It has no localizable content.

```
⠀**<switchinline></switchinline>**
```
As seen above with the elements [<caseinline></caseinline>](https://wiki.documentfoundation.org/UI_and_Help_files_Content_Guide#%3Ccaseinline%3E) and [<defaultinline></defaultinline>](https://wiki.documentfoundation.org/UI_and_Help_files_Content_Guide#%3Cdefaultinline%3E), this element allows to switch the content depending on the platform (Windows, Linux or Mac). It has no translatable content by itself, but *always* contains the latter nested elements. Example:
```
Press <switchinline select=\"sys\"> <caseinline select=\"MAC\">Command</caseinline><defaultinline>Ctrl</defaultinline>
 </switchinline>
```
and click the tab of the sheet where you want to insert the contents.
* **select** is its only attribute. It has no localizable content.

```
⠀**<variable></variable>**
```
This element determines a content that is reused in the files. The content between its tags has to be localized. Example:
```
<variable id=\"kopfundfusszeilentext\"><ahelp hid=\".uno:EditHeaderAndFooter\">Allows you to define and format headers and footers.</ahelp></variable>
```
This element has two attributes:
* **id** is the name of the variable and must not be translated. Its name could give indication on the type of content, unfortunately most of the time, it is in German.
* **visibility** where the content has not to be translated.

## Search and manage .po files
There are several operations that you can execute directly on your .po files. They are text files and some scripts such as the **translate toolkit** can be used to manipulate them.
As the *Search* field on Weblate is not very effective, using the *grep* command line instructions under Linux will give you much more significant results when you search for a string in multiple files. This part contains a brief description of some scripts, and examples with *grep* and *sed* commands to help you to manipulate your files.
You have first to download the files from Weblate and use the *cd* command to be in the directory you want to work on (ui or help).
**Translate Toolkit**
Most of the time the Translate Toolkit packages are available for your distro. In case it is not or it is an old version, you can get it from here [\[1\]](http://toolkit.translatehouse.org/). If you have any problems installing or using those scripts, do not hesitate to ask for help on the l10n mailing list.
Several scripts from the Translate Toolkit are implemented in Weblate, like the *Failing Checks*, which allow you to check your translation. Some, however, may be relevant for you:
* **poterminology** lets you extract a terminology file from the .po/pot files. Before beginning a translation project, it is a great help to have the most important or ambiguous words filled and translated in a glossary. You will be able to upload this file under a Weblate project too. The [syntax and options](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/poterminology.html) are explained on the site.
* **posegment** will help to increase the quality of your TM by segmenting the po files based on sentence level. The [syntax and options](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/posegment.html) can be found on the site.
* **pocompendium** let you create one big po file from a directory of po files. This is useful if you have for example have split a large file to distribute it to a team of translators. The [syntax and options](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/pocompendium.html) are explained on the site.
* **posplit** let you extract three .po files respectively containing translated strings, untranslated strings and fuzzy strings. The [syntax and options](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/commands/posplit.html) are explained on the site.

## Using ***grep*** **to find strings**
The *grep* command is used under Linux, macOS or Unix-like systems to search through text files, or to search the given file for lines containing a match to the given strings or words. The command will display the line matching the search.
* The simplest syntax is:

```
grep 'word' filename.po
```
Example: 
```
sophie@sophie:~/libo_ui-fr$ grep  'Browse' accessibility/source/helper.po
```
returns
```
msgid "Browse"
```
Here we are telling the grep command to find the word *Browse* in the ```helper.po``` file, which is in the subdirectory *source* of the *accessibility* directory.
* This is not very useful, because you have to know the directory where the string is located, while LibreOffice has so many. So we will add an option that will look recursively into all the directories, contained in the main one. This is the **-r** option.

⠀The syntax is:
```
grep -r 'word' directory
```
Example:
```
sophie@sophie:~/libo_ui-fr$ grep -r 'Browse' accessibility/
```
returns
```
accessibility/source/helper.po:msgid "Browse" 
```
this looks easier! The output gives you the path to the string
* To force to ignore the case of the word (for example to search case-insensitive for *Browse, browse or BROWSE*), you will add the **-i** option. The syntax is:

```
⠀grep -r -i 'word' directory
```
* Now, we want to retrieve the line number of the string in the output too. This is the **-n** option

⠀The syntax is:
```
grep -r -i -n 'word' directory
```
Let me show you an example on our own directory with all the options we know:
```
sophie@sophie:~/libo_ui-fr$ grep -r -i -n 'Browse' accessibility/
```
the output is:
```
accessibility/source/helper.po:23:"RID_STR_ACC_NAME_BROWSEBUTTON\n"
```
```
accessibility/source/helper.po:25:msgid "Browse"
```
You can see, that the second entry contains the word to translate.
* If you want your search to match only the string you have entered, you can add the **-w** option. For example to search for *is* and not retrieve *this* or *his*, etc.
* If you want to search for several words matching only what you have entered, the syntax is:

```
⠀egrep -w -r -n 'word1|word2' directory/
```
Example:
```
sophie@sophie:~/libo_ui-fr$ egrep -w -r -n '~File|_File' sw/
```

the output is:
```
sw/uiconfig/swriter/ui.po:313:msgid "_File System"
sw/uiconfig/swriter/ui.po:1649:msgid "_File name"
sw/source/ui/frmdlg.po:563:msgid "~File name"
sw/source/ui/misc.po:591:#~ msgid "~File system"
sw/source/ui/dialog.po:169:msgid "~File name"
sw/source/ui/index.po:522:msgid "~File"
```
**Note**: we use *egrep* to match a particular regular expression. The *e* is for *extended grep* but you can use the **-E** option for that as well: ``` *grep -E -r -n 'word1|word2' directory/*```
* If you have an escaping character in your search, like an apostrophe (e.g. *child's book* in English or *l'objet* in French), the simplest way to overcome that is to enclose the word to search with double quotes instead of single ones, like in this example:

```
sophie@sophie:~/libo_ui-fr$ grep -r -n "l'objet" sw/
sw/source/ui/utlui.po:4106:msgstr "Cliquer sur l'objet"
sw/source/ui/utlui.po:4133:msgstr "Souris sur l'objet"
sw/source/ui/utlui.po:4151:msgstr "Souris quitte l'objet"
sw/source/ui/utlui.po:4626:#~ msgstr "Renommer l'objet : "
sw/source/core/undo.po:641:msgstr "Supprimer l'objet"
```

* the usual regular expressions applied to grep (*: match zero or more of the preceding character or expression ; ^: match expression at the start of a line, as in ^A, etc.)

⠀**Using** ***sed*** **to modify your files**
Like *grep*, *sed* is a powerful command that let you modify the content of your .po files very easily. Sed stands for *S*tream *ED*itor. For example, if you want to substitute *Header* by *Title* on a file, the syntax will be:
```
sed 's/Header/Title/g' <file.po
```

* first you have the name of the command *s* for *substitute*
* then you have the original word separated by */* delimiters
* after that the word to substitute to the original
* *g* is used for global and will substitute all the occurrences in the file, and not only the first occurrence of the searched word
* then the file where the substitution takes place
* note the presence of the single quotes too.

⠀Sed uses regular expressions to manage the instructions, but the syntax will still remain the same as above. We will not detail all the syntax of the lines given bellow, but they are quite simple expressions you can use safely on your files.
* Remove comments from a file

Example of the file where you want to remove the *# my comment* comment in the `utlui.po`
Enter the following in the `sw/source/ui directory`:
`sophie@sophie:~/libo_ui-fr/sw/source/ui$ sed '/^#\ /d' utlui.po > tt`
that will create the file "tt" in that directory, containing the strings where all the "#" at the beginning of the line (^) followed by nothing are deleted (the *d* in the syntax).
To get the *tt* file turn into *utlui.po* again:
```sophie@sophi:~/libo_ui-fr/sw/source/ui$ mv tt utlui.po```
and now it's a cleaned file!
* Indicate the line of substitution

⠀Taking again our first example, you want to work only on a given line, 306 here:
```
sed '306 s/Header/Title/g' <file.po
```
so now you know how to *grep* first on the file to find the string and then use the *sed* command to correct it
* you will find more information [on the gnu site](http://www.gnu.org/software/sed/manual/sed.html) about the delimiters, the regular expressions and syntax.

### Cultural considerations: 
This section should provide guidance on how to handle cultural references and humor in the localized content.

## Glossary

## References
* https://wiki.documentfoundation.org/Translating_LibreOffice
* [UI and Help files Content Guide](https://wiki.documentfoundation.org/UI_and_Help_files_Content_Guide)
## Please Feel Free 
* You are encouraged to [subscribe to l10n](mailto:l10n+subscribe@global.libreoffice.org)[global.libreoffice.org](mailto:l10n+subscribe@global.libreoffice.org) mailing list. Apart from being a support channel for localizers, it's also the medium where important information for translators (such as string updates and deadlines) is announced. You can also ask 'timar' on irc.libera.chat in the #libreoffice-dev channel.
* You may edit new .ui files using Glade to see them in context. For that install Glade for your distribution (I only know for Linux, so fix it if you know for other distributions) and either a version from master or the last dev build you want to translate.
  * then enter in your terminal:

```
export GLADE_CATALOG_SEARCH_PATH=/opt/libreofficedev4.2/share/glade/** then enter the path of the file you want to display:
glade /opt/libreofficedev4.2/share/config/soffice.cfg/cui/ui/pageformatpage.ui

```





 


