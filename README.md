# Mangrove: A community bioinformatics project towards energy efficiency

The ‘Carbon Footprint’ of bioinformatics is not, at present, a concern publicly addressed during the development of algorithms, software and broader workflows. This has recently been highlighted by Grealey et al.(1) in the first systematic study of carbon emissions resulting from common bioinformatics applications such as genome assembly, genome-wide association studies (GWAS), transcriptomic analysis, metagenomics, phylogenetics and molecular simulations. 

Straightforward choices between comparable software can have an enormous impact on CO2 output. Metagenome assembly of 100 soil samples(2) with MetaVelvet k101v-1.2.01(3) resulted in 14 kgCO2e, whereas MEGAHITv1.0.3(4) and metaSPAdesv3.8.0(5) resulted in 77 and 186 kgCO2e respectively(1). This is the difference in kilometres driven (EU) of 82 for MetaVelvet, 439 for MEGAHIT and 1,065 for metaSPAdes. The latter, the equivalent of driving from Paris to Berlin or Prague to Sarajevo. 

Another fundamental analytical step in much of biology is phylogenetics, where we also see a steep increase in energy cost. For example, one study performed over 670,000 tree inferences on approximately 45,000 single-gene alignments(6) resulting in 3,656 kgCO2e, or 20,371km driven(1). Another phylogenetic analysis, using ExaML, applied to a 322Mbp alignment of orthologues(7), resulted in 4,769 kgCO2e or 24,983km driven(1); the same as a trip from Paris to Prague, via Zimbabwe. 

This project aims to mitigate the energy-expense of bioinformatics by:
1.	Develop workflows from existing software that avoid redundancy
2.	Update existing software and dependencies
3.	Develop new algorithms that will reduce the energy demand of key bioinformatics analyses

The quality and ease of analysis need not be negotiable: the aim is to arrive in Prague as quickly and comfortably as possible, minus the detour. The small sample of studies cited here are fantastic demonstrations of the scale and sophistication of biological data analysis. We intend to make it automatic for users to mitigate redundancy or wastefulness, while supporting the increasing use of bioinformatic analysis.



### How Mangrove works: 

-	What is Mangrove?  
Mangrove is a collection of bioinformatics workflows, new software and benchmarking tools to enable software choices that are energy efficient. 

-	How do I use Mangrove?  
Find the code you would like to run for your analysis through the wiki and clone the repository. 

- How to benchmark energy efficiency?
Your algorithm's energy efficiency can be estimated with the green algorithm calculator (https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202100707, http://www.green-algorithms.org/) 
 
-	Who can contribute and how?  
Absolutely anyone may contribute to existing projects via pull requests. Code edits towards usability, recompiling, bug fixes etc. are also welcome! To begin a project, or suggest new analysis please submit your ideas via issues. 

-	Can I publish my contributions?   
Yes! Feel free to publish anything you’ve found or developed while contributing. Please let us know about any publications so we can list them. 


<br /><br /><br /><br /><br />

1.	Grealey, J. et al. The Carbon Footprint of Bioinformatics. Mol. Biol. Evol. (2022). doi:10.1093/molbev/msac034
2.	Vollmers, J., Wiegand, S. & Kaster, A. K. Comparing and evaluating metagenome assembly tools from a microbiologist’s perspective - Not only size matters! PLoS ONE (2017). doi:10.1371/journal.pone.0169662
3.	Namiki, T., Hachiya, T., Tanaka, H. & Sakakibara, Y. MetaVelvet: An extension of Velvet assembler to de novo metagenome assembly from short sequence reads. Nucleic Acids Res. (2012). doi:10.1093/nar/gks678
4.	Li, D., Liu, C. M., Luo, R., Sadakane, K. & Lam, T. W. MEGAHIT: An ultra-fast single-node solution for large and complex metagenomics assembly via succinct de Bruijn graph. Bioinformatics (2015). doi:10.1093/bioinformatics/btv033
5.	Nurk, S., Meleshko, D., Korobeynikov, A. & Pevzner, P. A. MetaSPAdes: A new versatile metagenomic assembler. Genome Res. (2017). doi:10.1101/gr.213959.116
6.	Zhou, X., Shen, X. X., Hittinger, C. T. & Rokas, A. Evaluating fast maximum likelihood-based phylogenetic programs using empirical phylogenomic data sets. Mol. Biol. Evol. (2018). doi:10.1093/molbev/msx302
7.	Jarvis, E. D. et al. Whole-genome analyses resolve early branches in the tree of life of modern birds. Science (80-. ). (2014). doi:10.1126/science.1253451


