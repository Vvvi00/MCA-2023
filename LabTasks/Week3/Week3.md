# Week 3-Encoding Notated Music
## Task 1-Generating MusicXML and MEI files
Based on last week's task, I exported the transcribed composition from MuseScore to a MusicXML file, and then converted the MusicXML file to an MEI file.

- Download the MusicXML file [here](../../data/Blank.Space.Taylor.Swift.musicxml).
- Download the MEI file [here](../../data/Blank.Space.Taylor.Swift.mei).

## Task 2-Rendering the MEI file with Verovio

{% include_relative verovio_inline.html %}

## Task 3-Comparing MusicXML&MEI files
While both MusicXML and MEI are intended to represent sheet music in a digital format, MusicXML focuses more on the actual exchange and use in sheet music software, while MEI provides a more comprehensive and extensible framework suitable for scholarly encoding and detailed music representation across a variety of traditions. There are three specific points:

#### Format and Structure:
- MusicXML: An XML-based format for representing Western sheet music, with elements in the hierarchy representing musical notation, notes, dynamics, etc.
- MEI: An XML-based format designed to encode a wide variety of musical repertoire; a hierarchical structure with a modular approach that allows for extensions for specific musical genres.

#### Beat Number:
- MusicXML: The beat number is represented by the <time> element. There are nested elements within this element that define the beat type and the number of beats in their respective <beats> and <beat-type> elements.
- MEI: The same beat numbers are defined in the self-enclosed <metreSig> element. Similar to <note> tags, instead of assigning attributes in child items as in MusicXML, attributes are written in the tag itself.

#### Extensibility:
- MusicXML: Limited extensibility for specific use cases.
- MEI: Highly extensible with a modular design, allowing users to create custom modules for specialized applications.
