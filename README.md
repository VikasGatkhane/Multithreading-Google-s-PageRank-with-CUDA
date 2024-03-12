# Multithreading Google's PageRank with CUDA

Parallelizing Google's PageRank algorithm in C++ with CUDA framework on GPU. Conducted some experiments, tried new ideas. .

We use the Internet to search for information on a daily basis. We use
search engines to find out the useful information from the vast Internet.
This is possible because the search engines are using a heuristic called
PageRank. It is nothing but a value to a web page that is assigned by a
PageRanking algorithm. This algorithm scans all possible webpages and
then calculates the rank accordingly given by a formula. Search engines
show results according these ranks, which stand for the popularity of the
page. The lower is the rank, more popular the page is. Traditional approaches use multi-CPU architecture and this is not a very good choice
due to the communication overhead and the low processing power of CPU
compared to GPU. Hence, designing a PageRanking algorithm efficiently
modified for parallel GPU-CPU environment that achieves higher accuracy and consumes lesser time to evaluate the PageRank exact rank vector
even for large-scale webgraphs.
