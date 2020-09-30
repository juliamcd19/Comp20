Assignment:
Your assignment is to create an XML document that is a set list for a cover band.  
Each entry should have a field to describe the artist(s), title, music genre, and year the song was released.

Your file must include at least 10 songs.  
The data must be real, but you can use any artist/band(s).

Create a CSS file for aesthetic display of the data.

Note:  You are NOT required to produce DTD, schema, or XSL files, 
but you may try them if you want to explore this technology. 
(Extra credit may be awarded if your work is exemplary).

Process:
Idea: "Atta James" a jazz-based, Etta James-based cover band
Utilizing XML, CSS, Schema

XML:
Created XML file for songlist. 
Made coverBand element the root element because this page will only include one band's one setlist.
This can be easily adapted to include more bands and/or setlists for this band.
Included name, description, songs of band.
Added 10 songs each with title, artist, genre, year.

CSS:
Created CSS document for songlist.
Added basic display styling, color, lines, font sizes to page.

XSD:
Created XSD document to be based off of XML songlist.
Starting from top, added each element, complex or simple. 
Added unbounded maxOccurs sequence for song element due to repeating element.
Adaptable to add more bands by incerasing maxOccurs attribute on element sequence.

