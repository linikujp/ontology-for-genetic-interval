Using realism based ontology BFO(Basic Formal Ontology) as its top ontology's framwork, OGI formalized the genomic element by defining an upper class '_genetic interval_'. Not just a sequence, OGI represents gene as an entity with its 3D shape, topography, and primary sequence of DNA is the foundation for it 3D structure.

The ontology can be viewed from URI using http://ontology-for-genetic-interval.googlecode.com/svn/trunk/src/ogi-merged.owl

The **definition** of 'genetic interval' is "the spatial continuous _physical_ entity which contains ordered genomic sets(DNA, RNA, Allele, Marker,etc.) between and including two points (Nucleic Acid Base Residue) that have a liner primary sequence sturcture. It is either a proper part of an chromosome or a RNA molecule or an artificial genetic interval."

The OBI term genetic materialhttp://purl.obolibrary.org/obo/REO_0000826 is under discussion. According to their final definition. The OBI:genetic material can either be the alternative term of genetic interval or a subclass of it. check the discussion here: https://code.google.com/p/ontology-for-genetic-interval/wiki/genetic_material_discussion_in_OBI

The _'genetic sequence'_ is also formalized in OGI, the differences between 'genetic sequence' and 'genetic interval' is that, 'genetic squence' refers to a liner sequence with only primary structure, whereas 'genetic interval' refers to the 3D sequence in reality, which has not only 3D structure, but also need to have the 'genetic sequence' as its primary structure'. From this aspect we make a distinction between a modelled sequence and a real sequence object as realm.

**Synomous** terms are: genetic material interval

**Elucidation** It is genomic, so that protein is not the child of this class. it is continuous, so that neither genome(colletive of chormosomes), nor genotype diploid(collective alleles comes from different chromosomes), nor gene family(collective of genes of same homolog located to different chromosomes) are genomic interval. Whereas gene cluster which are juxtapositioned genes can be subclass of genomic interval. By length, the longest Genomic Interval is the interval with same start point and end point with chromosome, and smallest is when one start point and end point are equal( one residue of DNA or RNA). Interval holds property interval relation.

**Publications**:

1. Yu Lin, Norihiro Sakamoto (2009) “[Genome, Gene, Interval and Ontology](http://cdb-riken.academia.edu/LinYu/Papers/142399/Genome_Gene_Interval_and_Ontology)” _Interdisciplinary Ontology Vol.2 - Proceedings of the Second Interdisciplinary Meeting, Tokyo, Feb. 28th- Mar. 1st, 2009. Page(s):25-34_

2. Yu Lin, Hiroshi Tarui, Peter Simons (2009) “[From Ontology for Genetic Interval(OGI) to Sequence Assembly – Ontology apply to next generation sequencing](http://ceur-ws.org/Vol-559/Poster2.pdf)” _Proceeding of the Semantic Web Applications and Tools for Life Science Workshop, Amsterdam, Nov.20th, 2009._

3. Yu Lin, Peter Simons (2010) “[DNA sequence from below: A Nominalist Approach](https://code.google.com/p/ontology-for-genetic-interval/downloads/detail?name=DNASequencesfromBelow.pdf&can=2&q=)” _Interdisciplinary Ontology Vol.3 - Proceedings of the Third Interdisciplinary Meeting, Tokyo, Feb. 28th- Mar. 1st, 2010. Pages(s):79-88_

**Other ontolgies modeling Gene and DNA sequence**

1. Hiroshi Masuya and Riichiro Mizoguchi (2012) "[An Ontology of Gene](http://ceur-ws.org/Vol-897/session1-paper05.pdf)" _Proceedings of the 3rd International Conference on Biomedical Ontology (ICBO 2012), KR-MED Series Graz, Austria, July 21-25, 2012._

2. Christopher J. Mungall,1 Colin Batchelor, and Karen Eilbeck (2010)"[Evolution of the Sequence Ontology terms and relationships](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3052763/)" _J Biomed Inform. 2011 February; 44(1): 87–93_

3. Robert Hoehndorf1, Janet Kelso and Heinrich Herre (2009) "[The ontology of biological sequences](http://www.biomedcentral.com/1471-2105/10/377)" _BMC Bioinformatics 2009, 10:377._

**Peter Simons' related work**

Peter Simons [Vague Kinds and Biological Nominalism](http://link.springer.com/article/10.1007%2Fs12133-013-0127-0) _Metaphysica. October 2013, Volume 14, [Issue 2](https://code.google.com/p/ontology-for-genetic-interval/issues/detail?id=2), pp 275-282_

**Steve Parker's related work about DNA topography**

Parker SC, Tullius TD. [DNA shape, genetic codes, and evolution](http://www.ncbi.nlm.nih.gov/pubmed/21439813) _Curr Opin Struct Biol. 2011 Jun;21(3):342-7._

Parker SC, Hansen L, Abaan HO, Tullius TD, Margulies EH. [Local DNA topography correlates with functional noncoding regions of the human genome.](http://www.ncbi.nlm.nih.gov/pubmed/19286520) _Science. 2009 Apr 17;324(5925):389-92._