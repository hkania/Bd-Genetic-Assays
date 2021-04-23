# Bd-Genetic-Assays

Assays link: https://hkania.github.io/Bd-Genetic-Assays/

**Project Abstract**

Amphibian species are declining globally. One major driver of these declines is the worldwide spread of Batrachochytrium dendrobatidis (Bd), a pathogenic fungus known to induce the disease chytridiomycosis in amphibians. Bd can quickly spread across amphibian populations leading to population or even community-level collapses. Such dramatic impact on amphibians necessitates a comprehensive understanding of the emergence and spread of Bd. Molecular data can help reveal pathogen history that cannot be uncovered by field observations alone. Previous work in the Rosenblum lab has developed molecular assays to obtain Bd genetic sequences from amphibian skin swabs, an often overlooked source of pathogen genetic data. Additionally, the Rosenblum lab has generated R scripts to work with genomic sequences for both phylogenetic and population genetic analysis. Such advances in genomic methods have greatly expanded our understanding of Bd both regionally and globally. However, distributing and reproducing methods across the amphibian research community is still a major challenge. While both molecular and data analysis protocols exist, there is no efficient pipeline for broad distribution. Therefore, I developed an open-source platform that combines wet lab protocols and data analysis code developed in the Rosenblum lab. Using both GitHub and RMarkdown, I wrote and compiled R scripts into an interactive, online workspace. This workspace creates a detailed workflow, starting with genomic sequences and resulting in data outputs necessary for phylogenetic and population genetic analysis. It includes example input sequences to walk users through data cleaning, building concatenated amplicon alignments for phylogenetic trees, and calling sequence variants for population genetics. Once established on GitHub, the platform empowers collaborative science by allowing researchers to provide workflow feedback, improve code, and expand the breadth of analyses through novel pipelines. The unique potential of this platform is to enable the amphibian research community to more feasibly apply the method and truly provide open-access science.

**Before You Begin**

When utilizing the [HTML](https://hkania.github.io/Bd-Genetic-Assays/) Genetic Assay Workflows, [clone the repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) to your local computer if you wish to follow-along using the reference files. 

**Citations**
+ Byrne, A. Q., Vredenburg, V. T., Martel, A., Pasmans, F., Bell, R. C., Blackburn, D. C., Bletz, M. C., Bosch, J., Briggs, C. J., Brown, R. M., Catenazzi, A., Familiar López, M., Figueroa-Valenzuela, R., Ghose, S. L., Jaeger, J. R., Jani, A. J., Jirku, M., Knapp, R. A., Muñoz, A., … Rosenblum, E. B. (2019). Cryptic diversity of a widespread global pathogen reveals expanded threats to amphibian conservation. Proceedings of the National Academy of Sciences of the United States of America, 116(41), 20382–20387. https://doi.org/10.1073/pnas.1908289116
+ Byrne, A. Q., Rothstein, A. P., Poorten, T. J., Erens, J., Settles, M. L., & Rosenblum, E. B. (2017). Unlocking the story in the swab: A new genotyping assay for the amphibian chytrid fungus Batrachochytrium dendrobatidis. Molecular Ecology Resources, 17(6), 1283–1292. https://doi.org/10.1111/1755-0998.12675
+ Farrer, R. A., Weinert, L. A., Bielby, J., Garner, T. W. J., Balloux, F., Clare, F., Bosch, J., Cunningham, A. A., Weldon, C., du Preez, L. H., Anderson, L., Pond, S. L. K., Shahar-Golan, R., Henk, D. A., & Fisher, M. C. (2011). Multiple emergences of genetically diverse amphibian-infecting chytrids include a globalized hypervirulent recombinant lineage. Proceedings of the National Academy of Sciences, 108(46), 18732–18736. https://doi.org/10.1073/pnas.1111915108
+ Farrer, Rhys A., Henk, D. A., Garner, T. W. J., Balloux, F., Woodhams, D. C., & Fisher, M. C. (2013). Chromosomal Copy Number Variation, Selection and Uneven Rates of Recombination Reveal Cryptic Genome Diversity Linked to Pathogenicity. PLoS Genetics, 9(8), 1–13. https://doi.org/10.1371/journal.pgen.1003703
+ Longcore, J. E., Pessier, A. P., & Nichols, D. K. (1999). Batrachochytrium Dendrobatidis gen. Et sp. Nov., a Chytrid Pathogenic to Amphibians. Mycologia, 91(2), 219–227. https://doi.org/10.2307/3761366
+ Morgan, J. A. T., Vredenburg, V. T., Rachowicz, L. J., Knapp, R. A., Stice, M. J., Tunstall, T., Bingham, R. E., Parker, J. M., Longcore, J. E., Moritz, C., Briggs, C. J., & Taylor, J. W. (2007). Population genetics of the frog-killing fungus Batrachochytrium dendrobatidis. Proceedings of the National Academy of Sciences, 104(34), 13845–13850. https://doi.org/10.1073/pnas.0701838104
+ O’Hanlon, S. J., Rieux, A., Farrer, R. A., Rosa, G. M., Waldman, B., Bataille, A., Kosch, T. A., Murray, K. A., Brankovics, B., Fumagalli, M., Martin, M. D., Wales, N., Alvarado-Rybak, M., Bates, K. A., Berger, L., Böll, S., Brookes, L., Clare, F., Courtois, E. A., … Fisher, M. C. (2018). Recent Asian origin of chytrid fungi causing global amphibian declines. Science, 360(6389), 621–627. https://doi.org/10.1126/science.aar1965
+ Rosenblum, E. B., James, T. Y., Zamudio, K. R., Poorten, T. J., Ilut, D., Rodriguez, D., Eastman, J. M., Richards-Hrdlicka, K., Joneson, S., Jenkinson, T. S., Longcore, J. E., Parra Olea, G., Toledo, L. F., Arellano, M. L., Medina, E. M., Restrepo, S., Flechas, S. V., Berger, L., Briggs, C. J., & Stajich, J. E. (2013). Complex history of the amphibian-killing chytrid fungus revealed with genome resequencing data. Proceedings of the National Academy of Sciences, 110(23), 9385–9390. https://doi.org/10.1073/pnas.1300130110
+ Stuart, S. N., Chanson, J. S., Cox, N. A., Young, B. E., Rodrigues, A. S. L., Fischman, D. L., & Waller, R. W. (2004). Status and Trends of Amphibian Declines and Extinctions Worldwide. Science, 306(5702), 1783–1786.
+ Wake, D. B., & Vredenburg, V. T. (2008). Are We in the Midst of the Sixth Mass Extinction? A View from the World of Amphibians. Proceedings of the National Academy of Sciences of the United States of America, 105, 11466–11473.


**Dependencies**

R Libraries & Packages (.bib file in docs)
+ [R-adegenet](https://github.com/thibautjombart/adegenet)
+ [R-ape](http://ape-package.ird.fr/)
+ [R-base](https://www.R-project.org/)
+ [R-BiocManager](https://CRAN.R-project.org/package=BiocManager)
+ [R-Biostrings](https://bioconductor.org/packages/Biostrings)
+ [R-colorspace](https://CRAN.R-project.org/package=colorspace)
+ [R-ips](https://CRAN.R-project.org/package=ips)
+ [R-kableExtra](https://CRAN.R-project.org/package=kableExtra)
+ [R-knitr](https://yihui.org/knitr/)
+ [R-muscle](http://www.drive5.com/muscle/)
+ [R-phangorn](https://github.com/KlausVigo/phangorn)
+ [R-r2symbols](https://github.com/oobianom/r2symbols)
+ [R-readxl](https://CRAN.R-project.org/package=readxl)
+ [R-rmarkdown](https://CRAN.R-project.org/package=rmarkdown)
+ [R-seqinr](http://seqinr.r-forge.r-project.org/)
+ [R-seqRFLP](https://CRAN.R-project.org/package=seqRFLP)
+ [R-ShortRead](https://bioconductor.org/packages/release/bioc/html/ShortRead.html)
+ [R-stringr](https://CRAN.R-project.org/package=stringr)
+ [R-tidyverse](https://CRAN.R-project.org/package=tidyverse)
+ [R-XML](http://www.omegahat.net/RSXML)
+ [R-XVector](https://bioconductor.org/packages/XVector)

Command Line
+ [Freebayes](https://github.com/freebayes/freebayes); Garrison E, Marth G. Haplotype-based variant detection from short-read sequencing. arXiv preprint arXiv:1207.3907 [q-bio.GN] 2012
+ [Samtools](http://www.htslib.org/doc/)
+ [BWA](https://github.com/lh3/bwa); Li H. and Durbin R. (2009) Fast and accurate short read alignment with Burrows-Wheeler Transform. Bioinformatics, 25:1754-60. [PMID: 19451168]; Li H. (2013) Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM. arXiv:1303.3997v2 [q-bio.GN].
+ [picard](http://broadinstitute.github.io/picard/)
