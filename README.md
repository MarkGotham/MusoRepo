# 'MusoRepo': a Directory of Resources for Computational Musicology

This is a list of links to resources for computational musicology, with a focus on working with symbolic scores.
All of the resources are free and open source/access, except where specified ('[not free]').

There are other, excellent lists out there compiled and hosted by institutions like:
* [CCARH's Digital Resources for Musicology](http://wiki.ccarh.org/wiki/Digital_Resources_for_Musicology)
* [ISMIR's Resources list](http://www.ismir.net/resources.html) – research centers, datasets and more, mostly for audio analysis.
* [SMT Music Informatics Group](https://sites.google.com/site/smtmig/)

... and individuals like:
* [Alexander Lerch](http://www.audiocontentanalysis.org/data-sets/),
* [ciconia](https://github.com/ciconia/awesome-music),
* [Colin Raffel](http://colinraffel.com/wiki/mir_datasets),
* [dharasim](https://github.com/dharasim/MCR/wiki),
* [Georg Holzmann](http://grh.mur.at/sites/default/files/mir_datasets_0.html)

I have / will contribute this content to those lists where appropriate, but I think that this list is sufficiently distinct to warrant a separate existence, particularly in light of the focus on working with scores.
Please do reach out if you would like to contribute an item to this list, or if you have a suggestion for how to organize it better, or perhaps even a grand idea for us list makers should coordinate our efforts.

## Scores and Datasets

### Analysis datasets (e.g. harmony, form)

* [Annotated Beethoven Corpus](https://github.com/DCMLab/ABC) - Harmonic Analysis of the Beethoven String Quartets
* [GTTM](http://gttm.jp/gttm/) - Masatoshi Hamanaka's XML markups of musical examples from (and using the tree structure representation of) A Generative Theory of Tonal Music  (Lerdahl and Jackendoff 1983)
* [Machine-readable Schenkerian analyses](http://www.cs.rhodes.edu/~kirlinp/diss.html)

### Datasets related to scores (e.g. of chord progressions)

* [‘Annotated jazz chord progression corpus’](http://jazzparser.granroth-wilding.co.uk/ParserPaper.html) - Mark Granroth-Wilding and Mark Steedman
* [Corpus of rock chord progression](http://rockcorpus.midside.com) - deClercq and Temperley 2011
* [EWLD (Enhanced Wikifonia Leadsheet Dataset)](https://zenodo.org/record/1476555#.XGXW4eJKjMI) - more than 5,000 leadsheets and rich metadata based on the crowd-source 'Wikifonia' corpus (see below).
* [iRb Jazz Corpus](https://csml.som.ohio-state.edu/home/index.php/iRb_Jazz_Corpus) - OSU
* [Jazzomat Research Project’s ‘Weimar Jazz Database’](http://jazzomat.hfm-weimar.de/dbformat/dbcontent.html)
* [Jazz Audio-Aligned Harmony (JAAH) Dataset](https://zenodo.org/record/1290737#.W6vIKxNKixM) - 113 tracks selected from Smithsonian jazz collections. See also [MTG's Open Source Technologies](https://mtg.github.io/JAAH/)
* [Lakh MIDI Dataset](http://colinraffel.com/projects/lmd/) - MIDI
* [MusicNet](http://homes.cs.washington.edu/~thickstn/musicnet.html) - A curated collection of labeled classical music [recordings].
* ‘Wikifonia’ - corpus of lead sheets (vocal lines and harmonies). NB: no longer hosted online. (See also 'EWLD' above).
* [YCAC Dataset](https://ycac.yale.edu/) - .csv datasets of pitch 'slices' from a MIDI corpus.

### Encoded Musical Scores

* [ELVIS](https://database.elvisproject.ca/) - metacorpus, various formats.
* [JRP](http://josquin.stanford.edu/) - krn format. Works by Josquin and contemporaries.
* [Kern Scores](http://kern.ccarh.org/) - krn format.
* [Kunst der Fuge (MIDI)](http://www.kunstderfuge.com/) - MIDI.
* [LvH - French](https://github.com/leighvh1/19th-century-art-songs-by-French-composers) - Vocal lines from songs by French composers in krn format.
* [LvH - German](https://github.com/leighvh1/19th-century-art-songs-by-German-composers) - Vocal lines from songs by German composers in krn format.
* [MuseData](http://www.musedata.org/) - krn format, mostly Baroque and Classical music.
* [music21 Corpus](http://web.mit.edu/music21/doc/about/referenceCorpus.html) - metacorpus.
* [Nottingham dataset, cleaned version](https://github.com/jukedeck/nottingham-dataset)
* [Neuma](http://neuma.huma-num.fr/) - metacorpus, various formats.
* [OpenScore](https://openscore.cc/) - mscx format.
* [ScoresOfScores](https://github.com/MarkGotham/ScoresOfScores) - xml and mscx formats. 300 Lieder.

### Metadata

* [Discogs](http://www.discogs.com/)
* [Musicbrainz](http://musicbrainz.org/)
* [Music Ontology data](http://musicontology.com/)

## Software and Code Libraries

### Analysis / Annotation / Edition / Visualisation

* [Audio Timeliner](http://www.singanewsong.org/audiotimeliner/) [not free]
* [Dezrann](http://www.dezrann.net/)
* [Digitale Musikedition](www.edirom.de) - based on Frans Wiering’s idea of a “multidimensional model” of a musical edition
* [“Freischütz Digital”](www.freischuetz-digital.de)
* [jfugue](http://www.jfugue.org/) - Music programming for Java and JVM languages
* [mdecks](https://mdecks.com/mapharmony.phtml) [not free]
* [OCVE](www.chopinonline.ac.uk/ocve/) - Collection and comparison of primary source Chopin scores
* [“OPERA”](www.opera.adwmainz.de/informationen.html)
* [Peachnote](https://www.peachnote.de/)
* [Tido](https://www.tido-music.com/)
* [Music Connection Machine](http://www.musicconnectionmachine.org/)
* [Tuttitempi](https://tuttitempi.com/) - Score-aligned visualisation of the tempi used in multiple recordings from Peachnote.
* [XronoMorph](https://www.dynamictonality.com/xronomorph.htm) - app for creating rhythmic and melodic loops

### Automatic composition (with A.I.)

* [Band-in-a-Box](http://www.bandinabox.com/)
* [Google Magenta Project](http://magenta.tensorflow.org/)
* [Jukedeck](https://www.jukedeck.com/)
* [Sony CSL-Paris: Flow Machine](http://www.flow-machines.com/)
* [WHIM](http://www.whim-project.eu/)

### Digital music-making

* [OpenMusic](http://repmus.ircam.fr/openmusic/home) - Computer-assisted composition.
* [Max/MSP](https://cycling74.com/products/max/) – Real-time audio manipulation [not free]
* [Sonic Pi](http://sonic-pi.net/), [Overtone](http://overtone.github.io/), [SuperCollider](http://supercollider.github.io/) - Live-coding

### Notation softwares and score rendering

* [Abjad](http://abjad.mbrsi.org/#)
* [Dorico](https://www.steinberg.net/en/products/dorico.html) [not free]
* [Finale](https://www.finalemusic.com/) [not free]
* [Lilypond](http://lilypond.org/)
* [MuseScore](https://musescore.org/en/download/musescore.dmg)
* [Sibelius](https://www.avid.com/sibelius) [not free]
* [VexFlow](http://www.vexflow.com)
* [Verovio](http://www.verovio.org)

### Optical Music Recognition (OMR)

* [musitek](http://www.musitek.com/) [not free]
* [sharpeye](http://www.musicaleditor.com/scan-music.html) [not free]
* [SmartScore](https://www.musitek.com/smartscore-pro.html) [not free]
* [Audiveris](https://github.com/Audiveris/audiveris/wiki)

### Score Analysis - Open Source Softwares and Code Libraries

* [Humdrum](http://www.humdrum.org/)
* [music21 (python)](http://web.mit.edu/music21/)
* [music21 (js)](http://web.mit.edu/music21/music21j/doc/index.html)

### Online music notation softwares / score editions (all commercial)

* [Flat](https://flat.io/) [not free]
* [forScore](https://forscore.co/) [not free]
* [irealpro](https://irealpro.com/) - a smartphone application for real time accompaniment also supporting chord charts [not free]
* [neoScores](https://www.gogustaf.com/) [not free]
* [Newzik](https://newzik.com/) [not free]
* [Nkoda](https://www.nkoda.com/) [not free]
* [Noteflight](https://www.noteflight.com/) [not free]

### Standards

* [IEEE 1599](http://ieee1599.lim.di.unimi.it/) - the multi-layer XML-based format for music
* [MEI (Music Encoding Initiative)](http://music-encoding.org/) - an open-source effort to define a system for encoding musical documents in a machine-readable structure.
* [MusicXML](http://www.musicxml.com/) - the standard open format for exchanging digital sheet music.
* MNX File format (forthcoming) - [draft specifications](https://w3c.github.io/mnx/specification/)
* [SMuFL (Standard Music Font Layout)](http://www.smufl.org/) - a specification for mapping music symbols to Unicode for use in music fonts.

## Groups and Institutions

* [SMT Music Informatics Group](https://sites.google.com/site/smtmig/)

### Archival / Catalogues

* [Digital Image Archive of Medieval Music](http://www.diamm.ac.uk/)
* [Europeana](https://www.europeana.eu/portal/en)
* [HathiTrust Research Center](https://www.hathitrust.org/)
* [International Association of Music Libraries, Archives and Documentation Centres (IAML)](http://www.iaml.info/)
* [RISM](http://www.rism.info/home/)

### Journals and Conference Proceedings

* [Computer Music Journal](https://www.mitpressjournals.org/loi/comj)
* [Conference on Mathematics and Computation in Music (MCM)](http://www.smcm-net.info/) - From the Society for Mathematics and Computation in Music (SMCM)
* [Digital Libraries for Musicology (DLfM)](http://www.transforming-musicology.org/dlfm2017/) – an IMSIR satellite event
* [Empirical Musicology Review (EMR)](http://emusicology.org/)
* [Frontiers In Digital Humanities](http://journal.frontiersin.org/journal/digital-humanities)
* [International Computer Music Association](http://www.computermusic.org/)
* [International Conference on Auditory Displays](https://icad.org/)
* [International Conference on Live Coding](https://iclc.livecodenetwork.org/)
* [International Society for Music Information Retrieval (ISMIR)](http://www.ismir.net/)
* [International Workshop on Musical Metacreation](http://musicalmetacreation.org/)
* [HathiTrust Research Center 'Uncamp'](https://www.hathitrust.org/htrc_uncamp2018)
* [Journal of Mathematics and Music (JMAM)](https://www.tandfonline.com/toc/tmam20/current)
* [Journal of New Music Research](http://www.tandfonline.com/toc/nnmr20/current)
* [Music & Science Journal](http://journals.sagepub.com/loi/mnsa)
* [Music Encoding Conference](http://music-encoding.org/conference/) - annual gathering of the Music Encoding Initiative community.
* [New Interfaces for Musical Expression](http://www.nime.org/)
* ['TENOR'](http://www.tenor-conference.org/index.html) - International Conference on Technologies for Music Notation and Representation
* [TISMIR: Transactions of the International Society for Music Information Retrieval](http://tismir.ismir.net)

### Hackathons and Other Events

* [Classical Music Hackday](http://www.classicalmusichackday.org/#rec14632470)
* [MusicMesse, Frankfurt am Main](https://musik.messefrankfurt.com/frankfurt/en.html)

### Research Groups

* [Algomus](http://www.algomus.fr/) - 'Algorithmic Musicology' group, Lille, FR
* [Centre for Digital Music (‘C4DM’), Queen Mary, University of London, UK](http://c4dm.eecs.qmul.ac.uk/) - Mark Sandler and Simon Dixon
* [Center for Computer Assisted Research in the Humanities at Stanford University](http://www.ccarh.org) - Craig Sapp and Eleanor Selfridge-Field
* [Cognitive and Systematic Musicology Laboratory (CSML) at Ohio State University, US](https://www.asc.ohio-state.edu/music/csml/home/index.php/Home) - David Huron
* [Digital and Cognitive Musicology Lab (DCML) at EPFL, CH](https://github.com/DCMLab) - Martin Rohrmeier
* [IRCAM: Iremus](http://www.iremus.cnrs.fr/)
* [Distributed Digital Music Archives & Libraries Lab, McGill, CA](http://ddmal.music.mcgill.ca/) - Ichiro Fujinaga
* [Institute for Music Informatics and Musicology, University of Music Karlsruhe](http://hfm.eu/imwi/)
* [Intelligent Music Processing and Machine Learning Group, Linz, AT](http://www.ofai.at/music/) - Gerhard Widmer
* [Multimedia Computing Group, TU Delft, NL](https://www.tudelft.nl/ewi/over-de-faculteit/afdelingen/intelligent-systems/multimedia-computing/) - including Cynthia Liem and Julián Urbano working on music.
* [Music and Audio Research Lab (MARL), New York University, US](https://steinhardt.nyu.edu/marl/) - Juan Pablo Bello
* [Music Informatics Research Group, City University London, UK](http://mirg.city.ac.uk/) - Tillman Weyde
* [Music Informatics Group, Georgia Tech Center for Music Technology](http://www.musicinformatics.gatech.edu/about/related-classes/) - Alexander Lerch
* [Music Technology Group, Universitat Pompeu Fabra, Barcelona, ESP](https://www.upf.edu/web/mtg) - Xavier Serra
* [Universität für Musik und Darstellende Kunst Wien (University of Music and Performing Arts Vienna), AT](https://www.mdw.ac.at/) - Werner Goebl
* [Volk Group at Utrecht University, Utrecht, NL](https://www.uu.nl/staff/AVolk) - Anja Volk
