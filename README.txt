---------------------------------------------
        Scientific Report LaTeX Template
                Readme
            by Jac Thomas
              16/01/2021
         Jac.Thomas2@liverpool.ac.uk
---------------------------------------------

Quick set up:

    If this folder has come to you in the form of
    a .zip file, then unpack the contents into a
    folder and upload all of the files into a New
    Project on Overleaf (overleaf.com). It takes
    2 seconds to make a profile if you don't already
    have one.

This folder contains everything you would reasonably need
to create a simple but professional scientific report, 
including:

    Tables
    Figures
    Equations
    Title page
    Contents page
    Citations
    Bibliography
    Hyperlinks

It doesn't contain anything too fancy, like putting
paragraph text in two columns. This folder is also
intended as a guide for people learning about/learning
how to use LaTeX, so there are pretty extensive comments
and annotations in each of the files. If you've just arrived
here and want to learn how to learn how to use latex as
quickly as possibly, read "latex_tutorial.txt".

The contents of this folder are as follows:

    README.txt      
        Explains the contents of the folder.

    latex_tutorial.txt
        Basic introduction to how LaTeX works. Can be
        covered in 5 minutes. Designed for absolute
        beginners.
    
    main.tex        
        The main TeX file. Contains extensive annotations.
    
    preamble.sty    
        Stuff for the preamble of main.tex. This
        file has been made in order to keep the preamble
        of main.tex looking neat. It is called on the 2nd
        line of main.tex, by "\usepackage{preamble}".
        This command instructs LaTeX to put everything in
        preamble.sty in the preamble of main.tex. You could
        copy and paste everything in this file into the
        preamble (the bit before "\begin{document}") of 
        main.tex, remove the line "\usepackage{preamble}",
        and the result would be exactly the same.

    refs.bib
        Information on the references used in main.tex.
        Also explains how to add more references of
        different types.

    prop_ev_marr.png
        An example graphic.

    graph2.png
        A second example graph.