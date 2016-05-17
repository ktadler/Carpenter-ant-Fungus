# Carpenter-ant-Fungus
Work plan

- Download data from NCBI : SRA SRP057573
   succeded with the wget command on command line,
   each file sepparately
   
- Download reference genome
  Carpenter: Charisa says: Camponotus floridanus genome. Look at their paper
  (it’s cited in our paper so you can find it in the references) for the same type of number.
  http://science.sciencemag.org/content/351/6268/aac6633.long
  Fungus: This Whole Genome Shotgun project has been deposited at DDBJ/EMBL/GenBank
  under the accession LAZP00000000.
  The RNA-Seq expression dataset is available at the NCBI’s Gene Expression Omnibus
  under the accession code GSE68176.
  
- Build indecies 
  First have to convert bgff format to gtf
  should try following tools:
  - Galaxy BGFF to GFF3 -> GFF3 to GTF https://galaxy.cbio.mskcc.org/ -checked this. have to install tools and stuff on PC. bad way 
  - pipeline for cat genome https://github.com/riverlee/genbank2gtf -  checked this.have to change the pipeline for our organisms
  - http://genome.crg.es/~lpryszcz/scripts/gb2gtf.py - sounds nice. should try this

