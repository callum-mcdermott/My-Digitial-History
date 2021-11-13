# Devlog 2: November 13, 2021

## What I did

* I added the third individual to the Knowledge Graph
* I also looked at Geo4j and did the demo/sample one to get familiar with it. I decided to not use it for this project as the data I am using is too messy and would require me to actually fix both Christina and Susan's data to fit mine in a uniform way and this would take too long. Right now I can just enter the data manually into Gephi and not physically do that on the spreadsheet. (I know that Ursus Maritimus is Polar Bear which means I do not physically have to enter that into the slot on the excel sheet as I know and I know it already exists on Gephi). However once Gephi is finished I will have a large multi purpose uniform database that could be used on Neo4j as it would be uniform.
* Decided to stop with this as the Graph can show the top 3 people on Portfolio and if I have time I can add the fourth and so in from there
* After adding the third I decided to start adding species that the individuals have taken photos of. (Polar Bear, Arctic Fox, Ivory Gull...)
* This was easy for my data as I always include the Common name for the species that I enter into Portfolio (and I did not want to use the Latin names for this)
* For Christina data this is a problem as she has not written the Common name down so this has caused me to clean the data up and add the common names for all the items that are needed. This has been really annoying but I have experience doing this as I did this for my data and I am currently about halfway done.

## What I need to do

* Size of the nodes still remains in the air for me. I think I will make things based on either what they are (have creators, species and catalogers) be different sizes in a uniform way or have the sizes dictate the amount of each item. Could go either way on this and have not made my mind up
* Colour is not yet concrete but I have decided that I will colour code things based on what they represent. Creator, Cataloger and Species will be a certain colour
* As for the Species what I want to do is also add the taxonomy as a node for them. This would involve adding the genus, family, order, class, phylum and Kingdom. I want to do this as it will group the data and tell us/the museum what we have been emphasizing in digitization. Are any certain group over/under represented.
* This should be a easier/quicker to do than for the specific species as once one of the genus is in all I have to do is link the data/make the relationship. 

[Here is what it looks like so far](https://github.com/callum-mcdermott/My-Digitial-History/blob/main/Portfolio%204.0.pdf)
