# csharp_stv
Scripts for automating C# elections

# I'm new to R - what's going on here?

Go to [this website](https://posit.co/download/rstudio-desktop/), follow their instructions to download & install the R language & the IDE RStudio.

The two files I've provided you aren't actually scripts - it's a little easier than that! .rmd stands for "R Markdown"; they're essentially a halfway point between a script and a text file. The text interleaved between the code chunks should help you figure out exactly what to do to run STV for elections.

# What are these files? 

`csharp_s20_nominations.rmd` is the file I used to take all the nominations and boil them down into something I could easily send to nominees, with the reasons included. [Here is a link](https://docs.google.com/forms/d/e/1FAIpQLSdA9sN8Z4KGgaSZEJLG5fOxSDX8Y8ycuRpenqNJuKmtvX-o1g/viewform) to the nominations form that created the spreadsheet I input into this code. 

`csharp_s20_stv.rmd` is the file I used to run C#'s actual STV elections. The Bridge doesn't exist anymore, and that is what we used to run elections in that year, so unfortunately I can't get my hands on the exact data that was input into this code. But whatever we use to run elections will likely produce data of the same style, so small changes will make this code fine. 
