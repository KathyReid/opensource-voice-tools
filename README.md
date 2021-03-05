# A listing of open source voice tools 

## Introduction 

Voice technology is taking off in a big way. For organisations, businesses and individuals trying to make sense of voice and where it sits in their technical architectures, it can be really confusing to understand the open source offerings that are out there. 

This repo is a listing of known open source voice tools, structured by where those tools sit in the voice stack. 

## Transcription 

* Duca, Daniela. “Disrupting Transcription – How Automation Is Transforming a Foundational Research Method.” Impact of Social Sciences (blog), September 17, 2019. https://blogs.lse.ac.uk/impactofsocialsciences/2019/09/17/disrupting-transcription-how-technology-is-transforming-a-foundational-research-method/.


## Wake words 

## Speech to text 

| Website | Tool name | License | Description |
|---------|-----------|---------|-------------|
|[openslr.org](https://openslr.org)|Open Speech Language Resources|N/A          |Run by @danpovey, who is also a key maintainer of the Kaldi-ASR speech to text tool             |Provides a place to host open speech datasets, corpora and so on.
| [kaldi-asr.org](https://kaldi-asr.org)        |Kaldi Automatic Speech Recognition toolkit.           |Apache 2         |One of the first open source speech recognition toolkits. Academic reference is: `Povey, D., Ghoshal, A., Boulianne, G., Burget, L., Glembek, O., Goel, N., ... & Silovsky, J. (2011). The Kaldi speech recognition toolkit. In IEEE 2011 workshop on automatic speech recognition and understanding (No. CONF). IEEE Signal Processing Society.`             |
|         |           |         |             |

## Intent parsing 

## Intent resolution 

## Text to speech 

| Website | Tool name | License | Description |
|---------|-----------|---------|-------------|
|[Flowtron by Nvidia](https://nv-adlr.github.io/Flowtron)|A Tacotron-based speech synthsis tool which can be tweaked for pitch and prosody, setting it apart from other Tacotron-based TTS implementations|Apache2         |First released at the GTC 2020 Conference in May 2020. [Academic paper is avaialble here](https://arxiv.org/pdf/2005.05957.pdf). Citation is `Valle, R., Shih, K., Prenger, R., & Catanzaro, B. (2020). Flowtron: an Autoregressive Flow-based Generative Network for Text-to-Speech Synthesis. arXiv preprint arXiv:2005.05957.`     

* Mwiti, Derrick. “A 2019 Guide to Speech Synthesis with Deep Learning.” Medium, June 23, 2020. https://heartbeat.fritz.ai/a-2019-guide-to-speech-synthesis-with-deep-learning-630afcafb9dd.

^ This is a great article that explains the differences in the _evolutions_ or _generations_ of text to speech - from _concatenative_ to _statistical parametric_ to _generative_. More modern TTS approaches like Tacotron and WaveNet are _generative_ approaches. 


## Chatbots and Conversational UI tools 

| Website | Tool name | License | Description |
|---------|-----------|---------|-------------|
|[Mindmeld by Cisco](https://github.com/cisco/mindmeld)|.|Apache2         | The MindMeld Conversational AI platform is among the most advanced AI platforms for building production-quality conversational applications. It is a Python-based machine learning framework which encompasses all of the algorithms and utilities required for this purpose. Evolved over several years of building and deploying dozens of the most advanced conversational experiences achievable, MindMeld is optimized for building advanced conversational assistants which demonstrate deep understanding of a particular use case or domain while providing highly useful and versatile conversational experiences. The academic reference for this tool is:

> Raghuvanshi, A., Carroll, L. and Raghunathan, K., 2018, November. Developing Production-Level Conversational Interfaces with Shallow Semantic Parsing. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing: System Demonstrations (pp. 157-162)
| 

## Voice assistant wrappers 

* [Mycroft.AI](https://mycroft.ai) - an open source, layered voice assistant that works on a range of Linux-compatible hardware, such as x86 or ARM devices such as Raspberry Pi. Supported by a strong community of open source developers. 

* [OVAL / Genie project at Stanford](https://oval.cs.stanford.edu/) - Funded by the [Alfred P Sloan Foundation](https://sloan.org/) and by a NIST grant, Stanford's OVAL project aims to provide an open source alternative to commercial voice assistants. The project is currently in its infancy and is attempting to build an open source community. 

## Natural language processing (NLP)

* [Python Natural Language Toolkit NLTK](http://www.nltk.org/) - NLTK is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an [active discussion forum](https://groups.google.com/g/nltk-users?pli=1).

* [ECCO explainab](https://www.eccox.io/) - ECCO is a Python library that provides explainability for NLP using interactive visualisations. 

* [Detext](https://engineering.linkedin.com/blog/2020/open-sourcing-detext) [source code](https://github.com/linkedin/detext) DeText is a Deep Text understanding framework for NLP related ranking, classification, and language generation tasks. It leverages semantic matching using deep neural networks to understand member intents in search and recommender systems. As a general NLP framework, currently DeText can be applied to many tasks, including search & recommendation ranking, multi-class classification and query understanding tasks. Published by the AI team at LinkedIn.  

* [pglex](https://github.com/rsprouse/pglex) - First presented at the [ICLDC 7 conference](http://ling.lll.hawaii.edu/sites/icldc/) in 2021, pglex is a 'pretty good' lexical service designed to facilitate the construction of dictionary websites and other applications that incorporate lexical data. With pglex, researchers can provide lexical entries in JSON format to an instance of the pglex API and get 'pretty good' search results without requiring language-specific configurations. Built on ElasticSearch.

## Bias in voice assistants and NLP

* [Artie Bias Corpus](https://github.com/artie-inc/artie-bias-corpus/) - A corpus and set of tools for detecting _demographic bias_ in ASR systems.

* [Blodgett, S. L., Barocas, S., Daumé III, H., & Wallach, H. (2020). Language (Technology) is Power: A Critical Survey of" Bias" in NLP. arXiv preprint arXiv:2005.14050.] https://arxiv.org/pdf/2005.14050.pdf

## Speaker recognition 

* [ALIZE Open source toolkit for speaker recognition](https://github.com/ALIZE-Speaker-Recognition) - A cross-platform, open source speaker recognition toolkit from [Laboratoire Informatique d’Avignon, France](https://alize.univ-avignon.fr/). 

## Forced aligners 

_Forced aligners help to align audio recordings with orthographic transcription_ 

* [aeneas](https://github.com/readbeyond/aeneas) | [Docs](www.readbeyond.it/aeneas/) is a Python/C library and a set of tools to automagically synchronize audio and text (aka forced alignment). 

## Voice and language corpora 

* [Berlin Database of Emotional Speech](http://emodb.bilderbar.info/download/) - A tagged corpus (in German/Deutsche) of speech tagged with emotions. 
* [The Pile](https://pile.eleuther.ai) - The Pile is a 825 GiB diverse, open source language modelling data set that consists of 22 smaller, high-quality datasets combined together. 


## Glossary 

There are a lot of terms and acronyms in open source voice technology. This section provides explanations for each of them. 

* `Cognitive arbitration`: The process a voice assistant uses to understand what services and skills are available to it, depending on its _context_ - such as being online or offline. 

* `CRF`: [Conditional random field](https://en.wikipedia.org/wiki/Conditional_random_field). A statistical modelling method which can take into account context. Used in some neural-network based intent-parsing and semantic extraction software. 

* `LSTM`: [long short-term memory](https://en.wikipedia.org/wiki/Long_short-term_memory). Used within recurrent neural networks to help process _sequences_ of data, such as audio or speech. In order to know what is likely to come _next_, LSTM records what came _previously_. 

* `LVCSR`: Large vocabulary continuous speech recognition. Used in speech recognition tools to denote that a) the vocabulary on which the recognizer works has not been restricted or constrained - for example if it is deployed on embedded or low-powered hardware which cannot handle the memory or compute requirements of a large vocabulary and b) the recognizer works _continuously_, in contrast to a Wake Word or Keyword spotter which cedes control to the STT once a Wake Word is detected. 


