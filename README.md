OCRmyPDF
========

Script aimed at performing optical character recognition (OCR) on PDF files from PDF files containing only images

Usage: ./OCRmyPDF.sh filename.pdf

ATTENTION: THE SCRIPTS ARE STILL IN DEVELOPMENT PHASE, PLEASE DO NOT USE !!!!

Features
--------

- Generates a searchable PDF/A file from PDF file containing only images
- Keeps the original resolution of the embedded images
- Validation of the generated file against the PDF/A specification using jhove


Motivation
----------

I searched the web for a free tool to OCR PDF files on linux/unix and found many but none of them was satisfying.
- Either they produced PDF files with misplaced text below the image (making copy/paste impossible)
- Or they changed the resolution of the embedded images
- Or they generated PDF file having a rediculous big size
- Or they crashed when trying to OCR some of my PDF files
- Or they did not produce valid PDF files (even though they were readable with my current PDF reader) 
On top of that none of them produced PDF/A files (format dedicated for long time storage / archiving)

... so I decided to develop my own tool (using various existing scripts as an inspiration)

Install
--------

TODO

Install java:
cd /usr/ports/java/openjdk7/ && make install clean

Install jhove:
download jhove from here: http://sourceforge.net/projects/jhove/files/jhove/
After extracting the JHOVE files to some directory "jhove", you have to edit the file "jhove/conf/jhove.conf" and change something in "something" to the actual directory (ending in "/jhove").




