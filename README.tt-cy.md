<div align="left">
	<img width="540" height="540" src="media/logo.jpg" alt="Искиткеч татар">
</div>

# Искиткеч татар

[![en](https://img.shields.io/badge/lang-en-red.svg)](README.md)

# Бит турында

Монда татар теле өчен җентекләп сайланган китапханәләр, чыганаклар, хезмәтләр һәм дата җыелмаларын табырга була.

**Эчтәлек**

- [LLM-нар](#llm-нар)
- [Параллель текстлар җыелмалары](#параллель-текстлар-җыелмалары)
- [Монокорпуслар җыелмалары](#монокорпуслар-җыелмалары)
- [Аудио дата җыелмалары](#аудио-дата-җыелмалары)
- [Куллануга әзер тел модельләре](#куллануга-әзер-тел-модельләре)
- [Башка дата җыелмалары](#башка-дата-җыелмалары)
- [Кирил-латин имлә конверторлары](#кирил-латин-имлә-конверторлары)
- [Текст тавышлау & тавышны текстлау](#текст-тавышлау--тавышны-текстлау)
- [Тел корпуслары](#тел-корпуслары)
- [Тел анализаторлары](#тел-анализаторлары)
- [Ихтияри тәрҗемә проектлары](#ихтияри-тәрҗемә-проектлары)
- [Миллиләштерү әсбаплары](#миллиләштерү-әсбаплары)
- [Браузер плагиннары](#браузер-плагиннары)

## LLM-нар

* [tweety-tatar-base](https://huggingface.co/Tweeties/tweety-tatar-base-7b-2024-v1) - Mistral-7B-Instruct-v0.2
  моделленнан MistralAI белән өйрәтелгән татар телле LLM

## Параллель текстлар җыелмалары

* [ИПСАН параллель корпус дәйтәсары](https://huggingface.co/datasets/IPSAN/tatar_translation_dataset) - [ИПСАН](https://www.antat.ru/tt/)
  туплаган дәйтәсары.
* [Айгиз Кунафин дәйтәсары](https://huggingface.co/datasets/AigizK/tatar-russian-parallel-corpora) - Тел энтузиасты
  Айгиз Кунафин туплаган дәйтәсар.
* The Open Parallel
  Corpus ([tt-en](https://opus.nlpl.eu/results/tt&en/corpus-result-table), [tt-ru](https://opus.nlpl.eu/results/tt&ru/corpus-result-table)) -
  Ачык параллель текстлар җыентыгы(⚠ тазартырга зарур).
* [Apertium тел кушлары](https://github.com/apertium/apertium-tat-rus) - [Apertium](https://www.apertium.org/index.rus.html)
  проектының тәрҗемә өчен кулланган тел кушлары.

## Монокорпуслар җыелмалары

* [uonlp/CulturaX](https://huggingface.co/datasets/uonlp/CulturaX) - [Орегон университеты](http://nlp.uoregon.edu/)
  туплаган күптелле дәйтәсар.
* [Neurotatarlar дәйтасары](https://huggingface.co/neurotatarlar) - Без эшкәрткән китаплар һәм чыгарылган документллар
  дәйтасары.
* [Azatliq's crawled document](https://huggingface.co/datasets/veryrealtatarperson/tt-azatliq-crawl) - [Azatliq](https://www.azatliq.org/)
  сайтыннан чыгарылган документллар дәйтасары.

## Аудио дата җыелмалары

* [Mozilla common voice](https://commonvoice.mozilla.org/tt/datasets) - ихтияриләр туплаган ачык тавыш дата җыелмалары.

## Куллануга әзер тел модельләре

* [MMS-1b-tatar](https://huggingface.co/AigizK/wav2vec2-large-mms-1b-tatar) - Татар теленә көйләнгән ASR.

## Башка дата җыелмалары

* [SART](https://github.com/tat-nlp/SART) - Татар телендә ошашлык, аналогия һәм якынлык дата җыелмалары.

## Кирил-латин имлә конверторлары

* [baltoslav.eu](https://baltoslav.eu/lat/index.php)
* [speak.tatar](https://speak.tatar/en/lang/converter/tat/latin/cyrillic/)
* [yusuke1997.com](https://yusuke1997.com/tatar) ([чыганак](https://github.com/yusuke1997/translit_tt))
* [COPIUS](https://www.copius.eu/trtr.php?lang=tat)

## Текстны тавышлау & тавышны текстлау

* [speech.tatar](https://speech.tatar/) - [ИПСАН](https://www.antat.ru/tt/) ясаган тавышлау хезмәте.
* [Tatsoft ASR](https://tat-asr.api.translate.tatar/docs) - Tatsoft-ның тавышны текстка таныту өчен API.
* [Tatsoft TTS](https://tat-tts.api.translate.tatar/docs) - Tatsoft-ның текстны тавышлау өчен API.
* [TatarSCR](https://github.com/IS2AI/TatarSCR) - Ачык чыганаклы татарча боерыклар дәйтәсары.
* [Silero Models](https://github.com/snakers4/silero-models?tab=readme-ov-file#cyrillic-languages) - Татар телен таэмин
  итүче алдан өйрәтелгән STT / TTS модельләре. Минималь эшләүче
  урнәкне [монда](https://colab.research.google.com/drive/1hsn_Liy19eu17mb9qEQhM2GMEBxzcAP-#scrollTo=7b9e704a) табырга
  була.
* [Massively Multilingual Speech](https://huggingface.co/spaces/mms-meta/MMS) - Күптелле, ачык чыганаклы STT / TTS
  системасы.
* [TurkicTTS](https://github.com/IS2AI/TurkicTTS) - Ун төрки телне таэмин итүче тавыш синтезы системасы.
* [RHVoice](https://github.com/RHVoice/RHVoice) - Түләүсез, ачык чыганаклы, татар телен тәэмин итә торган тавыш
  синтезаторы.

## Тел корпуслары

* [search.corpus.tatar](https://search.corpus.tatar/index.php?of=search/search.php)
* [tugantel.tatar](https://tugantel.tatar/?lang=tt)
* [litcorpus.antat.ru](https://litcorpus.antat.ru/index_tt.html)

## Тел анализаторлары

* [Apertium's language analyzer](https://github.com/apertium/apertium-tat)
* Turkic Morpheme [portal](http://modmorph.turklang.net/tt/) һәм [API](http://modmorph.turklang.net/api/?language=16) -
  Гомумтөрки һәм фәкатъ Татар теле морфологик анализаторы.

## Ихтияри тәрҗемә проектлары

* [LibreOffice](https://translations.documentfoundation.org/languages/tt/) - Түләүсез һәм ачык
  чыганаклы [LibreOffice](https://www.libreoffice.org/) миллиләштерү.
* [Mozilla Firefox](https://pontoon.mozilla.org/tt/) - Түләүсез һәм ачык
  чыганаклы [Mozilla Firefox](https://www.mozilla.org/) миллиләштерү.
* [Minecraft](https://crowdin.com/project/minecraft/tt-RU) - Танылган Minecraft уенын миллиләштерү.
* [Mastodon](https://crowdin.com/project/mastodon/tt-RU) - Түләүсез һәм ачык
  чыганаклы [Mastodon](https://joinmastodon.org/) ([чыганак](https://github.com/mastodon)) социаль челтәрен
  миллиләштерү.
* [Warzone 2100](https://crowdin.com/project/warzone2100/tt-RU) - [Warzone 2100](https://wz2100.net/)([чыганак](https://github.com/Warzone2100/warzone2100))
  RTS-уенын миллиләштерү.
* [Steam](https://github.com/Amirhan-Taipovjan-Greatest-I/unofficial-tatar-steam-translations) - Рәсми булмаган Steam
  кушымтасын миллиләштерү.
* [Wikipedia](https://t.me/wugtat) - Wikipedia ихтияриларының берләшмәсе.

## Миллиләштерү әсбаплары

* [Tatar Style Guide](https://download.microsoft.com/download/4/8/2/4825b7b4-fda5-4f66-b475-0cc6a6b4e13f/tat-rus-styleguide.pdf) -
  Microsoft кулланган рәсми миллиләштерү әсбабы.
* [Microsoft terminology search](https://msit.powerbi.com/view?r=eyJrIjoiODJmYjU4Y2YtM2M0ZC00YzYxLWE1YTktNzFjYmYxNTAxNjQ0IiwidCI6IjcyZjk4OGJmLTg2ZjEtNDFhZi05MWFiLTJkN2NkMDExZGI0NyIsImMiOjV9) -
  Microsoft продуктларында кулланган рәсми тәрҗемә.

## Браузер плагиннары

* [tatarspeech](https://tatarspeech.dtc.tatar/)(beta) - реаль вакытта Youtube видеоларын татарчага тәрҗемә. 