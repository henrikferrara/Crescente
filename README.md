# Crescente

Welcome to the repository of Crescente, a new DMI (Digital Music Instrument) with some qualities imported from the electroacoustic universe.
Crescente is still a prototype and right now it is on its second iteration stage (regarding body construction, design and sensors placement).

Disclaimer: As this entire project started in the context of my master's dissertation, which I undertook at Universidade do Porto, in Portugal, some of the files contained on this repository are titled and/or written in portuguese. This is due to this repository being part of my dissertation's Annexes section, which must stay publicly available. Anyhow, I'll be continuing to update this project using english only and all the essential information will be readily available here.

![Crescente1](/Crescente_Imagens/crescente1.jpg)

## Table of contents
  * [About](#about)
  * [Folders and Files](#folders-and-files)
  * [Requirements](#requirements)
  * [Building the Body](#building-the-body)
  * [Future Work](#future-work)
 
## About

The development of Crescente was heavily inspired by a list of things. Among those, there was a deep need to dive into the DIY world of new instruments, alongside an urge to find ways of making an electronic instrument enable expressivity, through gesture and physicality. Some existing NIMEs also inspired how this prototype came to be, such as ["De Shroom"][DESHROOM] by Fedde Ten Berge, ["Halldorophone"][HALLDOR] by Halldór Úlfarsson, ["The Daïs"][DAIS] by Pelle Christensen and ["Knurl"][KNURL] by Rafaele Andrade.

Crescente is a portable standalone instrument, as the entire sound production chain happens within Crescente (it does also have an output for simultaneous external amplification and/or processing, when needed). It is shaped in a moon like body, which is embraced by the musician and exposes its most visually striking sensors facing front.

For more information about Crescente, please visit Bela's [blog post][BLOG]!

### Sound examples: (will be uploading soon!)

Physical gestures employed by a musician, consciously or unconsciously, are comprised of features such as intentionality, effort, intimacy towards the instrument, virtuosity and other factors that crucially influence the perception of expressiveness. To conceive a digital musical instrument (DMI) which asks from the musician a “vocabulary” of gestures visible to the audience, in addition to a certain cause-effect relationship between physical gesture, musician, instrument and sound, one must realise which gestures could lead to the desired effect (e.g. produce a glissando sound) and which sensors best fit that scenario. This implies a continuous circular development process which features experimenting and thinking about the physical instrument, sensors, actuators, and sound synthesis.
This process ends at the time when the musician feels the instrument has the right balance between gesture and musicality, thus, implying a design process that is
particular to the musicians themselves. This is the case of Crescente. The decisions, evolutions and setbacks made during the research development phase were
mostly done considering the my desires, expectations and aims as a musician.


## Folders and Files

* On the folder **Crescente Circuit Designs** you'll find the schematics (PNG image + fzz. file) for Crescente (currently version is v3), which were designed using Fritzing;
* On the folder **Crescente Imagens** you'll find high quality pictures of Crescente's second (and current) iteration;
* On the folder **Crescente Updated Patch** you'll find the latest updated version of the Pd patch I'm using on Crescente;
* On the folder **Crescente Gestos** you'll find high quality pictures portraying some of the gesture vocabulary that can be utilized when playing Crescente;
* On the folder **Crescente_v1.0alpha** you'll find the first stable version of Crescente's Pd patch. This version was utilized for the first recordings of the prototype. (Note: Some parts of the code used were originally built by [Johan Eriksson][AUTO] and others by [Bela's team][BELARESOURCE]);
* On the folder **prototyping testing patches** you'll find a series of Pure Data patches that were utilized on several testing tasks during Crescente's development. These are here merely for Archival purposes;
* **link paraPerformance cCrescente 25 de Junho 2021** is an unlisted YouTube link for the [first video][FIRST] I recorded playing Crescente at a very early stage of the second iteration of the prototype;
* **link pasta registosAudiovisuais Prototipagem** is a link for a Google Drive folder which contains a series of pictures which document a lot of moments on Crescente's prototyping and building phase;


## Requirements

If you wish to build your own Crescente, there is a list of materials and tools you'll need before you start:
* [Bela Starter Kit][BELASTARTER] (You may also use a [Bela Mini][BELAMINI] but I haven't tested which changes to the project would be necessary);
* Computer running any browser which supports [Bela IDE][IDE] and [Pure Data][PD] installed (So you can edit or create your own Crescente patch);
* A [Trill Square][SQUARE] sensor and a [Trill Bar][BAR] sensor;
* 4 round FSR sensors;
* A round Piezo;
* A small surface transducer;
* A round push button;
* 2 potentiometers (500kΩ is fine but you can use other values);
* 5V Powerbank;
* USB to 5V DC Barrel Jack Power Cable;
* Breadboard;
* Jumper Wires (or similar);
* Single-conductor wire (at least two different colors);
* Soldering Iron;
* Solder;
* Wirecutter;
* Electrical tape;
* 10kΩ and 1MΩ resistors;

Besides these materials and tools, you'll also be needing a few others to build the body (case) of the instrument. These materials will depend on how you wish to build Crescente. As this project is still in development, there is no ideal build guide available, as other materials and forms are planned to be experimented. However, you may follow the next section if you wish to reproduce the body as it was achieved for Crescente's second iteration.

## Building the Body

**Soon**

## Future Work

**Soon**



[DESHROOM]: https://www.feddetenberge.nl/de-shroom
[HALLDOR]: http://www.halldorophone.info/about/
[DAIS]: https://blog.bela.io/dais-haptic-feedback-instrument/
[KNURL]: https://blog.bela.io/knurl-hybrid-cello/
[BLOG]: https://blog.bela.io/crescente-electroacoustic-instrument/
[AUTO]: https://www.automatonism.com/
[BELARESOURCE]: https://learn.bela.io/tutorials/pure-data/audio/virtual-string-synthesis/
[FIRST]: https://youtu.be/IwxxiV-YO88
[BELASTARTER]: https://shop.bela.io/products/bela-starter-kit?variant=31529851519058
[BELAMINI]: https://shop.bela.io/products/bela-mini-starter-kit?variant=30993041391698
[IDE]: https://learn.bela.io/the-ide/meet-the-ide/
[PD]: https://puredata.info/
[BAR]: https://shop.bela.io/collections/trill/products/trill-bar
[SQUARE]: https://shop.bela.io/collections/trill/products/trill-square
