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
|[Flowtron by Nvidia](https://nv-adlr.github.io/Flowtron)|A Tacotron-based speech synthsis tool which can be tweaked for pitch and prosody, setting it apart from other Tacotron-based TTS implementations|Apache2         |First released at the GTC 2020 Conference in May 2020           

## Chatbots and Conversational UI tools 

| Website | Tool name | License | Description |
|---------|-----------|---------|-------------|
|[Mindmeld by Cisco](https://github.com/cisco/mindmeld)|.|Apache2         | The MindMeld Conversational AI platform is among the most advanced AI platforms for building production-quality conversational applications. It is a Python-based machine learning framework which encompasses all of the algorithms and utilities required for this purpose. Evolved over several years of building and deploying dozens of the most advanced conversational experiences achievable, MindMeld is optimized for building advanced conversational assistants which demonstrate deep understanding of a particular use case or domain while providing highly useful and versatile conversational experiences. The academic reference for this tool is:

> Raghuvanshi, A., Carroll, L. and Raghunathan, K., 2018, November. Developing Production-Level Conversational Interfaces with Shallow Semantic Parsing. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing: System Demonstrations (pp. 157-162)
| 

## Voice assistant wrappers 



## Other tools 

* [Artie Bias Corpus](https://github.com/artie-inc/artie-bias-corpus/) - A corpus and set of tools for detecting _demographic bias_ in ASR systems.


## Glossary 

There are a lot of terms and acronyms in open source voice technology. This section provides explanations for each of them. 

* `LVCSR`: Large vocabulary continuous speech recognition. Used in speech recognition tools to denote that a) the vocabulary on which the recognizer works has not been restricted or constrained - for example if it is deployed on embedded or low-powered hardware which cannot handle the memory or compute requirements of a large vocabulary and b) the recognizer works _continuously_, in contrast to a Wake Word or Keyword spotter which cedes control to the STT once a Wake Word is detected. 

* `Cognitive arbitration`: The process a voice assistant uses to understand what services and skills are available to it, depending on its _context_ - such as being online or offline. 
