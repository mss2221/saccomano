---
layout: page
title:  "Digital Projects"
---



__[Music Encoding in Minimal Editions](https://hcommons.org/deposits/item/hc:31979/)__\\
Integration of encoded music in an online minimal edition

<!-- * __[El corrido mexicano](https://mss2221.github.io/corridosEd/)__

* __[Serbian hymns from Zagreb](https://mss2221.github.io/zagreb/)__ -->

These two demo projects show how scholars can present their research on an easily accessible and maintainable platform.  Music is transcribed into MEI, the [Music Encoding Intiative](https://music-encoding.org/) format, rendered with the [Veriovio](https://www.verovio.org/index.xhtml) music engraving library, and served through a static site using the ["_Ed._"](https://github.com/minicomp/ed) Jekyll template for [minimal editions](https://go-dh.github.io/mincomp/).
<br/>
<br/>

---
<br/>
__[The Serge Prokofiev Archive as Data](https://spa-data.github.io/spa-data/)__\\
Projects based on encoding, retrieval, and display of metadata for\\
[The Serge Prokofiev Archive](https://library.columbia.edu/libraries/rbml/units/performing_arts/prokofiev.html), Columbia Rare Book and Manuscript Library
<br><br>

* __[Prokofiev's Sketchbooks](https://mss2221.github.io/spademo/sketches/)__\\
_Playable transcriptions encoded in MEI and displayed with Verovio_

The Serge Prokofiev Archive contains sketchbooks in which Prokofiev wrote out brief, musical ideas. The SPA-data repository makes available a small corpus of these sketches in machine readable form for analysis, in both MEI and MusicXML formats.

Verovio was incorporated into the Jekyll website builder to generate individual pages for each sketch. Each page provides an image of the source material, an SVG rendering of the encoded score, and an audio player that allows the user to hear a MIDI stream generated from the encoding.

<br/>
* __[Prokofiev’s Correspondents](https://arcg.is/mKWbj)__\\
_An Interactive Visualization of Letters, Postcards, and Telegrams from the Serge Prokofiev Archive._

Using publicly available metadata from Columbia’s Rare Book and Manuscript Library’s website, I created a web-based display with ArcGIS of the correspondence holdings in the Prokofiev archive. This involved preparing and cleaning the data set for use in a visualization program, researching available GIS applications and geolocation services, and acquiring the data wrangling skills necessary to produce an engaging and informative presentation online. The map provides a graphic representation of Prokofiev’s various residences while living in the West, as well as the locations of his correspondents. In addition, by highlighting outliers, the map allows users to discover aspects of Prokofiev’s personal and professional life not accessible through a simple enumerative listing of the archive’s contents.


<style>.embed-container {position: relative; padding-bottom: 50%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="250" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Correspondence Sites" src="//www.arcgis.com/apps/Embed/index.html?webmap=527e9d78086740968ed21600e92c84ba&extent=-6.6347,38.5844,25.8848,58.6096&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>
{::options parse_block_html="true" /}
<div style="float: right;">[View map in ArcGIS](https://arcg.is/mKWbj)
</div>
<br><br>

* __[Project Website: The Serge Prokofiev Archive as Data](https://spa-data.github.io/spa-data/)__\\
_Website created with Jekyll for SPA-Data repository_

A public interface to the Gibhub archive containing metadata for the items in the Serge Prokofiev Archive. Includes space to showcase digital humanities projects by myself and project founder Dr.&nbsp;Natalia Ermolaev. Created using Jekyll. Integrated with Verovio for display and playing of MEI encoded scores.
<br><br>


* __[The Serge Prokofiev Archive Finding Aid](https://findingaids.library.columbia.edu/ead/nnc-rb/ldpd_10815449)__\\
_Columbia University Rare Book and Manuscript Library_

From May of 2017 through January of 2018 I was responsible for making records of the archive’s holdings available online on the library’s website. This entailed first converting all the received digital records into XML and then transforming them into the standard Columbia EAD format. Data had to be cleaned and normalized in order to be processed properly by XSL transforms, and separate transforms had to be written for each subseries of items in the archive. For example, books, manuscripts, and correspondence were all stored in different formats, with different field names, and containing different sets of metadata. The result was the first publicly available listing of the archive’s holdings, including nearly 10,000 pieces of personal and business correspondence written between 1912 and 1947.
