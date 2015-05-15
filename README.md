Using realism based ontology BFO(Basic Formal Ontology) as its top ontology's framwork, OGI formalized the genomic element by defining an upper class 'genetic interval'. Not just a sequence, OGI represents gene as an entity with its 3D shape, topography, and primary sequence of DNA is the foundation for it 3D structure.

The definition of 'genetic interval' is "the spatial continuous physical entity which contains ordered genomic sets(DNA, RNA, Allele, Marker,etc.) between and including two points (Nucleic Acid Base Residue) that have a liner primary sequence sturcture. It is either a proper part of an chromosome or a RNA molecule or an artificial genetic interval."

The OBI term genetic material http://purl.obolibrary.org/obo/REO_0000826 is under discussion. According to their final definition. The OBI:genetic material can either be the alternative term of genetic interval or a subclass of it. check the discussion here: https://code.google.com/p/ontology-for-genetic-interval/wiki/genetic_material_discussion_in_OBI

The 'genetic sequence' is also formalized in OGI, the differences between 'genetic sequence' and 'genetic interval' is that, 'genetic squence' refers to a liner sequence with only primary structure, whereas 'genetic interval' refers to the 3D sequence in reality, which has not only 3D structure, but also need to have the 'genetic sequence' as its primary structure'. From this aspect we make a distinction between a modelled sequence and a real sequence object as realm.

Synomous terms are: genetic material interval

#####Elucidation

It is genomic, so that protein is not the child of this class. it is continuous, so that neither genome(colletive of chormosomes), nor genotype diploid(collective alleles comes from different chromosomes), nor gene family(collective of genes of same homolog located to different chromosomes) are genomic interval. Whereas gene cluster which are juxtapositioned genes can be subclass of genomic interval. By length, the longest Genomic Interval is the interval with same start point and end point with chromosome, and smallest is when one start point and end point are equal( one residue of DNA or RNA). Interval holds property interval relation.
