# 'MusoRepo': a Directory of Resources for Computational Musicology

This is a list of links to resources for computational musicology, with a focus on working with symbolic scores.
All of the resources are free and open source/access, except where specified.

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

* [Annotated Beethoven Corpus](https://github.com/DCMLab/ABC) - Harmonic analysis of the Beethoven String Quartets.
* [Beethoven Piano Sonata with Functional Harmony dataset (BPS-FH)](https://github.com/Tsung-Ping/functional-harmony) - harmonic and formal analyses of the first movements of Beethoven Piano Sonatas.
* [GTTM](http://gttm.jp/gttm/) - Masatoshi Hamanaka's XML markups of musical examples from (and using the tree structure representation of) A Generative Theory of Tonal Music (Lerdahl and Jackendoff 1983).
* [Machine-readable Schenkerian analyses](http://www.cs.rhodes.edu/~kirlinp/diss.html).
* ['Taking-Form'](https://github.com/MarkGotham/Taking-Form) - formal analysis of c.150 Mozart and Beethoven movements along with conversion code.
* [TAVERN](http://u.osu.edu/tavern/) - Theme And Variation Encodings with Roman Numerals. 27 sets of variations by Mozart and Beethoven.
* ['When in Rome'](https://github.com/MarkGotham/When-in-Rome) - a collection of harmonic analysis datasets in the 'Roman Text' format combining new corpora with conversions of all existing ones (ABC, BPS-FH, and TAVERN as above).

### Datasets related to scores (e.g. of chord progressions)

* [‘Annotated jazz chord progression corpus’](http://jazzparser.granroth-wilding.co.uk/ParserPaper.html) - Mark Granroth-Wilding and Mark Steedman
* [DDMAL's Billboard Project](http://ddmal.music.mcgill.ca/research/billboard) - chords, structure, instrumentation, and timing annotations of Billboard chart hits.
* [EWLD (Enhanced Wikifonia Leadsheet Dataset)](https://zenodo.org/record/1476555#.XGXW4eJKjMI) - more than 5,000 leadsheets and rich metadata based on the crowd-source 'Wikifonia' corpus (see below).
* [iRb Jazz Corpus](https://csml.som.ohio-state.edu/home/index.php/iRb_Jazz_Corpus) - OSU
* [Isophonics](http://www.isophonics.net/datasets) - data (and software) from the [Centre for Digital Music (‘C4DM’)](http://c4dm.eecs.qmul.ac.uk/) across a range of repertoires and parameters (structure, key, chord, beats).
* [Jazzomat Research Project’s ‘Weimar Jazz Database’](http://jazzomat.hfm-weimar.de/dbformat/dbcontent.html)
* [Jazz Audio-Aligned Harmony (JAAH) Dataset](https://zenodo.org/record/1290737#.W6vIKxNKixM) - 113 tracks selected from Smithsonian jazz collections. See also [MTG's Open Source Technologies](https://mtg.github.io/JAAH/)
* [Pop/rock chord progressions](http://rockcorpus.midside.com) - deClercq and Temperley 2011
* [RWC Music Database](https://staff.aist.go.jp/m.goto/RWC-MDB/) - various repertoires, permission required
* [Temperley / Kostka-Payne chords](http://davidtemperley.com/kp-stats/) - by Temperley, after the textbook by Kostka and Payne. Direct download [here](http://davidtemperley.com/wp-content/uploads/2016/09/kp-corpus-files.zip)
* ‘Wikifonia’ - corpus of lead sheets (vocal lines and harmonies). NB: no longer hosted online. (See also 'EWLD' above).
* [YCAC Dataset](https://ycac.yale.edu/) - .csv datasets of pitch 'slices' from the [Classical Archives](https://www.classicalarchives.com/) MIDI corpus

### Encoded scores

* [Choral Public Domain Library (CPDL)](http://www.cpdl.org/) - vocal music in a range of formats
* [ELVIS](https://database.elvisproject.ca/) - metacorpus, various formats.
* [JRP](http://josquin.stanford.edu/) - krn format. Works by Josquin and contemporaries.
* [Kern Scores](http://kern.ccarh.org/) - krn format.
* [LvH - French](https://github.com/leighvh1/19th-century-art-songs-by-French-composers) - Vocal lines from songs by French composers in krn format.
* [LvH - German](https://github.com/leighvh1/19th-century-art-songs-by-German-composers) - Vocal lines from songs by German composers in krn format.
* [MuseData](http://www.musedata.org/) - MuseData format, mostly Baroque and Classical music.
* [music21 Corpus](http://web.mit.edu/music21/doc/about/referenceCorpus.html) - metacorpus.
* [Mutopia](https://www.mutopiaproject.org)
* [Nottingham dataset, cleaned version](https://github.com/jukedeck/nottingham-dataset)
* [Neuma](http://neuma.huma-num.fr/) - metacorpus, various formats.
* [OpenScore](https://openscore.cc/) - mscx format.
* [ScoresOfScores](https://github.com/MarkGotham/ScoresOfScores) - xml and mscx formats. 300 Lieder.

### Metadata

* [Discogs](http://www.discogs.com/)
* [Musicbrainz](http://musicbrainz.org/)
* [MusicNet](http://homes.cs.washington.edu/~thickstn/musicnet.html) - A curated collection of labeled classical music [recordings].
* [Music Ontology data](http://musicontology.com/)
* [setlist.fm](https://www.setlist.fm) - crowd-sourced concert setlists

### MIDI

* [Band-in-a-Box Jazz standards](http://bhs.minor9.com/)
* [BitMidi](https://bitmidi.com/)
* [Classical Archives](https://www.classicalarchives.com/) - crowd-sourced, restrictions on download-at-scale
* [Kunst der Fuge](http://www.kunstderfuge.com/) - crowd-sourced, restrictions on download-at-scale
* [Lakh MIDI Dataset](http://colinraffel.com/projects/lmd/)
* [MAESTRO (MIDI and Audio Edited for Synchronous TRacks and Organization)](https://magenta.tensorflow.org/datasets/maestro) - piano performances with fine alignment between note labels and audio waveforms.

### Scores as images (not encoded)

* [Digital Image Archive of Medieval Music (DIAMM)](http://www.diamm.ac.uk/)
* [Diva.js](https://ddmal.github.io/diva.js/)
* [Europeana](https://www.europeana.eu/portal/en) - includes music
* [Gesualdo Online](https://ricercar.gesualdo-online.cesr.univ-tours.fr/) - MEI sources also available
* [HathiTrust Research Center](https://www.hathitrust.org/) - includes music
* [International Music Score Library Project (IMSLP)](http://imslp.org) - some encodings, primarily PDF
* [Measuring Polyphony](http://measuringpolyphony.org/) - polyphonic, late-medieval music

## Apps / Software / Code Libraries for ...

### Analysis / Parsing / Manipulation of Scores

* [Humdrum](http://www.humdrum.org/)
* [jfugue](http://www.jfugue.org/) - writing programs that create music. Java and JVM languages
* [Midifile](http://midifile.sapp.org/) - library for parsing Standard MIDI Files from [Craig Sapp](https://ccrma.stanford.edu/~craig/)
* [music21 (p)](http://web.mit.edu/music21/) - python
* [music21 (j)](http://web.mit.edu/music21/music21j/doc/index.html) - javascript
* ['Spectral Orchestrator' (SPORCH)](https://sourceforge.net/projects/sporch/) - harmonies/orchestrations from digitally recorded sound files.
* [Timidity](http://timidity.sourceforge.net/) - command line synthesizer that plays MIDI files from [Tuukka Toivonen](https://tuukkatoivonen.org).

### Digital music-making

* [OpenMusic](http://repmus.ircam.fr/openmusic/home) - Computer-assisted composition.
* [Chuck](http://chuck.stanford.edu) - strongly-timed, concurrent, and on-the-fly music programming language.
* [Common Music / GRACE](https://sourceforge.net/projects/commonmusic/) - Live-coding
* [Max/MSP](https://cycling74.com/products/max/) – Real-time audio manipulation [not free]
* [Open Software System for Interactive Applications (OSSIA)](https://ossia.io) - Open-source intermedia sequencer  (previously ‘i-score’)
* [Overtone](http://overtone.github.io/) - Live-coding. See also the [Leipzig](https://github.com/ctford/leipzig) composition library for Clojure and Clojurescript.
* [Sonic Pi](http://sonic-pi.net/) - Live-coding
* [SuperCollider](http://supercollider.github.io/) - Live-coding

### Edition

* [Digitale Musikedition](www.edirom.de) - based on Frans Wiering’s idea of a “multidimensional model” of a musical edition
* [“Freischütz Digital”](www.freischuetz-digital.de)
* [OCVE](www.chopinonline.ac.uk/ocve/) - Collection and comparison of primary source Chopin scores
* [“OPERA”](www.opera.adwmainz.de/informationen.html)
* [Tido](https://www.tido-music.com/) - [not free]

### Notation / Engraving / Score Rendering

See [Wikipedia's 'Comparison of scorewriters'](https://en.wikipedia.org/wiki/Comparison_of_scorewriters) to compare [Dorico](https://www.steinberg.net/en/products/dorico.html), [Finale](https://www.finalemusic.com/), [FORTE](https://www.fortenotation.com/en/products/writing-scores/forte-home/), [Lilypond](http://lilypond.org/) (and editors including [Denemo](http://www.denemo.org/), [Frescobaldi](https://sourceforge.net/projects/frescobaldi.mirror/), and [Hacklily](https://www.hacklily.org)), [MuseScore](https://musescore.org/), [Notion](https://www.presonus.com/products/Notion/), [Sibelius](https://www.avid.com/sibelius), and more.

In addition to which:
* [Abjad](http://abjad.mbrsi.org/#)
* GUIDO [Music Notation Format (GMN)](http://guidolib.sourceforge.net/GUIDO/) and [Engine Library](http://guidolib.sourceforge.net)
* SCORE: abandonware, but see Craig Sapp’s [Scorelib](http://scorelib.sapp.org/) library for parsing SCORE data files.
* [VexFlow](http://www.vexflow.com)
* [Verovio](http://www.verovio.org)

And further online-only applications (all commercial):
* [Flat](https://flat.io/) [not free]
* [forScore](https://forscore.co/) [not free]
* [irealpro](https://irealpro.com/) - real time accompaniment also supporting chord charts [not free]
* [neoScores](https://www.gogustaf.com/) [not free]
* [Newzik](https://newzik.com/) [not free]
* [Nkoda](https://www.nkoda.com/) [not free]
* [Noteflight](https://www.noteflight.com/) [not free]

### Optical Music Recognition (OMR)

See [Wikipedia's 'Comparison](https://en.wikipedia.org/wiki/Optical_music_recognition) for commercial software like [musitek](http://www.musitek.com/), [sharpeye](http://www.musicaleditor.com/scan-music.html), and [SmartScore](https://www.musitek.com/smartscore-pro.html), as well as freeware like [Audiveris](https://github.com/Audiveris/audiveris/wiki).
In addition to which:
* [PlayScore/ReadScoreLib](http://www.playscore.co/readscorelib/) by [SeeScore](https://www.seescore.co.uk/)

### Standard Formats

* [IEEE 1599](http://ieee1599.lim.di.unimi.it/) - multi-layer XML-based format for music.
* [MEI (Music Encoding Initiative)](http://music-encoding.org/) - an open-source effort to define a system for encoding musical documents in a machine-readable structure.
* [MIDI](https://www.midi.org)
* MNX File format (forthcoming) - [draft specifications](https://w3c.github.io/mnx/specification/).
* [MusicXML](http://www.musicxml.com/) - the standard open format for exchanging digital sheet music.
* [SMuFL (Standard Music Font Layout)](http://www.smufl.org/) - a specification for mapping music symbols to Unicode for use in music fonts.
* XXX - Further (not international standard) file formats supported by music21: ABC, Capella, Humdrum, MuseData, Noteworthy, NoteworthyBinary, Scala, TinyNotation (native to music21), Volpiano

## Teaching Theory / Fundamentals / Aural Skills

* [Ars-Nova](https://www.ars-nova.com/home6.html) - including 'Practica Musica', 'Counterpointer', 'Songworks', 'Musica Touch', 'Rythmist'  [not free]
* [Artusi](https://www.artusi.xyz) - interactive music theory exercises. Commercial launch 2019 [not free]
* [Auralia](https://www.risingsoftware.com/auralia/) - aural and fundamentals training [not free]
* [Chordify](https://chordify.net) - songwriting / leadsheets [fremium]
* [Four Score and More](https://fourscoreandmore.org/) - music theory resources including automatic score exercises generation
* [Harmonia](https://harmonia.illiacsoftware.com) - [not free]
* [Hook Theory](https://www.hooktheory.com) - songwriting / leadsheets [not free]
* [Indiana MFO](http://www.music.indiana.edu/departments/academic/music-theory/mfonline/about.shtml) - [not free]
* [musictheory.net](https://www.musictheory.net) - Lessons and exercises
* [Music Theory Practice](https://music-theory-practice.com) and their [external recommendations](https://music-theory-practice.com/best-online-music-theory-courses.html)
* [Music Theory Tutor](http://musictheorytutor.weebly.com/index.html) - free lessons over video conferencing
* [OpenMusicTheory](http://openmusictheory.com/) - a growing, online "textbook" for music theory and aural skills.
* [nSpireMe](www.nspireme.co.uk) - [not free]
* [SmartMusic](https://www.smartmusic.com) - [not free]

### Visualisation / Annotation

* [Audio Timeliner](http://www.singanewsong.org/audiotimeliner/) [not free]
* [Dezrann](http://www.dezrann.net/)
* [mdecks](https://mdecks.com/mapharmony.phtml) [not free]
* [Peachnote](https://www.peachnote.de/) - apps including [Tuttitempi](https://tuttitempi.com/): Score-aligned visualisation of the tempi used in multiple recordings.
* [Music Connection Machine](http://www.musicconnectionmachine.org/)
* [XronoMorph](https://www.dynamictonality.com/xronomorph.htm) - app for creating rhythmic and melodic loops

## Groups and Institutions

### Companies working on automatic composition with A.I.

* [Band-in-a-Box](http://www.bandinabox.com/) [not free]
* [Google Magenta Project](http://magenta.tensorflow.org/)
* [Jukedeck](https://www.jukedeck.com/) [not free]
* [Open AI](https://openai.com/) - [MuseNet](https://openai.com/blog/musenet/)
* [Sony CSL-Paris: Flow Machine](http://www.flow-machines.com/)

### Journals and conference proceedings

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
* [Transactions of the International Society for Music Information Retrieval (TISMIR)](http://tismir.ismir.net)

### Other gatherings and international organisations

* [Classical Music Hackdays](http://www.classicalmusichackday.org/#rec14632470)
* [International Association of Music Libraries, Archives and Documentation Centres (IAML)](http://www.iaml.info/)
* [MIREX](https://www.music-ir.org/mirex/wiki/MIREX_HOME)
* [MusicMesse, Frankfurt am Main](https://musik.messefrankfurt.com/frankfurt/en.html) - music industry 'trade fair'
* [SMT Music Informatics Group](https://sites.google.com/site/smtmig/)

### Projects

* [Analysis, creation and teaching of orchestration (ACTOR)](https://www.actorproject.org/)
* [Duchemin / 'Lost Voices' project](http://duchemin.haverford.edu/)
* [Neuma](http://www.iremus.cnrs.fr/fr/base-de-donnees/neuma)
* [SIMSSA](https://simssa.ca) - towards full-music search over a large collection of musical scores
* [Trompa](https://trompamusic.eu/)
* [Tudor Partbooks](http://www.tudorpartbooks.ac.uk)

### Research Groups

Here is a list of research laboratories working on MIR problems.
The entries are sorted first by alphabetical order of their country code, and secondly by group name.

| Group Name and URL | University/Company/City | Country code | Principal investigator | Notes |
| --- | --- | --- | --- | --- |
[Centre for Systematic Musicology](https://systematische-musikwissenschaft.uni-graz.at/) | U. of Graz | AT | Richard Parncutt
[Institute of Computational Perception](https://www.jku.at/en/institute-of-computational-perception/) | Johannes Kepler U., Linz | AT | Gerhard Widmer and Markus Schedl
[Intelligent Music Processing and Machine Learning Group](http://www.ofai.at/music/) | [Austrian Research Institute for Artificial Intelligence (OFAI)](http://www.ofai.at/research/impml/index.html) | AT | Gerhard Widmer
[Music Information Retrieval Lab](http://www.ifs.tuwien.ac.at/mir) | Vienna U. of Technology | AT | Andreas Rauber
[Universität für Musik und Darstellende Kunst Wien](https://www.mdw.ac.at/) | U. of Music and Performing Arts, Vienna | AT  | Werner Goebl
[Centre for Interdisciplinary Research in Music, Media and Technology (CIRMMT)](http://www.cirmmt.org/) | McGill U. | CA | | |
[Distributed Digital Music Archives & Libraries Lab (DDMAL)](http://ddmal.music.mcgill.ca/) | McGill U. | CA | Ichiro Fujinaga
[Digital and Cognitive Musicology Lab (DCML)](https://github.com/DCMLab) | EPFL | CH | Martin Rohrmeier
[Institute for Music Informatics and Musicology](http://hfm.eu/imwi/) | U. of Music, Karlsruhe | DE | Thomas Seedorf
[International Audio Laboratories Erlangen](http://www.audiolabs-erlangen.de/) | [Fraunhofer IIS](http://www.iis.fraunhofer.de/en.html) and [Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU)](http://www.fau.eu/), Erlangen | DE | Techniques and tools for analyzing, structuring, retrieving, navigating, and presenting music-related audio signals and other time-dependent multimedia data streams.
[Special Interest Group on Music Analysis](http://sig-ma.de/) | (N/A) | DE | (N/A)
[Music Informatics and Cognition Group](https://vbn.aau.dk/en/organisations/the-music-informatics-and-cognition-group), [CREATE](https://www.create.aau.dk)| Aalborg U. | DK | David Meredith
[Application of Information and Communication Technologies Research Group](http://www.atic.uma.es/index_atic.html) | U. of Málaga | ES | Lorenzo J. Tardón and Isabel Barbancho Perez
[Instituto Complutense de Ciencias Musicales (ICCMU)](https://iccmu.es/)| U. Complutense de Madrid | ES | Álvaro Torrente Sánchez-Guisande
[Music Technology Group](https://www.upf.edu/web/mtg) | U. Pompeu Fabra, Barcelona | ES | Xavier Serra | Specialized in sound and music computing. With more than 50 researchers, the MTG carries out research on topics such as audio signal processing, sound and music description, musical interfaces, sound and music communities and performance modeling among others
['Algomus' ('Algorithmic Musicology') group](http://www.algomus.fr/) | U. de Lille | FR | Mathieu Giraud |  Research lab on computational music analysis, focusing on large-scale analysis of scores
[Centre d'Études Supérieures de la Renaissance (CESR)](https://cesr.cnrs.fr/) | U. de Tours | FR | |
[Institut de Recherche et Coordination Acoustique / Musique (IRCAM)](http://www.ircam.fr/) | Paris | FR | Frank Madlener |
[IReMus](http://www.iremus.cnrs.fr/) | Paris | FR | |
[Institut de Recherche en Informatique de Toulouse (IRIT)](https://www.irit.fr/) | Toulouse | FR | | The [SAMoVA](https://www.irit.fr/recherches/SAMOVA/pagehome.html) team focuses its research activities mainly on audiovisual content structuring, analysis and modeling. The [MELODI](https://www.irit.fr/-Equipe-MELODI-) team focuses on natural language processing.
[Laboratoire Bordelais de Recherche en Informatique (LaBRI)](http://www.labri.fr/) and [Studio de Création Musical (SCRIME)](http://www.scrime.labri.fr/) | Bordeaux | FR | | Part of the French CNRS. The first research interest implies music information retrieval for enhancing music recommendations and automatic playlist creation. The second research interest involve creating new ways to play music interactively which is supported in the free and open-source intermedia sequencer [i-score](https://i-score.org/).
[Music Informatics Laboratory (LIM), Dept. of Computer Science](https://www.lim.di.unimi.it) | U. of Milan | IT | Goffredo Haus
[Media Interaction Group, Information Technology Research Institute (ITRI)](https://staff.aist.go.jp/m.goto/MIG/index-j.html) | [National Institute of Advanced Industrial Science and Technology (AIST)](https://www.aist.go.jp/index_en.html), Tsukuba | JPN | [Masataka Goto](https://staff.aist.go.jp/m.goto/)
[Music and Audio Computing Lab](http://mac.kaist.ac.kr/index.html) | [Korea Advanced Institute of Science and Technology (KAIST)](https://www.kaist.ac.kr/html/en/index.html) | KOR | Juhan Nam
[Music and Audio Research Group (MARG)](http://marg.snu.ac.kr) | Seoul National U. | KOR | Kyogu Lee |
[Multimedia Computing Group](https://www.tudelft.nl/ewi/over-de-faculteit/afdelingen/intelligent-systems/multimedia-computing/) | T.U. Delft | NL | Cynthia Liem and Julián Urbano working on music | The MMC Group develops algorithms for enriching, accessing, and searching large quantities of multimedia data. Our work on Music Information Retrieval focuses on search, recommendation, similarity, evaluation and methodological issues.
[RITMO Centre for Interdisciplinary Studies in Rhythm, Time and Motion Department of Musicology](https://www.uio.no/ritmo/) | U. of Oslo | NO | Anne Danielsen
[MIR Group](http://mir.dei.uc.pt/) | [University of Coimbra](https://www.uc.pt/) | PRT | Rui Pedro Paiva |
[Music and AI Lab](https://musicai.citi.sinica.edu.tw) | Academia Sinica | TWN | Yi-Hsuan Yang
[Centre for Computer Music Research (ICCMR)](http://cmr.soc.plymouth.ac.uk/index.html)  | U. of Plymouth | UK | Eduardo Miranda and Alexis Kirke
[Centre for Digital Music (C4DM)](http://c4dm.eecs.qmul.ac.uk/) | Queen Mary, U. of London | UK | Mark Sandler and Simon Dixon | C4DM is a world-leading multidisciplinary research group in the field of music and audio technology. Research ranges from record/replay equipment to the simulation and synthesis of instruments and voices, acoustic spaces, music understanding, delivery and retrieval. With a strong focus on making innovation usable, we are ideally placed to work with industry leaders in forging new business models for the music industry.
[Centre for Research in New Music (CeReNeM)](https://research.hud.ac.uk/institutes-centres/cerenem/) | U. of Huddersfield | UK | Michael Clarke
[Music Informatics Research Group (MIRG)](http://mirg.city.ac.uk/) | City U. London | UK | Tillman Weyde
[(Centre for) Practice and Research in Science and Music, (PRiSM)](https://www.rncm.ac.uk/research/research-centres-rncm/prism/) | RNCM and U. of Oxford | UK | Emily Howard and Marcus du Sautoy
[Center for Computer Assisted Research in the Humanities, (CCARH)](http://www.ccarh.org) | Stanford U. | USA | Craig Sapp and Eleanor Selfridge-Field
[Center for Music Technology (GTCMT)](http://www.gtcmt.gatech.edu/) | Georgia Tech | USA | Gil Weinberg
[Cognitive and Systematic Musicology Laboratory (CSML)](https://www.asc.ohio-state.edu/music/csml/home/index.php/Home) | Ohio State U. | USA | David Huron
International Music Information Retrieval Systems Evaluation Laboratory (IMIRSEL), [School of Information Sciences](https://ischool.illinois.edu/) | U. of Illinois at Urbana-Champaign (UIUC) | USA | J. Stephen Downie |
[MuE: Music + Engineering](http://mue.music.miami.edu/) | U. of Miami | USA | |
[Music and Entertainment Technology Laboratory (MET-lab)](http://www.met-lab.org) | Expressive and Creative Interaction Technologies (ExCITe) Center, Drexel U., Philadelphia | USA | Youngmoo Kim | Devoted to research in digital media technologies that will shape the future of entertainment. MET-lab's primary research focus encompasses several areas: music information retrieval, music production technology, new musical interfaces, and musical humanoid robotics. The lab also emphasizes K-12 outreach and hosts Summer Music Technology, a one-week experience based educational curriculum for high school students.
[Music and Audio Research Laboratory (MARL)](https://steinhardt.nyu.edu/marl/) | New York U. | USA | Juan Pablo Bello | Doctoral and masters programs in music technology in the heart of New York City. Main research areas include MIR, Immersive Audio, Music Cognition and Interactive Systems
[Music Informatics Group](http://www.musicinformatics.gatech.edu/about/related-classes/) | Georgia Tech Center for Music Technology | USA | Alexander Lerch
