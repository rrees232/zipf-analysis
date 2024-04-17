zipf analysis
=============

This repository contains code to observe
whether books adhere to Zipf's law,
as done in support of the paper
"Zipf analysis of 19th-century English-language books",
V.Dracula,
to appear in Annals of Computational Linguistics, 2022. 

To run the code, you will need the Pandas package installed.

To reproduce the figures in the publiation, run the command:
	bash bin/run_analysis.sh

This script will automatically pull text of the 2 books to process
(Frankenstein and Dracula) from project Gutenberg (Gutenberg.org) and place them into 'data' directory. 
Internet access is required. 
