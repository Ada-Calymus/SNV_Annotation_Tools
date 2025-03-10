# SNV_Annotation_Tools
Useful tools for variant annotation

[ONCOFUSE] (https://fusionhub.persistent.co.in/oncofuse.html)
Oncofuse can be used to annotate breakpoints of structural rearrangements and identify fusion genes. It is also..."designed to predict the oncogenic potential of fusion genes found by Next-Generation Sequencing in cancer cells. It is a post-processing step that tries to validate in-silico the predictions made by fusion detection software. Oncofuse is NOT a fusion detection software, its goal is NOT to identify fusion sequences, but to assign a functional prediction score (oncogenic potential, i.e. the probability of being 'driver' events) to fusion sequences identified by other software such as Tophat-fusion, fusioncatcher or STAR."

[SNP-Nexus] (https://www.snp-nexus.org/v4/)
SNPnexus is a web-based variant annotation tool designed to simplify and assist in the selection and prioritisation of known and novel genomic alterations.
Input: multiple types, including VCF, web-based
Output: annotated files, CSV, TSV, HTML, graphics

[GEMINI] (https://gemini.readthedocs.io/en/latest/)
GEMINI (GEnome MINIng) is a flexible framework for exploring genetic variation in the context of the wealth of genome annotations available for the human genome. By placing genetic variants, sample phenotypes and genotypes, as well as genome annotations into an integrated database framework, GEMINI provides a simple, flexible, and powerful system for exploring genetic variation for disease and population genetics. Using the GEMINI framework begins by loading a VCF file (and an optional PED file) into a database. Each variant is automatically annotated by comparing it to several genome annotations from source such as ENCODE tracks, UCSC tracks, OMIM, dbSNP, KEGG, and HPRD. All of this information is stored in portable SQLite database that allows one to explore and interpret both coding and non-coding variation using “off-the-shelf” tools or an enhanced SQL engine. Note: only supports hg19. 
Input: VCF, pedigree file (optional)
Output: SQL database, customizable 

[ANNOVAR] (http://annovar.openbioinformatics.org/en/latest/)
command-line tool, supports SNPs, INDELs, CNVs and block substitutions, provides wide variety of annotation techniques, utilizes RefSeq, UCSC Genes, and the Ensembl gene annotation systems; can compare mutations detected in dpSNP or 1000 Genomes Project.
Input: VCF, ANNOVAR input format (simple text-based format); can convert other formats into ANNOVAR input format
Output: VCF (if input VCF), output file with multiple columns, tab-delimited output file

[wANNOVAR] (http://wannovar.usc.edu/)
web-based access to ANNOVAR

[PolyPhen-2] (http://genetics.bwh.harvard.edu/pph2/)
Polymorphism Phenotyping; Web application; predicts impact of amino acid substitution on protein; Calculates Bayes posterior probability
Input: FASTA

[SIFT] (http://sift.jcvi.org/)
predicts how an amino acid substitution will affect protein function; Based on degree of conservation of amino acid residues- collected though PSI-BLAST; Standalone or web app program;
Input: Uniprot ID or Accession, Go term ID, Function name, Species Name or ID, etc

[snpEff] (http://snpeff.sourceforge.net/)
Genetic variant annotation and effect prediction toolbox; integrated with Galaxy, GATK, and GNKO; can annotate SNPs, INDELs, and multiple-nucleotide polymorphisms; categorizes effects into classes by functionality; Standalone or Web app;
Input: VCF, BED
Output: VCF (with new ANN field, also used in ANNOVAR and VEP), HTML summary files

[SnpSIFT] (http://snpeff.sourceforge.net/SnpSift.html)
Filter annotated files; Part of SnpEff main distribution; one variants have been annotated, this can be used to filter your data to find relevant variants

[VAAST 2] (http://www.yandell-lab.org/software/vaast.html)
Variant Annotation, Analysis, and Search Tool; probabilistic search tool for identifying damage genes and the disease causing variants; can score both coding and non-coding variants; Four tools: VAT (Variant annotation tool), VST (Variant Selection Tool), VAAST, pVAAST (for pedigree data); updated April 2015
Input: FASTA, GFF3, GVF
Output: CDR (condenser file), VAAST file (both unique to VAAST)

[VEP] (http://useast.ensembl.org/info/docs/tools/vep/index.html?redirect=no)
Ensembl Variant Effect Predictor; determines effect of variants on genes, transcripts, and protein sequence; uses SIFT and PolyPhen
Input: Coordinates of variants and nucleotide changes; whitespace- separated format, VCF, pileup, HGVS
Output: VCF, JSON, Statistics

[KOBAS] (http://kobas.cbi.pku.edu.cn/)
Gene ontology, annotation, and enrichment tool with vizualization funtions on webserver. "The annotation module accepts the gene-list as input, including IDs or sequences, and generates annotations for each gene based on multiple databases of pathways, diseases, and GO information . The enrichment module gives an answer about which pathways and GO terms are statistically significantly associated with the input gene list or expression. Two different enrichment analyses are available, named gene-list enrichment and exp-data enrichment." doi.org/10.1093/nar/gkab447

[CCAS] (https://ngdc.cncb.ac.cn/ccas/#/home)
Cancer genome Consensus Annotation System: A one-stop and comprehensive annotation system for the individual patient at multi-omics level. CCAS integrates 20 widely recognized resources in the field to support data annotation of 10 categories of cancers covering 395 subtypes.

