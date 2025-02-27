---
title: Language support in Azure Video Indexer
description: This article provides a comprehensive list of language support by service features in Azure Video Indexer.
author: Juliako
manager: femila
ms.topic: conceptual
ms.custom: ignite-2022
ms.author: juliako
ms.date: 09/14/2022
---

# Language support in Azure Video Indexer

This article provides a comprehensive list of language support by service features in Azure Video Indexer. For the list and definitions of all the features, see [Overview](video-indexer-overview.md).

The list below contains the source languages for transcription that are supported by the Video Indexer API. 

> [!NOTE]
> Some languages are supported only through the API and not through the Video Indexer website or widgets.
>
> To make sure a language is supported for search, transcription, or translation by the Azure Video Indexer website and widgets, see the [frontend language 
> support table](#language-support-in-frontend-experiences) further below.

## General language support

This section describes languages supported by Azure Video Indexer API.

- Transcription (source language of the video/audio file)
- Language identification (LID)
- Multi-language identification  (MLID)
- Translation

  The following insights are translated, otherwise will remain in English:
  
    - Transcript
    - Keywords
    - Topics
    - Labels
    - Frame patterns (Only to Hebrew as of now)
- Language customization

| **Language**                   | **Code**       | **Transcription** | **LID**\*   | **MLID**\*  | **Translation** | **Customization** (language model)  |
|:------------------------------:|:--------------:|:--------------------:|:-------:|:-------:|:-------------:|:---------------:|
| Afrikaans                        | `af-ZA`      |   |      |    |  | ✔ |
| Arabic (Israel)                  | `ar-IL`      | ✔ |      |   |  | ✔ |
| Arabic (Jordan)                  | `ar-JO`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic (Kuwait)                  | `ar-KW`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic (Lebanon)                 | `ar-LB`      | ✔ |      |   | ✔ | ✔ |
| Arabic (Oman)                    | `ar-OM`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic (Palestinian Authority)   | `ar-PS`      | ✔ |      |   | ✔ | ✔ |
| Arabic (Qatar)                   | `ar-QA`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic (Saudi Arabia)            | `ar-SA`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic (United Arab Emirates)    | `ar-AE`      | ✔ |  ✔  | ✔  | ✔ | ✔ |
| Arabic Egypt                     | `ar-EG`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic Modern Standard (Bahrain) | `ar-BH`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Arabic Syrian Arab Republic      | `ar-SY`      | ✔ | ✔   | ✔  | ✔ | ✔ |
| Bangla                           | `bn-BD`      |   |      |   | ✔ |   |
| Bosnian                          | `bs-Latn`    |   |      |   | ✔ |   |
| Bulgarian                        | `bg-BG`      |   |      |   | ✔ |   |
| Catalan                          | `ca-ES`      |   |      |   | ✔ |   |
| Chinese (Cantonese Traditional)  | `zh-HK`      | ✔ | ✔   | ✔ | ✔ | ✔ |
| Chinese (Simplified)             | `zh-Hans`    | ✔ |   ✔\*|   | ✔ | ✔ |
| Chinese (Traditional)            | `zh-Hant`    |   |      |   | ✔ |  |
| Croatian                         | `hr-HR`      |   |      |   | ✔ |  |
| Czech                            | `cs-CZ`      | ✔ |  ✔  |  ✔ | ✔ | ✔ |
| Danish                           | `da-DK`      | ✔ |  ✔  |  ✔ | ✔ | ✔ |
| Dutch                            | `nl-NL`      | ✔ |  ✔  |  ✔ | ✔ | ✔ |
| English Australia                | `en-AU`      | ✔ |  ✔  |  ✔ | ✔ | ✔ |
| English United Kingdom           | `en-GB`      | ✔ |  ✔  |  ✔ | ✔ | ✔ |
| English United States            | `en-US`      | ✔ |  ✔\* | ✔\* | ✔ | ✔ |
| Estonian                         | `et-EE`      |   |       |   | ✔ |   |
| Fijian                           | `en-FJ`      |   |       |   | ✔ |  |
| Filipino                         | `fil-PH`     |   |       |   | ✔ |  |
| Finnish                          | `fi-FI`      | ✔ |  ✔   |  ✔ | ✔ | ✔ |
| French                           | `fr-FR`      | ✔ |  ✔\* | ✔\* | ✔ | ✔ |
| French (Canada)                  | `fr-CA`      | ✔ |  ✔   | ✔  | ✔ | ✔ |
| German                           | `de-DE`      | ✔ |  ✔ \*| ✔ \*| ✔ | ✔ |
| Greek                            | `el-GR`      |   |       |   | ✔ |   |
| Haitian                          | `fr-HT`      |   |       |   | ✔ |   |
| Hebrew                           | `he-IL`      | ✔ |  ✔   | ✔  | ✔ | ✔ |
| Hindi                            | `hi-IN`      | ✔ |  ✔   | ✔  | ✔ | ✔ |
| Hungarian                        | `hu-HU`      |   |       |   | ✔ |  |
| Indonesian                       | `id-ID`      |   |       |   | ✔ |  |
| Italian                          | `it-IT`      | ✔ | ✔\*  |  ✔ | ✔ | ✔ |
| Japanese                         | `ja-JP`      | ✔ | ✔\*  |  ✔ | ✔ | ✔ |
| Kiswahili                        | `sw-KE`      |   |       |   | ✔ |  |
| Korean                           | `ko-KR`      | ✔ | ✔    |  ✔ | ✔ | ✔ |
| Latvian                          | `lv-LV`      |   |       |   | ✔ |  |
| Lithuanian                       | `lt-LT`      |   |       |   | ✔ |  |
| Malagasy                         | `mg-MG`      |   |       |   | ✔ |  |
| Malay                            | `ms-MY`      |   |       |   | ✔ |  |
| Maltese                          | `mt-MT`      |   |       |   | ✔ |  |
| Norwegian                        | `nb-NO`      | ✔ |  ✔   |  ✔ | ✔ | ✔ |
| Persian                          | `fa-IR`      | ✔ |      |   | ✔ | ✔ |
| Polish                           | `pl-PL`      | ✔ |  ✔   |  ✔ | ✔ | ✔ |
| Portuguese                       | `pt-BR`      | ✔ | ✔\*  |  ✔ | ✔ | ✔ |
| Portuguese (Portugal)            | `pt-PT`      | ✔ | ✔    |  ✔ | ✔ | ✔ |
| Romanian                         | `ro-RO`      |   |       |   | ✔ |  |
| Russian                          | `ru-RU`      | ✔ | ✔\*   |  ✔ | ✔ | ✔ |
| Samoan                           | `en-WS`      |   |       |   | ✔ |  |
| Serbian (Cyrillic)               | `sr-Cyrl-RS` |   |       |   | ✔ |  |
| Serbian (Latin)                  | `sr-Latn-RS` |   |       |   | ✔ |  |
| Slovak                           | `sk-SK`      |   |       |   | ✔ |  |
| Slovenian                        | `sl-SI`      |   |       |   | ✔ |  |
| Spanish                          | `es-ES`      | ✔ | ✔\*  | ✔\*  | ✔ | ✔ |
| Spanish (Mexico)                 | `es-MX`      | ✔ |       |   | ✔ | ✔ |
| Swedish                          | `sv-SE`      | ✔ |  ✔    |  ✔ | ✔ | ✔ |
| Tamil                            | `ta-IN`      |   |        |  | ✔ | |
| Thai                             | `th-TH`      | ✔ |  ✔    |  ✔ | ✔ | ✔ |
| Tongan                           | `to-TO`      |   |       |   | ✔ |  |
| Turkish                          | `tr-TR`      | ✔ | ✔    |  ✔ | ✔ | ✔ |
| Ukrainian                        | `uk-UA`      | ✔  | ✔   |  ✔ | ✔ |  |
| Urdu                             | `ur-PK`      |    |      |   | ✔ |  |
| Vietnamese                       | `vi-VN`      | ✔  |  ✔  | ✔  | ✔ |  |

\*By default, languages marked by * are supported by LID or/and MLID auto-detection. When [uploading a video](https://api-portal.videoindexer.ai/api-details#api=Operations&operation=Upload-Video) with API, you can specify to use other supported languages (see the table above) to auto-detect one or more languages by language identification (LID) or multi-language identification (MLID) by using `customLanguages` parameter. The `customLanguages` parameter allows up to 10 languages to be identified by language identification (LID) or multi-language identification (MLID).

> [!NOTE]
> To change the default languages, set the `customLanguages` parameter. Setting the parameter, will replace the default languages supported by language identification (LID) and by multi-language identification (MLID).

## Language support in frontend experiences

The following table describes language support in the Azure Video Indexer frontend experiences.

* website - the website column lists supported languages for the [Azure Video Indexer website](https://aka.ms/vi-portal-link). For for more information, see [Get started](video-indexer-get-started.md).
* widgets - the [widgets](video-indexer-embed-widgets.md) column lists supported languages for translating the index file. For for more information, see [Get started](video-indexer-embed-widgets.md).

| **Language**                      | **Code**       | **Website** | **Widgets**   | 
|:------------:|:------------:|:--------------------:|:-------:|
| Afrikaans                        | `af-ZA`      |           | ✔ |  
| Arabic (Iraq)                    | `ar-IQ`      |           |  |
| Arabic (Israel)                  | `ar-IL`      |           |  | 
| Arabic (Jordan)                  | `ar-JO`      |           |  | 
| Arabic (Kuwait)                  | `ar-KW`      |           |  |  
| Arabic (Lebanon)                 | `ar-LB`      |           |  |
| Arabic (Oman)                    | `ar-OM`      |           |  | 
| Arabic (Palestinian Authority)   | `ar-PS`      |           |  | 
| Arabic (Qatar)                   | `ar-QA`      |           |  |
| Arabic (Saudi Arabia)            | `ar-SA`      |           |  | 
| Arabic (United Arab Emirates)    | `ar-AE`      |           |  | 
| Arabic Egypt                     | `ar-EG`      |           | ✔ |
| Arabic Modern Standard (Bahrain) | `ar-BH`      |           |  | 
| Arabic Syrian Arab Republic      | `ar-SY`      |           |  | 
| Bangla                           | `bn-BD`      |           |✔  |
| Bosnian                          | `bs-Latn`    |           | ✔ |  
| Bulgarian                        | `bg-BG`      |           |  ✔|  
| Catalan                          | `ca-ES`      |           | ✔ | 
| Chinese (Cantonese Traditional)  | `zh-HK`      |           | ✔ | 
| Chinese (Simplified)             | `zh-Hans`    |      ✔    |✔  |
| Chinese (Traditional)            | `zh-Hant`    |           |✔  |  
| Croatian                         | `hr-HR`      |           |  |
| Czech                            | `cs-CZ`      |    ✔      | ✔ | 
| Danish                           | `da-DK`      |           | ✔ | 
| Dutch                            | `nl-NL`      |   ✔       | ✔ | 
| English Australia                | `en-AU`      |           | ✔ |  
| English United Kingdom           | `en-GB`      |           |  ✔| 
| English United States            | `en-US`      |   ✔       |  ✔ | 
| Estonian                         | `et-EE`      |           |  ✔|  
| Fijian                           | `en-FJ`      |           |  ✔| 
| Filipino                         | `fil-PH`     |           |✔  | 
| Finnish                          | `fi-FI`      |           | ✔ | 
| French                           | `fr-FR`      |           | ✔  | 
| French (Canada)                  | `fr-CA`      | ✔         |✔  | 
| German                           | `de-DE`      | ✔         |  |
| Greek                            | `el-GR`      |           |✔  | 
| Haitian                          | `fr-HT`      |           | ✔ |
| Hebrew                           | `he-IL`      |           | ✔ |
| Hindi                            | `hi-IN`      | ✔         |✔  | 
| Hungarian                        | `hu-HU`      |  ✔        | ✔ | 
| Indonesian                       | `id-ID`      |           |  | 
| Italian                          | `it-IT`      |           |  ✔ | 
| Japanese                         | `ja-JP`      | ✔         | ✔  | 
| Kiswahili                        | `sw-KE`      | ✔         | ✔ | 
| Korean                           | `ko-KR`      |✔          |  ✔|  
| Latvian                          | `lv-LV`      |           |✔  |  
| Lithuanian                       | `lt-LT`      |           | ✔ |
| Malagasy                         | `mg-MG`      |           | ✔ | 
| Malay                            | `ms-MY`      |           |✔  | 
| Maltese                          | `mt-MT`      |           |  |
| Norwegian                        | `nb-NO`      |           | ✔ |
| Persian                          | `fa-IR`      |           |  |
| Polish                           | `pl-PL`      |  ✔        | ✔ | 
| Portuguese                       | `pt-BR`      | ✔         | ✔  | 
| Portuguese (Portugal)            | `pt-PT`      |           |✔  |  
| Romanian                         | `ro-RO`      |           |  ✔| 
| Russian                          | `ru-RU`      | ✔         | ✔  |
| Samoan                           | `en-WS`      |           |  | 
| Serbian (Cyrillic)               | `sr-Cyrl-RS` |           | ✔ | 
| Serbian (Latin)                  | `sr-Latn-RS` |           |  | 
| Slovak                           | `sk-SK`      |           | ✔ |
| Slovenian                        | `sl-SI`      |           | ✔ | 
| Spanish                          | `es-ES`      | ✔         |  ✔ |
| Spanish (Mexico)                 | `es-MX`      |           |  ✔| 
| Swedish                          | `sv-SE`      |  ✔        | ✔ | 
| Tamil                            | `ta-IN`      |           | ✔ | 
| Thai                             | `th-TH`      |           |✔  | 
| Tongan                           | `to-TO`      |           | ✔ |
| Turkish                          | `tr-TR`      | ✔         | ✔ | 
| Ukrainian                        | `uk-UA`      | ✔         |✔  |  
| Urdu                             | `ur-PK`      |           | ✔ |  
| Vietnamese                       | `vi-VN`      | ✔         | ✔ |

## Next steps

- [Overview](video-indexer-overview.md)
- [Release notes](release-notes.md)
