SNP Pack
========

Some C++ code by Dr. Reed Cartwright and his minion
in collaboration with Dr. Eric Stone.

The two functions to know about are

snppack_init: which calculates the prior distributions of genotypes
and major and minor alleles.

snppack_prob: which calculates the joint distribution of genotypes and
major and minor alleles given the read data of one site.  It also
returns a log-weight of the site [ log(P(R)) ] which will be important
to handle when combining information from multiple lineages.
