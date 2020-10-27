---
title: "Exercise: Write a DMP"
teaching: 15 min
exercises: 0
questions:
- ""
ojectives:
- "Using information provided in a scenario, create a data management plan using the [Data Stewardship wizard](http://dsw.scilifelab.se/)."
keypoints:
- "There are tools that make the writing process easier."
- "Do not feel over-whelmed by the time spent on writing/answering questions, it is time well spent since it will save time in the long-run, just as good project planning does."
- "If you ever are stuck, contact us data stewards at NBIS by sending an email to [data@nbis.se](mailto:data@nbis.se) or ask for a consultation via [our homepage](https://nbis.se/support/supportform/index.php?form=consultation)."
---
## Instructions to get started
Open/download the scenario <link to above text>

Log in to DS wizard with your university credentials


Click on Projects in left-hand margin 


 

Click on Create in top right corner, name the project <your_name>_test_DMP, select knowledge model named Intro DMP course module… and click on Save

> ## Scenario
>
> **VEGFR2 Y949F mutation**
> Principal investigator Sam Smith (sam.smith@example.com) at Uppsala University 
> and [you; as a researcher and contact person], wish to do RNA sequencing of 
> lung tissue from transgenic mice in order to investigate the effect of a single 
> tyrosine to phenylalanine exchange in the endothelial receptor VEGFR2 at 
> position Y949. Dr Smith has applied for funding at Vetenskapsrådet. The project 
> is planned to start 2021-01-01 and continue throughout the year. [you] will attend 
> the course ‘Introduction to data management practices’ given by NBIS in order to 
> ensure the data management quality.
> 
> The RNA sequencing will be done at the national sequencing facility NGI on an Illumina
> HiSeq 2500 sequencer, a well described and known machine. There will be 3 replicates
> each of the wild-type and mutant, producing .bam files with a total size of ~70 GB.  
> In addition to the sequence datasets, the sequences will be mapped to the reference 
> genome of Mus musculus, GRCm38 (mm10), available at 
> [https://www.ncbi.nlm.nih.gov/assembly/GCF_000001635.20/](https://www.ncbi.nlm.nih.gov/assembly/GCF_000001635.20/)
> 
> In order to ensure experiment quality, calibrating measurements and repeat samples will
>  be done. The steps of the analysis will be documented using R Notebooks. The research 
> team will use the MINSEQE (Minimal Information about a high throughput SEQuencing 
> Experiment) metadata standard, since this is the standard used by ENA which will 
> simplify the submission process. In addition, the file organisation and naming 
> conventions will be documented in a README text file that will be put in the root 
> folder of the project, and a dictionary of the samples metadata will be created.
> 
> The analysis will be done by the research group at the SNIC center Uppmax, for which 
> a project will be applied for. 
> 
> This project adheres to Open Science and FAIR principles, so the sequencing datasets 
> will be published in European Nucleotide Archive (ENA) at the time of arrival, and will 
> be put under an embargo for one year until the analysis has been done and a paper has 
> been submitted to a publisher. This way the datasets will be backed-up at a remote 
> location, separate from the Uppmax account.
{: .solution}

{% include links.md %}