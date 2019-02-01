# nuctools_shiny

This package allows one to interactively click and pick points on a distance histogram, used to calculate NRL in chromatin, and annotate the plot in order to calculate the NRL.


packages needed include shiny, zoo and plyr


```
#command line
git clone https://github.com/chrisclarkson/nuctools_shiny/

cd nuctools_shiny

ls *NRL.txt > files #list all files with histogram data and put this list in a 'files'

#the Rscript will read 'files' and can then the app can be run


#R
install.packages('shiny')

install.packages('zoo')

install.packages('plyr')



```


