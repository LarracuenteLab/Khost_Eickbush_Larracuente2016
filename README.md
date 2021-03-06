#Khost, Eickbush and Larracuente. Single molecule long read sequencing resolves the detailed structure of complex satellite DNA loci in Drosophila melanogaster
Pipelines, scripts and data files

#Links to raw reads
Raw PacBio reads from: Kim K, Peluso P, Babayan P, Yeadon PJ, Yu C, Fisher WW, et al. Long-read, whole-genome shotgun sequence data for five model organisms. Scientific data. 2014;1(140045). Epub 11/25/2014. doi: doi:10.1038/sdata.2014.45.
Downloaded accession SRX499318 data from:

https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro1_24NOV2013_398.tgz 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro2_25NOV2013_399.tgz 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro3_26NOV2013_400.tgz 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro4_28NOV2013_401.tgz 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro5_29NOV2013_402.tgz 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/raw/Dro6_1DEC2013_403.tgz

PBcR-BLASR (Celera 8.1) Error corrected reads: http://bergmanlab.ls.manchester.ac.uk/?p=2151

Raw Illumina reads: ENA Accession ERX645969

Miller, D.E., C.B. Smith, R.S. Hawley and C.M. Bergman (2013) PacBio Whole Genome Shotgun Sequences for the D. melanogaster Reference Strain. http://bergmanlab.ls.manchester.ac.uk/?p=1971

#Links to assemblies
Falcon assembly: 
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/reads/dmel_FALCON_diploid_assembly.tgz

Celera 8.1 PBcR haploid Blasr quivered assembly
https://s3.amazonaws.com/datasets.pacb.com/2014/Drosophila/reads/dmel_haploid_assembly.tgz

Celera 8.2 MHAP assembly from:
 Berlin K, Koren S, Chin CS, Drake JP, Landolin JM, Phillippy AM. Assembling large genomes with single-molecule sequencing and locality-sensitive hashing. Nat Biotechnol. 2015;33(6):623-30. doi: 10.1038/nbt.3238. PubMed PMID: 26006009.

Accession GCA_000778455

#Description of supplementary files
File S1: Sample Celera 8.3 MHAP specification file, with default small/haploid genome parameters. Parameters altered in this study were merSize, -k, --num-hashes, and assembleCoverage.

File S2: Sample Celera 8.3 MHAP specification file, with large/diploid genome parameters. Parameters altered in this study were merSize, -k, --num-hashes, and assembleCoverage.

File S3: Sample specification file used to run Canu assembler with 4% error rate

File S4: Sample specification file used to run FALCON

File S5: Spec file used to construct BLASR-corr Cel8.3 assembly

File S6: SLURM script used to construct BLASR-corr Cel8.3 assembly. Note: this script did not appear to properly allocate resources on our cluster, resulting in a long (~17 days) assembly time. Configured properly, assembly should be much faster.

File S7: SLURM file used to run Canu 1.2 using BLASR corrected reads (Canu-corr assembly). This uses the default Canu settings but skips read correction.

File S8: SLURM job handler file used to to run Celera 8.3 assembler

File S9: Custom Repbase repeat library used to annotate assemblies. 

File S10: Perl script used to annotate assembly from BLAST output

File S11: GFF annotation file for the major Rsp locus in the PBcR-BLASR assembly, constructed using custom scripts.

File S12: GFF annotation file for the 1.688 loci in the PBcR-BLASR assembly, constructed using custom scripts.

File S13: GFF annotation file for the minor Rsp locus in the PBcR-BLASR assembly, constructed using custom scripts.
