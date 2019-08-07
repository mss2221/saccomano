---
layout: page
title:  "DH Projects"
---
### [The Serge Prokofiev Archive as Data](https://spa-data.github.io/spa-data/)

#### Columbia Rare Book and Manuscript Library
* MEI repository of musical sketches

[Prokofiev's Sketches]()
Playable transcriptions encoded in MEI and displayed with Verovio

The Serge Prokofiev Archive contains sketchbooks in which Prokofiev wrote out brief, musical ideas. The SPA-data repository makes available a small corpus of these sketches in machine readable form for analysis, in both MEI and MusicXML formats.

I used Jekyll with Verovio to generate individual pages for each sketch that display an image of the source material along with an SVG image of the encoded score, and that also allow the user to play a MIDI stream generated from the stored file.



__Project One:__

Prokofiev’s Correspondents: An Interactive Visualization of Letters, Postcards, and Telegrams from the Serge Prokofiev Archive.

Using publicly available metadata from Columbia’s Rare Book and Manuscript Library’s website, I created a web-based display with ArcGIS of the correspondence holdings in the Prokofiev archive. This involved preparing and cleaning the data set for use in a visualization program, researching available GIS applications and geolocation services, and acquiring the data wrangling skills necessary to produce an engaging and informative presentation online. The map provides a graphic representation of Prokofiev’s various residences while living in the West, as well as the locations of his correspondents. In addition, by highlighting outliers, the map allows users to discover aspects of Prokofiev’s personal and professional life not accessible through a simple enumerative listing of the archive’s contents.

[ArcGIS: Prokofiev's Correspondents](https://arcg.is/mKWbj)

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Correspondence Sites" src="//columbia.maps.arcgis.com/apps/Embed/index.html?webmap=527e9d78086740968ed21600e92c84ba&extent=-31.8604,31.9532,59.9854,64.8868&zoom=true&previewImage=false&scale=true&legendlayers=true&disable_scroll=true&theme=light"></iframe></div>
<br><br>

__Project Two:__

[Serge Prokofiev Archive Finding Aid](https://findingaids.library.columbia.edu/ead/nnc-rb/ldpd_10815449)
Columbia University Rare Book and Manuscript Library

From May of 2017 through January of 2018 I was responsible for making records of the archive’s holdings available online on the library’s website. This entailed first converting all the received digital records into XML and then transforming them into the standard Columbia EAD format. Data had to be cleaned and normalized in order to be processed properly by XSL transforms, and separate transforms had to be written for each subseries of items in the archive. For example, books, manuscripts, and correspondence were all stored in different formats, with different field names, and containing different sets of metadata. The result was the first publicly available listing of the archive’s holdings, including nearly 10,000 pieces of personal and business correspondence written between 1912 and 1947.
<br><br>

__Project Three:__

[The Serge Prokofiev Archive as Data](https://spa-data.github.io/spa-data/)

A public interface to the Gibhub archive containing metadata for the items in the Serge Prokofiev Archive. Includes space to showcase digital humanities projects by myself and the project founder, Dr. Natalia Ermolaev. Created using Jekyll.

__Presentations and Workshops__


* [Digital Centers Internship Program](https://library.columbia.edu/about/jobs-internships/digital_internship.html)
Columbia University Libraries and the
[Music & Arts Library](https://library.columbia.edu/libraries/music.html) Digital Music Lab

Selected for a one-year internship program in music encoding and computer assisted analysis.

[Blog post on workflow](https://blogs.cul.columbia.edu/dcip/2016/12/22/digital-archives-and-music-scores-analysis-manipulation-and-display/)
