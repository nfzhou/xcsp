This is an interpreter for the XCSP language (www.xcsp.org) written in Picat (picat-lang.org).
This program assumes correct syntax, and thus does not detect syntax errors. Also, it assumes
that no operators or keywords are used as identifiers.

Given an XCSP instance, say "nqueens_8.xml", this program can be run as follows:
   
    Picat> cl("xcsp")
    Picat> main("nqueens_8")

Alternatively, this program can be run as a standalone command:

    picat xcsp nqueens_8
