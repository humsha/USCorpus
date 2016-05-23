Urdu Summary Corpus Tools
---------------------------------------------------
Muhammad Humayoun (PhD)
humayoun@gmail.com

Post-doc Researher
Institut de Recherche en Informatique de Toulouse (IRIT)
Universite Paul Sabatier, Toulouse, France
http://www.irit.fr

Assistant Professor
University of Central Punjab,
Lahore, Pakistan
http://www.ucp.edu.pk/


Muhammad Uzair, uzairnaroo@gmail.com
---------------------------------------------------

+ Normalization is taken from [1], Diacritic marks are also removed in this step. 
+ Table-lookup based Morphological Analyzer and lemmatizer is built from [3].
+ Stemmer is built from [1] 
+ Table-lookup based POS tagger is built from [4]. We used unigram and bigram counts.


Commands:

+ Unzip USCTools.zip 
+ Open Console
+ Go to USCTools directly typing: cd USCTools


For Normalization
$ java -cp bin USCTools normalize input.txt output.txt 	 

For Lemmatization
$ java -cp bin USCTools lemmatize input.txt output.txt 	 

For Morphological analysis
$ java -cp bin USCTools morph_analysis input.txt output.txt 	 

For stemming by Assas-Band
$ java -cp bin USCTools stemming input.txt output.txt 	 

For POS tagging (table lookup tagger build from urmono.tag file shared by [1])
$ java -cp bin USCTools tagging input.txt output.txt 	 

[1] Q.-u.-A. Akram, A. Naseer, and S. Hussain. Proceedings of the 7th Workshop
on Asian Language Resources (ALR7), chapter Assas-band, an Affix-
Exception-List Based Urdu Stemmer, pages 40–47. Association for Computational
Linguistics, 2009.


[2] A. Gulzar. Urdu normalization utility v1.0. Technical report,
Center for Language Engineering, Al-kwarzimi Institute of Computer
Science (KICS), University of Engineering, Lahore, Pakistan.
http://www.cle.org.pk/software/langproc/urdunormalization.htm, 2007.


[3] M. Humayoun, H. Hammarström, and A. Ranta. Urdu morphology, orthography
and lexicon extraction. CAASL-2: The Second Workshop on
Computational Approaches to Arabic Script-based Languages, LSA Linguistic
Institute. Stanford University, California, USA., pages 21–22, 2007.
http://www.lama.univ-savoie.fr/ humayoun/UrduMorph/.
0

[4] B. Jawaid, A. Kamran, and O. Bojar. A tagged corpus and a tagger for
urdu. In N. C. C. Chair), K. Choukri, T. Declerck, H. Loftsson, B. Maegaard,
J. Mariani, A. Moreno, J. Odijk, and S. Piperidis, editors, Proceedings
of the Ninth International Conference on Language Resources and
Evaluation (LREC’14), Reykjavik, Iceland, may 2014. European Language
Resources Association (ELRA).
https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-65A9-5
