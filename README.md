# Community Phen Gen

*Table of Contents*

1. [**Background**](https://github.com/NCBI-Hackathons/Community_PhenGen#background)
2. [**Methods**](https://github.com/NCBI-Hackathons/Community_PhenGen#methods)
3. [**Results**](https://github.com/NCBI-Hackathons/Community_PhenGen#results)
4. [**Members**](https://github.com/NCBI-Hackathons/Community_PhenGen#members)
5. [**Documentation**](https://github.com/NCBI-Hackathons/Community_PhenGen#documentation)

We are creating a program that will pull out all pathogenic or likely pathogenic SNPs that are currently included on the chips that are used for some common direct to consumer genetic/ancestry tests. This program can help us identify whether people who run their raw data through a database such as Promethease may find that they have a pathogenic or likely pathogenic SNP in any of the Porphyria genes. 

Collecting the experiences of people who are identified from the general population in this fashion would be valuable to find out how they are following up with this information. Although most of these individuals will never develop symptoms (due to the low penetrance of these genes), it may prove useful to see if these individuals would enroll in future studies trying to compare those with latent and active porphyria in order to identify modifying genes and environmental factors that contribute to the phenotype. Furthermore, some of these results are expected to be false positives and this might allow the participants to access diagnostic testing and verify their genotype.

One possible way to recruit these individuals would be to add a link to the research database (and study consent) on SNPedia for each of the pathogenic variants of interest. To our knowledge, nobody has tried to recruit in this fashion and it may work because people who use these databases to interpret their raw data are likely to be interested in additional information and therefore may be willing to participate in research studies.

### Background:
*Data-driven discovery of rare disease determinants*

Porphyria is a group of eight inherited genetic disorders that arise when the body is unable to synthesize heme used to transport oxygen throughout the body. This negatively affects the skin and/or nervous system causing symptoms including extreme abdominal and chest pain, skin blistering, vomiting, confusion, constipation, fever, high blood pressure, and possibly leading to paralysis, low blood sodium levels, and seizures.

Porphyria is divided into two main types, acute and cutaneous, depending on the most commonly experienced symptoms. Acute Porphyrias typically present with attacks of symptoms, like intense abdominal pain or skin blistering, which become more severe over several days. Cutaneous Porphyrias may result in skin blistering, redness, scarring, and pain when exposed to the sun.

Likely affecting 1 to 100 people in every 50,000, Porphyria is a rare disease which on average takes 10-15 years to diagnose following the onset of symptoms. Once Porphyria is recognized diagnostic testing can be performed via blood, urine, stool and genetic testing.

### Methods:
*Implementation*

To build a database of pathogenic or likely pathogenic SNPs we have sourced Ancestry and 23andMe data (Illumina OmniExpress & Illumina GSA microarray chips) and compared to ClinVar entries with an output of the rsid, the SNP location, and the level of pathogenicity. This will be combined with a database containing phenotype, genetic and symptom information of people with Porphyria and their family to try to capture data on asymptomatic people.

Our system currently consists of a cloud database built upon MongoDB Community Edition, and a web server run through NGINX. The entire system can be generated by using two lines of code.

*Operation*

### Results:

### Members:
Rays Jiang - [ray-jiang](https://github.com/ray-jiang) - Jiang2@health.usf.edu 

Renee Fonseca - [reneemf](https://github.com/reneemf) - fonsecarenee1@gmail.com

Minh Pham - [minhhpham](https://github.com/minhhpham) - minhpham@mail.usf.edu 

Deborah Cragun - dcragun@health.usf.edu 

Luis Tañon Reyes - luistanon@mail.usf.edu

Alex Dean - [deansmacked](https://github.com/deansmacked) - daviddean@health.usf.edu

Krishna Sharma - sharmak@mail.usf.edu

### Documentation:
