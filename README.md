hoaiclasses
===========

Ruby Classes to perform  fee calculations for architects and engineers in Germany.
This is a small project I do to get aquainted with Ruby and object oriented programming.

On the rare chance anyone running across this would like to comment or even contribute:
All your efforts are welcome!


## A little background

Germany is one of the last countries with a legal regulation of the fees of architects and engineers.
Although many find such a system debatable per se it offers a good idea about the money vs. service-ratio
of things such as architectonical designs, detailing, contracting and site supervision as well as the 
value of engineering services (structural, mechanical, electrical...) of all kinds.
This regulation is called "HOAI", short for "Honorarordnung für Architekten und Ingenieure" or 
"Fee ordinance for Architects and Engineers".

The idea behind it is pretty straight forward:
The higher the building cost and the more complicated the project, the greater 
the effort to do the planning has to be.
In order to determin the correct fee you pick it from a fee table where the columns match so called 
"fee zones" to describe the complexity of the project and the lines match a building cost value.
In this respect, the complete architectural services for a building of middle complexity (fee zone "III")
and building costs of say 1 000 000.00 EUR will for example end up with a fee of 130 000.00 EUR.

Of course, there is a bit more complexity behind this, but you'll get the idea.
For example, you have to take different extra percentages, service phases and fee table versions 
into account, to only name a few of the problems you'll run across when doing the calculation.

## The goal of this project
The classes in this repo want to take the pain out of the process described above by:
* providing standardized fee tables of the fee systems from 1998 until today
* providing a ruby class to access these fee tables and to do the basic calculations
* providing a cli to run, test and integrate the above
* (Maybe) providing GUI tools to do the same

Berlin, October 2014


#### Further reading:
* [Another fee calculator in German, commercial: www.hoai.de](http://www.hoai.de/online/hoai_rechner/index.php)
* [More about the HOAI on the German Wikipedia](http://de.wikipedia.org/wiki/Honorarordnung_für_Architekten_und_Ingenieure)
* [A very nice PDF comparing Architectural services in Germany and the UK/US form the Bund Deutscher Architekten](http://www.bda-bund.de/fileadmin/mediaFiles/Bundesverband/pdfs/CoFA_Flyer.pdf)



