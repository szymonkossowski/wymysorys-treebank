# Summary
`wymysorys-treebank` is the first treebank for the Wymysorys language, complied in compliance with 
the [Universal Dependencies (UD)](https://universaldependencies.org/) framework, compiled as a part of my Bachelor's Thesis 
for the Bachelor of Arts degree in International Studies in Computational Linguistics at the University of Tübingen in Germany. 

The treebank contains 120 manually annotated sentences consisting of 1903 tokens. The treebank includes texts from 7 sources
across 5 genres.

# Introduction
This Wymysorys treebank contains 120 sentences and 1903 tokens, collected from 7 texts belonging to 5 genres: speech, encyclopedia, 
narration, poetry, and grammar. The genres are denoted in the metadata of each sentence as `# text_genre = [genre]`; the genres 
are denoted as follows: `speech`, `encyclopedia`, `narration`, `poetry`, `grammar`.

The texts were fully manually annotated and later validated with the use of the `validate.py` script
shared by the UD. The validation was carried out on three first levels, as the levels 4 and 5 require access to the language-specific 
labels and guidelines, which have not been defined for Wymysorys, a language absent from the UD.

The included texts are:
+ Król, Tymoteusz. (2023); *Wymysoü ej śejny, kliny śtot. Gyśihta fu Wymysiöejyn yr wymysiöeryśa śpröh*
*/ Wilamowice to piękne, małe miasto. Wilamowskojęzyczne opowieści Wilamowian*; Polskie Towarzystwo Ludoznawcze

An extensive set of the transcriptions of interviews with Wymysorys-speakers by Tymoteusz Król. Primarily in the speech 
genre, in the metadata in the treebank denoted as `# text_source = "Wilamowice to piękne, małe miasto"`

+ Król, Tymoteusz (2022); *Dy Wymysiöejyn ȧn jyr nökwyn*; Stowarzyszenie Wilamowianie

A popular-science booklet about the folk culture of the Vilamovians and their neighbours by Tymoteusz Król. Represents the 
encyclopedia genre, in the metadata in the treebank denoted as `# text_source = "Dy Wymysiöejyn ȧn jyr nökwyn".

+ Król, Tymoteusz (2025); *Wymysiöejer kistiöeryja ˙an łidła fum Płaćnik-Pejter / Wilamowskie gawędy i pieśni Piotrka Płaćnika*; 
Narodowy Instytut Kultury i Dziedzictwa Wsi 

A book with Wymysorys folk songs and tales from Wilamowice, gathered by Piotrek Płaćnik, edited by Tymoteusz Król. Texts from 
this book represent two genres: narration and poetry; in the metadata in the treebank denoted as 
`# text_source = "Wilamowskie gawędy i pieśni Piotrka Płaćnika".

+ de Saint-Exupéry, Antoine (2019); *Der Kliny Fjyśt*; Ośrodek Zaangażowanych Badań nad Ciągłością Kulturową; translated 
from French by Tymoteusz Król and Joanna Maryniak

Wymysorys translation of the "Little Prince" by Antoine de Saint-Exupéry, represents the narration genre. In the metadata 
in the treebank denoted as `# text_source = "Der Kliny Fjyśt"`.

+ Szutow, Paweł (2024); *S’łjyrbihła cyr wymysiöeryśa śpröh fjy dy grusa łoüt / Podręcznik do nauki języka wilamowskiego *
*dla dorosłych*; Wydawnictwo Cum Laude

A Wymysorys textbook for adults, genre: grammar; in the metadata in the treebank denoted as 
`# text_source = "S’Łjyrbihła cyr wymysiöeryśa śpröh fjy dy grusa łoüt"`.

+ Król, Tymoteusz (2011); *S’Ława fum Wilhelm* 

An epic long poem in Wymysorys; genre: poetry; in the treebank denoted as `# text_source = "S’Ława fum Wilhelm"`.

+ Biesik, Florian (1921); *Uf jer wełt*

An epic long poem in Wymysorys, inspired by the Dante Alighieri's *Divine Comedy*; genre: poetry; in the treebank 
denoted as `# text_source = "Uf jer wełt"`.

# Acknowledgements
I want to thank my B.A. thesis supervisor, Dr. Johannes Dellert, for his invaluable support during the process of building 
the treebank. I am also grateful to Dr. Tymoteusz Król for his advice on the sources for the treebank and where to look for them.

# References
+ Andrason, A. and T. Król (2016). *A grammar of Wymysorys*. Durham: Duke University Slavic and East European Resource Center.
+ de Marneffe, M.-C., C. D. Manning, J. Nivre, and D. Zeman (2021, 07). Universal dependencies. *Computational Linguistics 47*(2), 255–308.