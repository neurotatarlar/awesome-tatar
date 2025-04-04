<div align="left">
	<img width="540" height="540" src="media/logo.jpg" alt="Awesome Tatar">
</div>

# Awesome Tatar

[![en](https://img.shields.io/badge/lang-tt--cy-darkgreen.svg)](README.tt-cy.md)

# About

A curated list of awesome libraries, resources, services and datasets for Tatar language.

**Table of Contents**

- [LLMs](#llms)
- [Parallel corpora](#parallel-corpora)
- [Monocorpora](#monocorpora)
- [Audio datasets](#audio-datasets)
- [Other datasets](#other-datasets)
- [Cyrill-latin convertors](#cyrill-latin-convertors)
- [Text-to-speech & speech-to-text](#text-to-speech--speech-to-text)
- [Language corpus](#language-corpus)
- [Language analyzers](#language-analyzers)
- [Volunteer localization projects](#volunteer-localization-projects)
- [Localization guides](#localization-guides)
- [Browser's plugins](#browsers-plugins)

## LLMs

* [tweety-tatar-base](https://huggingface.co/Tweeties/tweety-tatar-base-7b-2024-v1) - LLM for the Tatar language,
  converted from the Mistral-7B-Instruct-v0.2 model trained by MistralAI
* [mGPT-1.3B-tatar](https://huggingface.co/ai-forever/mGPT-1.3B-tatar) - The model derived from the base mGPT-XL (1.3B) model which was originally trained on the 61 languages from 25 language families using Wikipedia and C4 corpus by SberAI.



## Parallel corpora

* [IPSAN's parallel corpus dataset](https://huggingface.co/datasets/IPSAN/tatar_translation_dataset) - Dataset
  collected
  by [Institute of Applied Semiotics](https://www.antat.ru/en/).
* [Aygiz Kunafin's dataset](https://huggingface.co/datasets/AigizK/tatar-russian-parallel-corpora) - Dataset collected
  by language enthusiast Aygiz Kunafin.
* The Open Parallel
  Corpus ([tt-en](https://opus.nlpl.eu/results/tt&en/corpus-result-table), [tt-ru](https://opus.nlpl.eu/results/tt&ru/corpus-result-table)) -
  miscellaneous parallel corpora (⚠ it requires data cleaning and preparation).
* [Apertium's language pair](https://github.com/apertium/apertium-tat-rus) -
  an [Apertium](https://www.apertium.org/index.rus.html) language pair for translating from Tatar to Russian (in incubator), [Kazakh - Tatar pair](https://www.apertium.org/index.eng.html#?dir=tat-kaz&q=) (production).

## Monocorpora

* [uonlp/CulturaX](https://huggingface.co/datasets/uonlp/CulturaX) - Multilanguage dataset
  of [The University of Oregon ](http://nlp.uoregon.edu/).
* [Neurotatarlar's dataset](https://huggingface.co/neurotatarlar) - Our dataset includes processed books and documents
  crawled from the internet.
* [Azatliq's crawled document](https://huggingface.co/datasets/veryrealtatarperson/tt-azatliq-crawl) - Dataset of
  documents crawled from the [Azatliq](https://www.azatliq.org/) website.

## Audio datasets

* [Mozilla common voice](https://commonvoice.mozilla.org/tt/datasets) - ASR dataset powered by volunteer
  contributors.
* [TatSC](https://github.com/IS2AI/Soyle?tab=readme-ov-file#available-languages) - [ISSAI's](https://issai.nu.edu.kz/issai-datasets/) ASR dataset
* [TatarTTS](https://huggingface.co/datasets/issai/TatarTTS) - [ISSAI's](https://issai.nu.edu.kz/issai-datasets/) TTS dataset
* [TatarSCR](https://huggingface.co/datasets/issai/TatarTTS) - [ISSAI's](https://issai.nu.edu.kz/issai-datasets/) Speech Commands Dataset dataset

## Text datasets

* [SART](https://github.com/tat-nlp/SART) - datasets of Similarity, Analogies, and Relatedness for Tatar language.
* [TUMLU](https://github.com/ceferisbarov/TUMLU) - A Unified and Native Language Understanding Benchmark for Turkic Languages.
* [TextDetox](https://huggingface.co/datasets/textdetox/multilingual_toxicity_dataset) - Multilingual Toxicity Detection Dataset.
* [BRIGHTER](https://huggingface.co/datasets/brighter-dataset/BRIGHTER-emotion-categories) - BRIGHTER: BRIdging the Gap in Human-Annotated Textual Emotion Recognition Datasets for 28 Languages.

## Cyrill-latin convertors

* [baltoslav.eu](https://baltoslav.eu/lat/index.php)
* [speak.tatar](https://speak.tatar/en/lang/converter/tat/latin/cyrillic/)
* [yusuke1997.com](https://yusuke1997.com/tatar) - ([source1](https://github.com/yusuke1997/tatar_transliteration) and [source2](https://github.com/yusuke1997/translit_tt))
* [COPIUS](https://www.copius.eu/trtr.php?lang=tat)

## Text-to-speech & speech-to-text models

* [MMS-1b-tatar](https://huggingface.co/AigizK/wav2vec2-large-mms-1b-tatar) - Fine-tuned ASR for tatar language.
* [speech.tatar](https://speech.tatar/) - Read aloud service powered
  by [Institute of Applied Semiotics](https://www.antat.ru/en/).
* [Tatsoft ASR](https://tat-asr.api.translate.tatar/docs) - API for automatic speech recognition system for Tatar
  language provided by Tatsoft.
* [Tatsoft TTS](https://tat-tts.api.translate.tatar/docs) - API for text-to-speech synthesis system for Tatar language
  provided by Tatsoft.
* [TatarSCR](https://github.com/IS2AI/TatarSCR) - An open-source Tatar Speech Commands Dataset
* [Silero Models](https://github.com/snakers4/silero-models?tab=readme-ov-file#cyrillic-languages) - Pre-trained STT /
  TTS models with tatar language support. Minimal working example can be
  found [here](https://colab.research.google.com/drive/1hsn_Liy19eu17mb9qEQhM2GMEBxzcAP-#scrollTo=7b9e704a).
* [Massively Multilingual Speech](https://huggingface.co/spaces/mms-meta/MMS) - Open-source STT / TTS initiative for
  thousands of languages.
* [TurkicTTS](https://github.com/IS2AI/TurkicTTS) - A multilingual text-to-speech synthesis system for 10 turkic
  languages.
* [RHVoice](https://github.com/RHVoice/RHVoice) - A free and open source speech synthesizer with tatar language support.

## Language corpus

* [search.corpus.tatar](https://search.corpus.tatar/index.php?of=search/search.php)
* [tugantel.tatar](https://tugantel.tatar/?lang=tt)
* [litcorpus.antat.ru](https://litcorpus.antat.ru/index_tt.html)

## Language analyzers

* [Apertium's language analyzer](https://github.com/apertium/apertium-tat)
* Turkic Morpheme [portal](http://modmorph.turklang.net/tt/) and [API](http://modmorph.turklang.net/api/?language=16) -
  Morphological analyzer for Turkic languages, including Tatar.

## Volunteer localization projects

* [LibreOffice](https://translations.documentfoundation.org/languages/tt/) - Localization of free and
  open-source [LibreOffice](https://www.libreoffice.org/).
* [Mozilla Firefox](https://pontoon.mozilla.org/tt/) - Localization of free and
  open-source [Mozilla projects](https://www.mozilla.org/).
* [Minecraft](https://crowdin.com/project/minecraft/tt-RU) - Localization of legendary Minecraft.
* [Mastodon](https://crowdin.com/project/mastodon/tt-RU) - Localization of free and open-source social
  network [Mastodon](https://joinmastodon.org/) ([source](https://github.com/mastodon)).
* [Warzone 2100](https://crowdin.com/project/warzone2100/tt-RU) - Localization of real-time strategy
  game [Warzone 2100](https://wz2100.net/)([source](https://github.com/Warzone2100/warzone2100)).
* [Steam](https://github.com/Amirhan-Taipovjan-Greatest-I/unofficial-tatar-steam-translations) - Unofficial localization
  of Steam.
* [Wikipedia](https://t.me/wugtat) - Community of Wikipedia volunteers.
* [Ubuntu](https://launchpad.net/~ubuntu-l10n-tt) - Localization of Ubuntu OS to Tatar language.
* [LineageOS AOSP](https://crowdin.com/project/lineageos-aosp/tt-RU) - Localization of the biggest Android open source fork. 

## Localization guides

* [Tatar Style Guide](https://download.microsoft.com/download/4/8/2/4825b7b4-fda5-4f66-b475-0cc6a6b4e13f/tat-rus-styleguide.pdf) -
  Official localization style gide used by Microsoft.
* [Microsoft terminology search](https://msit.powerbi.com/view?r=eyJrIjoiODJmYjU4Y2YtM2M0ZC00YzYxLWE1YTktNzFjYmYxNTAxNjQ0IiwidCI6IjcyZjk4OGJmLTg2ZjEtNDFhZi05MWFiLTJkN2NkMDExZGI0NyIsImMiOjV9) -
  Official translations used in Microsoft's products.

## Browser's plugins

* [tatarspeech](https://tatarspeech.dtc.tatar/)(beta) - real-time YouTube video translation to Tatar.
