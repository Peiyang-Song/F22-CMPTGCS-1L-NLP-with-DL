# Peiyang-NLP-Project
## A brief introduction to this project

This project is conducted by Peiyang Song (he/him/his), an undergrad of CCS Computing in his first year. In view of his multilingual nature, this project focuses at least some more on Mandarin NLP, but not necessarily restricted to that. This project is based on the groundbreaking publication *NLP from Scratch* by Dr. Ronan Collobert, but again, not restricted to that.

## The main topic of this project

This project aims to develop a unified model capable of addressing multiple NLP tagging tasks with reliance on limited data (i.e., natural language) input with the help of end-to-end multi-layer neural networks in Deep Learning. Favorable results are shown through tests in real time and comparisons with well-established benchmarks in the industry. For more specific information about this project, please use the files in this repo according to the instructions below.

## Keywords

Multilingual Natural Language Processing, Tagging, Deep Learning, Multi-layer Neural Networks, Backpropagation, End-To-End Architecture, Part-Of-Speech Tagging, Chunking, Named Entity Recognition, Semantic Role Labeling, Benchmark System, Multi-task Handling.

## A brief introduction to the files in this project

1. README.md (this file): a broad picture of what this project deals with and what each file is used for.
2. PROGRESS.md: a calendar that keeps track of the progress of this project.
3. Textbook - NLP textbook.pdf: a classical textbook on NLP, by Dr. Dan Jurafsky
4. Agenda - NLPCC2022 handbook.pdf: an agenda of NLPCC2022, an influential conference in the field of Mandarin NLP
5. Publication - NLP from Scratch.pdf: Groundbreaking work on incorporating DL into NLP, by Dr. Ronan Collobert
6. Publication - Deep Learning for Efficient Discriminative Parsing.pdf: Tightly related work with NLP from Scratch, by Dr. Ronan Collobert
7. Benchmark - Chunking CHK.htm: Benchmark on chunking.
8. Benchmark - Named Entity Recognition NER.htm: Benchmark on Named Entity Recognition.
9. Benchmark - Part of Speech POS.pdf: Benchmark on Part-of-Speech Tagging.
10. Benchmark - Semantic Role Labeling SRL.htm: Benchmark on Semantic Role Labeling.
11. Benchmark - Syntactic Parsing PSG.pdf: Benchmark on Syntactic Parsing.
12. NLP from Scratch_Peiyang Song.pptx: Slides for my third presentation.
13. Note - Websites.docx: Lecture note for websites containing massive study resources (presenter: Prof. Phill Conrad; note taker: Peiyang Song).
14. Note - AWS Zoom Meeting: Meeting record (presenter: James Woods; host: Prof. Phill Conrad; note taker: Peiyang Song).
15. sanity-test-input.txt: Input file.
18. sanity-test-output.txt: Output file.
19. senna-linux64, senna-osx, senna-win32.exe: executable files for this project.
20. Other .c & .h files: code for this project.
21. data/: training and test data (natural language).
22. embeddings/: trained over natural languages on wikipedia for two months.
23. hash/: hash data for this project.
24. Final presentation/: files related to the fourth (final) presentation, including slides, recordings, images, etc.

## Instruction for codes and applications

Recommended steps:
1. If you have yet to read through the descriptions for each file in this repo, you are highly recommended to go back and review the previous parts first (No. 1).
2. Great! Now you must have got a sense of how each file functions. Then, you are suggested to run the executable files (No. 19) for a clear overview.
3. If you are now interested in the tags that are labeled to the input text, you are encouraged to take a look at the underlying codes for each task (No. 20). Or if you are more curious about how this algorithm works on a deeper level, it would be good to look into the groundbreaking publication NLP from Scratch by Dr. Ronan Collobert (No. 5), on which this project is based.
4. All right. Either way, you should already get some certain understanding of this project. Now, the benchmarks (No. 7 to No. 11) are available for a comparison between this work and previous traditional NLP ones, from which you will see how this work is superior and, as mentioned before, "groundbreaking."
5. So far, you have traveled all through this project's central parts. Your next step is based on your own interest. If you are more interested in the field of NLP, it would be beneficial to follow the classical textbook b Dr. Dan Jurafsky (No. 3) and perhaps the video course from Stanford University (CS224N), which is not included in this repo but available on youtube. Otherwise, in case the deep learning part fascinates you more, you may prefer to follow the book Neural Networks and Deep Learning by Dr. Michael Nielsen, which is not included in this repo but is available on google.
6. Materials of my third and fourth presentations are both included in this repo. The third one concentrates mostly on the NLP parts, and the fourth one incorporates more DL parts. Hope those resources help. :)

## Main reference

1. Dr. Dan Jurafsky and Dr. James H. Martin, Speech and Language Processing (3rd ed. draft), NLP Research Group, Stanford University.
2. Agenda and proceedings, *11th CCF International Conference on Natural Language Processing and Chinese Computing* (NLPCC2022).
3. Dr. Ronan Collobert, "Natural Language Processing (almost) from Scratch", *Journal of machine learning research: JMLR.* 12. ARTICLE (2011): n. pag. Print.
4. Dr. Michael A. Nielsen, "Neural Networks and Deep Learning", Determination Press, 2015.
5. CS224N: NLP with Deep Learning, Prof. Christopher Manning, Department of Linguistics and Computer Science, Winter 2021.
6. CS9: Immediate Python, Prof. Richert Wang, Department of Computer Science and CCS Computing, Winter 2021.
7. Dr. Ronan Collobert, "Deep Learning for Efficient Discriminative Parsing", *International Conference on Artificial Intelligence and Statistics (AISTATS)*, 2011.

**Note**: There is still plenty of other valuable literature that has benefited the author greatly but is not tightly related to this repo. Therefore, the author does not include them in the "Main reference" part here, but will certainly give credit to them in later works or a personal repo. In other words, the reference above includes only materials that have directly helped the author during this project, and will also help you understand elements in this repo better.

## Acknowledgment

This project is supported by the UCSB CMPTGCS 1L class in Fall 2022, advised by Prof. Phill Conrad at UCSB CCS. The overall direction of this project, the recommended NLP textbook, and many practical skills are all thanks to his precious guidance. Also, the author wants to thank Prof. Lei Li at UCSB CoE CS for professionally introducing many NLP resources and cutting-edge views, paving the road for the author to develop his specific project ideas. Finally, the author would like to thank Prof. Tim Sherwood from UCSB CoE, Prof. Richert Wang from UCSB CCS, Laya Pullela from UCSB CCS, and other anonymous supporters for their kind support for this project and beyond.
