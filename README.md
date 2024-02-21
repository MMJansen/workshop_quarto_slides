# Creating Slides with Quarto

These are the files used for a workshop on creating slides with Quarto. The workshop is mainly about Revealjs.

Take a look at:  

-  `workshop_quarto_slides.pdf` for the handout
-  `workshop_quarto_slides.qmd` to see how the slides were made

To get the **workshop experience**:  

-  Start by reading `workshop_quarto_slides.pdf`
    -  the html is a lot nicer, but then you have to render the qmd first to get the complete view
-  Do the exercises when prompted


To **render the qmd**, some work has to be done:  

-  Place the files (at least the qmd and the resources_main) in an R project
-  You have to add some extensions to the project:
    - See this warning from the Quarto people:  
*Quarto extensions may execute code when documents are rendered. Therefore, if you do not trust the author of an extension, do not install or use the extension.*
    -   If you decide you trust the authors, run these lines in the terminal (RStudio user here), one by one:
    -  `quarto add coatless/quarto-webr`
    -  `quarto add produnis/quarto-timer`
    -  `quarto add quarto-ext/pointer`
-  Now the qmd can be rendered
