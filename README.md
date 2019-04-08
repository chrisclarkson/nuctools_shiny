# nuctools_shiny

Nucleosome Repeat Length (NRL) is a calculation that I have had to perform many times throughout my PhD. 

This measurement serves as a metric for nucleosome packing density for a piece of chromatin.

It involves manual point/peak picking on a plot called a phasogram.

This applet allows one to interactively click and pick points on phasograms, and interactively calculate the NRL value for many different phasograms by use of a 'Next' and 'Back' button. 

This applet save me a lot of time.

Exemplary data is supplied from my other page: https://github.com/chrisclarkson/NRL_calc which documents my paper.

Packages needed include shiny, zoo and plyr


```
#command line
git clone https://github.com/chrisclarkson/nuctools_shiny/

cd nuctools_shiny

ls *aggregate.txt > files #list all files with phasogram data in 'files'

#the Rscript will read 'files' and can then the app can be run


#R
install.packages('shiny')

install.packages('zoo')

install.packages('plyr')

Rscript NRL_multiple_files.R

```


