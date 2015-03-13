ISGC-ANSE-2014
==============

ISGC 2014 ANSE paper

To build the paper the reccomended way:

latex 'Integrating Network-Awareness and Network-Management into PhEDEx.tex'

dvips -Ppdf -z -G0 'Integrating Network-Awareness and Network-Management into PhEDEx.dvi' -o

ps2pdf -z -sPAPERSIZE=A4 'Integrating Network-Awareness and Network-Management into PhEDEx.ps'

...but I find that doesn't work well. It works with pdflatex, though that's not recommended:

pdflatex 'Integrating Network-Awareness and Network-Management into PhEDEx.tex'

(if it complains about an error, just hit <RETURN>, it should continue)

N.B. Starting from a clean directory, you will need to run pdflatex twice in order to get the figure numbers and references correct.

Clean the working directory with:

./clean.sh
