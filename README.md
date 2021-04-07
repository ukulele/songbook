# The Ukulele Songbook Project

## The aims

* to have an open songbook with songs annotated in a relatively straightforward markup.
* to use LaTeX to leverage its typesetting ability.
* have multiple formats of output to cater for a wide range of requirements such as large text or fitting to projector screens.

#### Songbook

LaTeX is an excellent and mature typesetting system which generates PDFs for us, and the songs are all stored in this format, along with various master documents that encompass:

* Archived songs
* New songs
* Special occasion songs
* Single songs

There's plenty of flexibility. The idea was to not have one hefty master songbook, but instead several smaller ones.

LaTeX formatting is not particularly easy, but songs are quite straightforward, and we hope the simple markup is easy to understand.

## Building

Maven and Java.

Currently using Java version:
```
openjdk 11.0.8 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
Eclipse OpenJ9 VM AdoptOpenJDK (build openj9-0.21.0, JRE 11 Mac OS X amd64-64-Bit Compressed References 20200715_677 (JIT enabled, AOT enabled)
OpenJ9   - 34cf4c075
OMR      - 113e54219
JCL      - 95bb504fbb based on jdk-11.0.8+10)
```

Clone the repo and run 

`mvn install`

Then

`mvn latex:latex`

To build the PDF in `<root>/target/site/songbook/songbook.pdf`

And a help document in `<root>/target/site/help/help.pdf`

----------------------------------------

The Ukulele Songbook project by Vish Vishvanath, Matt Gunning, Alyn Gwyndaf, Charlie Ullman, et al is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.

http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US

