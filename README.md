# ABL README

Alignment-Based Learning (ABL) is a symbolic grammar inference framework that
has succesfully been applied for several unsupervised machine learning tasks
in Natural Language Processing (NLP). Given sequences of symbols only, a
system that implements ABL induces structure by aligning and comparing the
input sequences. As a result, the input sequences are augmented with the
induced structure. For more information, see the reference list at the end of
this file.

This package contains a C++ implementation of ABL. It is maintained by:

   Menno van Zaanen (menno@ics.mq.edu.au)

The latest version of this package can be found on:

   http://www.ics.mq.edu.au/~menno/research/software/abl/

For any questions, remarks, bugs, improvements, or any other matters of
concern about this package, send an email to: menno@ics.mq.edu.au.


# IMPORTANT FILES

Please read the following before using this ABL package:

LICENCE     : conditions and terms for using this software
INSTALL     : information on installing this software
NEWS        : what is new in this version


# REQUIREMENTS

The ABL package should run on any standard UNIX based platform. It requires a
C++ compiler (> GCC 3.0). We have succesfully compiled and tested it on the
following platforms:

- GNU/Linux:
   Slackware 10.0 with gcc-3.3.4
   Debian 3.1 with gcc-4.0.3
   SuSE 8.3 with gcc-3.3.3

- SunOS:
   5.9 with gcc-3.4.4

# ACKNOWLEDGEMENTS

The ABL package was developed by Menno van Zaanen (Macquarie University) and
Jeroen Geertzen (Tilburg University). The project was financially supported
with a grant from Macquarie University.


# REFERENCES

[1]   "Bootstrapping Structure into Language: Alignment-Based Learning",
      Menno van Zaanen, 2001,
      PhD Thesis, School of Computing, University of Leeds, UK.

[2]   "Implementing Alignment-Based Learning",
      Menno van Zaanen, 2002,
      In: Proceedings of the International Colloquium on Grammatical 
      Inference (ICGI), pp 312-314, Amsterdam, the Netherlands.

[3]   "String alignment in grammatical inference: what suffix trees can do",
      Jeroen Geertzen, 2003,
      Technical report ILK-0311, Tilburg University, The Netherlands.
