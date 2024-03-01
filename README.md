# arxiv_to_bib
This simple script takes an arxiv.org number (i.e. '2202.01591' for the paper https://arxiv.org/abs/2202.01591) and gives a bibtex entry with authors, title, arxiv link and doi.

Bugs: might give trouble with special characters in the title, seems to not work for entries earlier than 2010, cannot retrieve journal publications.

I would like to modify this by using the inspirehep API and maybe build a database via PSQL. Very much WIP.
