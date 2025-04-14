---
editor_options: 
  markdown: 
    wrap: 72
---

# **Results** {#sec-results}

```{=html}
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-LKV6J2QECN"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-LKV6J2QECN');
</script>
```
## **Core collection establishment** {.unnumbered}

To enhance the statistical accuracy and efficiency of subsequent
analyses, we established a core collection of soybeans using a
combination of genetic distance metrics and an advanced maximization
strategy. Our core collection consists of 52 vegetable-type soybeans and
192 grain-type soybeans, selected from a total of 2,394 soybean
accessions (107 vegetable and 2,287 grain soybeans), representing 10.2%
of the entire collection (~~Supplementary Table 3~~). This approach not
only exemplifies the effectiveness and representativeness achieved
through the integration of phenotypic and genotypic data but also
ensures the retention of 100% genetic diversity and over 98% allelic
coverage (~~Supplementary Table 4~~). Additionally, other diversity
indices, such as VD% of \< 23.79% and VR% of \> 106.68%, further support
the robustness and reliability of the core collection. Evaluation
statistics, meeting predefined criteria with a MD% of \< 20% and a CR%
of \> 80% (Hu et al. 2000) (~~Supplementary Table 5~~), provide further
affirmation of the core collection’s quality. PCA scatter plots visually
confirm that the core subset maintains the underlying data structure and
variations, validating its ability to preserve the diversity present in
the original population (**Fig. 2B-C** and **Supplementary Fig. 2**).

#### **⚠️NOTE: Some data in this book is unpublished; therefore, certain results may be uncompleted, simulated, and some plots may appear blurred.** {.unnumbered}

**[[FIGURE 2; inaccessible]{.smallcaps}]**

> **Fig. 2 Genomic features and genetic architecture of the soybean core
> collection.** **A** Circos plot illustrating the genomic
> characteristics of soybeans. The outer gray track represents the
> length of each of the 20 chromosomes (Mb). I, Distribution of soybean
> genes. II, Distribution of 87k SNPs analyzed in the present study.
> III, Minor allele frequency (MAF). IV, nucleotide diversity π. V, GC
> content. Gene and SNP density were calculated as the ratio of SNPs per
> 200 kb. Other parameters were estimated using a sliding window with a
> window size of 50 kb and a step size of 10 kb. The red lines for MAF
> and nucleotide diversity π indicate the top 1%. GC content values
> below 75 were colored in purple, while values above 75 were colored in
> brown. **B** Genetic structure of the grain soybean germplasm using
> principal components analysis (PCA). Brown dots represent the 192 core
> accessions, while gray dots denote the 2,095 non-core accessions.
> **C** Genetic structure of the vegetable soybean germplasm using PCA.
> Green dots represent the 52 core accessions, while gray dots denote
> the 55 non-core accessions

**[[SUPPLEMENTARY FIGURE 2; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 2** Genetic structure of the soybean germplasms
> based on phenotypic data. **A** Genetic structure of the grain soybean
> germplasm (EC~G~, 2,287 accessions) and the core collection (CC~G~,
> 192 accessions) using principal component analysis (PCA). Brown dots
> represent the CC~G~, and gray dots represent the difference of EC~G~
> from CC~G~ (EC~G~\\CC~G~). **B** Genetic structure of the vegetable
> soybean germplasm (EC~V~, 107 accessions) and the core collection
> (CC~V~, 52 accessions) using PCA. Green dots represent the CC~V~, and
> gray dots represent the difference of EC~V~ from CC~V~ (EC~V~\\CC~V~)

Furthermore, our core accessions encompass representatives from diverse
genetic backgrounds, constituting a valuable reservoir of germplasms.
For instance, the vegetable soybean variety ‘Ryokkoh’ (Vegsoy_023) from
Japan has been used as a parent genotype to Taiwan’s breeding programs
for decades. Noteworthy varieties such as ‘Kaorihime’ (Vegsoy_008),
‘Blue Side’ (Vegsoy_010), and ‘Chakaori’ (Vegsoy_043) have been
recognized for their large seeds and abundance of aromatic components
(Bagherzadi et al. 2020; Guo et al. 2022; Huang et al. 2022). Moreover,
the 192 grain soybeans from 29 countries worldwide constitute a diverse
and highly heterogeneous pool (**Fig. 3A**). Consequently, our
established core collection served as the foundation for downstream
analyses, including population structure analysis and identification of
selection footprints.

**[[FIGURE 3; inaccessible]{.smallcaps}]**

> **Fig. 3 Phylogenetic relationship and structure analysis of soybean
> core accessions. A** Geographic distribution of the 244 core
> accessions, with varying shades representing different accession
> quantities. **B** The unweighted pair group method with arithmetic
> mean (UPGMA) phylogenetic tree of 244 accessions. Different colors
> denote distinct groups defined by the discriminant analysis of
> principal components (DAPC) algorithm, accompanied by representative
> images of soybean seeds in each group: Green for Group I (‘Blue
> side’), Purple for Group II (‘PI 192867’), Yellow for Group III
> (‘Shelby’), Red for Group IV (‘PI 323574’), and Blue for Group V (‘PI
> 62248’). Images of soybean seeds were sourced from the NPGRC (NPGRC
> 2023). **C** Plot of Bayesian information criterion (BIC)values
> against the number of groups, indicating the minimum BIC value at K =
> 5, beyond which BIC increases. **D** Genetic variances explained by
> eigenvalues of the principal components analysis (PCA) as a
> preliminary step for DAPC. The x-axis (bottom) represents the number
> of PCs, while the y-axis (left) represents the proportion of variance
> (%). The secondary y-axis (right) represents the cumulative proportion
> (%). The first four PCs were retained following Cattell’s rule, as per
> guidelines provided by Thia (2023). **E** Bar plot showing the
> percentage of membership probability for each group identified at K =
> 5. **F** Scatter and density plots of DAPC. Each dot represents an
> accession, with inertia ellipses indicating groups. The densities of
> accessions on the first (x-axis) and second (y-axis) linkage
> disequilibrium are depicted in different colors for each group

------------------------------------------------------------------------

## **Population structure** {.unnumbered}

Population structure was conducted on the core accessions using
genotypic data obtained from the Axiom^®^ SoyaSNP180K chip array,
resulting in 78,189 high-quality SNPs meeting stringent criteria (MAF \>
0.05, heterozygosity \< 0.10, and missing rate \< 0.10). Of these SNPs,
55,871 (71%) were located within genic regions, covering approximately
48.71% (27,076 out of 55,589) of all soybean chromosomal genes
documented in the SoyBase under assembly version Wm82.a2.v1 (Brown et
al. 2021) (~~Supplementary Table 6~~). SNP density and diversity indices
for the 78k SNPs across the 244 core accessions were depicted in **Fig.
2A**. Our findings indicate that SNP markers were uniformly distributed
across all chromosomes, demonstrating consistent levels of SNP
polymorphism. The average SNP spacing was 12,139 bp, with variation
ranging from 9,626 bp on chromosome 17 to 16,837 bp on chromosome 1
(~~Supplementary Table 7~~). Across all chromosomes, the average missing
rate, MAF, nucleotide diversity π, and GC content were 0.12%, 0.24,
0.33, and 0.51, respectively (~~Supplementary Table 8~~ **and
Supplementary Fig. 3**). Furthermore, the coefficient of variation (CV%)
of nucleotide diversity π among chromosomes in vegetable soybeans (77%)
was notably higher than that observed in grain soybeans (38%),
indicating disparate domestication and selection patterns among distinct
chromosomes in vegetable soybeans.

**[[SUPPLEMENTARY FIGURE 3; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 3** Summary of polymorphism statistics for 78k
> SNP data: **A** Minor allele frequency (MAF), **B** Missing rate of
> each SNP marker, **C** Nei’s genetic diversity, **D** Polymorphic
> information content (PIC) in the present study

To evaluate the population structure among the 244 core accessions, we
conducted UPGMA phylogenetic tree construction (**Fig. 3B**) and DAPC
using a set of 78k SNPs (**Fig. 3C-F**). The accessions were divided
into five distinct groups, optimized to maximize the genetic distance
between groups and minimize within-group variation based on the BIC
value (**Fig. 3C**). Group I primarily consisted of vegetable soybeans,
with 28 accessions from Japan and 13 from Taiwan, while Groups II to V
predominantly included grain soybeans sourced from China (38), the
United States (23), Japan (19), and other 26 countries (~~Supplementary
Table 9~~). The results suggest a genetic affinity in vegetable soybean
germplasm between Taiwan and Japan. Conversely, grain accessions from
China exhibited a dispersed distribution across four distinct groups,
indicating notable heterogeneity in Chinese grain soybean germplasm.
Moreover, the first linear discriminant function effectively
discriminated Group I from other clusters, while the second linear
discriminant function specifically distinguished Group II and Group V
(**Fig. 3F** and **Supplementary Fig. 4**). These observations were
further elucidated by the membership probabilities of each group; Group
I demonstrated the lowest proportion of admixed accessions, whereas
Group III exhibited the highest level of admixture among the five groups
(**Fig. 3E**). The distinct clustering patterns observed between
vegetable and grain soybeans in the core collection suggest differential
selection histories and potential selective signals.

**[[SUPPLEMENTARY FIGURE 4; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 4** Mean values of discriminant functions
> corresponding to each group

To comprehensively understand genetic relationships and population
structure within the soybean core collection, we employed distinct SNP
selection criteria based on MAF filtering and LD correlation to
investigate their impact on population structure delineation. We
conducted a comparative DAPC analysis using three datasets: (1) a
dataset containing both common (i.e. MAF ≥ 0.05) and rare variants (i.e.
MAF \< 0.05) (147k SNPs), (2) a subset comprising common variants only
(78k SNPs), and (3) a further LD-refined subset based on common variants
with LD correction (r^2^ \< 0.5) (13k SNPs). Across these datasets, all
244 core accessions consistently clustered into five groups with 91%
clustering consistency (**Supplementary Fig. 5**). Notably, the DAPC
model based on the 78k SNP dataset demonstrated the highest stability,
explaining the most inter-group variability (82.87%) and exhibiting
superior discrimination of inter-group variations. Consequently, the 78k
SNP dataset was selected for downstream analyses. **Supplementary Fig.
6** presents a three-dimensional interactive scatter plot illustrating
the population architecture among the 244 core accessions using the 78k
SNP dataset.

**[[SUPPLEMENTARY FIGURE 5; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 5** DAPC cluster analysis results using different
> SNP datasets: **A** 147k SNPs containing both common (MAF ≥ 0.05) and
> rare (MAF \< 0.05) variants, **B** 78k SNPs consisting solely of
> common variants, and **C** 13k SNPs with additional LD-correction
> (r^2^ \< 0.5) for common variants

**[[SUPPLEMENTARY FIGURE 6; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 6** Three-dimensional interactive scatter plot
> depicting population architecture among 244 core accessions utilizing
> a 78k SNP dataset

------------------------------------------------------------------------

## **Genetic diversity** {.unnumbered}

Assessment of genetic diversity within the five groups of Taiwanese
soybean core accessions, revealed Group I to exhibit the lowest genetic
diversity (π = 0.19), whereas other groups ranged from 0.29 to 0.36
(**Fig. 4A** and ~~Supplementary Table 10~~). Notably, the population
differentiations between Group I and other groups (*F*~ST~ = 0.20-0.30)
were considerably higher compared to those observed among other pairs
(*F*~ST~ = 0.03-0.13) (**Fig. 4A** and ~~Supplementary Table 11~~).
Furthermore, Group I displayed a larger number of fixed alleles (24,444)
than other groups (313-5,878) (**Fig. 4B**). Given that Group I
primarily consists of vegetable soybeans, the observed lower genetic
diversity, increased differentiations, and greater distance from other
groups suggest the present of a distinct and potentially specialized
genetic profile within this subpopulation. These findings suggested that
vegetable soybeans may have experienced strong selection pressure for
specific traits, resulting in reduced diversity and distinct genetic
differentiation compared to grain soybeans.

**[[FIGURE 4; inaccessible]{.smallcaps}]**

> **Fig. 4 Analysis of genetic diversity, differentiation, and linkage
> disequilibrium (LD) decay among five groups (or two types) of soybean
> core accessions.** **A** Statistics analysis of genetic diversity and
> population differentiation. The size of each circle corresponds to the
> value of nucleotide diversity π, while the values displayed between
> pairs of groups indicate population divergence (*F*~ST~). **B**
> Distribution of fixed alleles within each of the five groups. **C** LD
> Decay across the genome in five groups of soybeans. **D** LD Decay
> comparison between two types of soybeans (grain and vegetable
> soybeans). **E-F** Results of analysis of molecular variance (AMOVA)
> for five groups (or two types) of soybean core accessions. ^\*\*\*^,
> *p*-value \< 0.001

A comprehensive analysis of LD decay rates and AMOVA were undertaken to
deepen our understanding of evolutionary processes and population
stratification. Notably, LD decay rates in vegetable soybeans and Group
I (61kb and 60kb, respectively) were considerably slower than those
observed in grain soybeans and Groups III to V (53kb and 57-62kb,
respectively, **Fig. 4C-D**). This observation suggests that vegetable
soybeans may have undergone more intensive selective processes and
domestication compared to other soybeans. The AMOVA results revealed
that 15.06% of the total genetic variation was shared among the five
groups, whereas 83.19% was shared among individuals within groups, with
only 1.75% shared within individuals (**Fig. 4E** and ~~Supplementary
Table 12~~). These findings indicate a significant (*p* \< 0.001)
population structure across all levels of population strata
(**Supplementary Fig. 7)**. Likewise, a notably similar pattern of
genetic differentiation was observed between vegetable soybeans and
grain soybeans. (**Fig. 4F**, ~~Supplementary Table 12~~ and
**Supplementary Fig. 7**), highlighting distinct human selection
resulting from their agricultural utilization.

**[[SUPPLEMENTARY FIGURE 7; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 7** Results of analysis of molecular variance
> (AMOVA). **A** AMOVA among the five groups. **B** Significance test of
> all levels of population strata among the five groups. The histograms
> depict the distribution of the randomized strata, while the black line
> represents the given genetic variance components. **C** AMOVA among
> two types of soybeans (grain and vegetable soybean). **D**
> Significance test of all levels of the population strata among two
> types of soybeans. ^\*\*\*^, *p*-value \< 0.001

------------------------------------------------------------------------

## **Selection signatures** {.unnumbered}

To investigate the genetic foundation driving the selection of vegetable
soybeans within the breeding program, we utilized the *pcadapt*
algorithm, integrating PCA with correlation analysis, to identify loci
associated with population structure and potential selection signals
within the 78k SNP dataset. By setting the parameter K = 1 to enhance
differentiation between vegetable soybeans and grain soybeans
(**Supplementary Fig. 4**), 159 significant selection signatures (SNP
loci) and 67 potential selection regions were detected across 17
chromosomes, collectively spanning 4.49 Mb (0.34%) of the soybean genome
(**Fig. 5A** and~~Supplementary Table 13~~). These findings suggest
targeted breeding efforts focusing on specific genome loci associated
with desirable traits such as yield or quality attributes, in vegetable
soybeans.

**[[FIGURE 5; inaccessible]{.smallcaps}]**

> **Fig. 5 Genomic selection signatures in 244 soybean accessions. A**
> Manhattan plot depicting selection signatures identified for
> discerning genomic differentiation between vegetable soybeans and
> grain soybeans using *pcadapt* algorithms. The red dashed line
> corresponds to the 0.5% false discovery rate threshold. **B**
> Candidate gene for *GmXXXXX* (*Glyma.XXGXXXXXX*). **C** Candidate gene
> for *GmXXXXX* (*Glyma.XXGXXXXXX*). The top of each panel displays the
> selection region of the peak SNP (AX-XXXXXXXX and AX-XXXXXXXX),
> indicated by a vertical dashed line. The color of each SNP reflects
> its LD (*r*^2^) value with the peak SNP, as illustrated in the color
> intensity index on top. The bottom of each panel shows genes within
> the selection region of the peak SNP, denoted by orange boxes. **D**
> Circos plot illustrating genomic selection signatures. I, Distribution
> of soybean genes. II, Distribution of previously reported quantitative
> trait loci (QTLs) of genome-wide association study. III,
> -log~10~(*p*-value) for selection signatures association with
> vegetable soybean improvement. IV, Distribution of detected 67
> selection regions. V, Links representing selection regions overlapped
> with QTL with similar functions. Red, yellow, blue, yellow, and green
> links connect regions overlapping with QTL associated with
> morphological traits, physiological traits, reproductive traits,
> disease or abiotic stress tolerance, and seed or pod-related traits,
> respectively

The identification of these loci provides valuable insights into the
genetic basis of adaptation and improvement in vegetable soybeans,
facilitating the development of more efficient breeding strategies for
crop enhancement. Within the 67 selected regions, 40 well-documented
soybean genes were detected, including members of the *GmXXXXX*,
*GmXXXXX*, *GmXXXXX*, *GmXXXXX* gene families, as well as *GmXXXXX*,
*GmXXXXX, GmXXXXX*, *GmXXXXX*, *GmXXXXX*, and others. These genes are
known to regulate various aspects of plant physiology, including plant
architecture, auxin response, seed development, seed nutrients, and
stress response (Ghosh and Islam 2016; Jiang et al. 2020; Xiong et al.
2023) (**Supplementary Fig. 8** and ~~Supplementary Table 14~~).
Notably, two promising candidate genes, *GmXXXXX* (*Glyma.XXGXXXXXX*)
and *GmXXXXX* (*Glyma.XXGXXXXXX*), were identified within selected
regions X-X (GmXX: XXX..XXX) and X-X (GmXX: XXX..XXX), respectively
(**Fig. 5B-C**). These genes play pivotal roles in pod and seed
development in vegetable soybeans, influencing soybean growth habit,
flowering time, seed weight, and overall seed yield (Jiang et al. 2020;
Liu et al. 2010; Xiong et al. 2023; Yu et al. 2023).

**[[SUPPLEMENTARY FIGURE 8; inaccessible]{.smallcaps}]**

> **Supplementary Fig. 8** Distribution of gene ontology (GO) functional
> categories of soybean genes within 67 selected regions: **A**
> Biological process. **B** Cellular component. **C** Molecular function

Furthermore, these selection regions were found to overlap with 49
previously reported QTLs identified in GWAS researches, as illustrated
in **Fig. 5D** and **Fig. 6A** (details provided in ~~Supplementary
Table 15~~). Among these QTLs, 20 were associated with morphological
traits, 16 with reproductive traits, 8 with physiological traits, and 5
with disease resistance and abiotic stress tolerance. Additionally, 11
out of 49 QTLs linked to seed-related or pod-related traits were also
observed, such as seed coat color, 100-pod fresh weight, 100-seed fresh
weight, and leaflet area (Fang et al. 2017; Li et al. 2019) (**Fig.
5D**). This concordance between previously reported QTLs and the
identified selection regions indicates these regions significance in the
development of vegetable soybeans, providing compelling evidence for the
relevance of these genomic regions in vegetable soybean breeding
programs.

Considering significant differences in seed-related traits between
vegetable soybeans and grain soybeans (Liu et al. 2022; Nair et al.
2023), we explored the impact of vegetable soybean improvement on
alleles associated with agronomic trait, specifically focusing on
100-seed weight. We identified alleles with significant signatures in
Group I (predominantly composed of vegetable soybeans) as favorable
alleles for vegetable soybeans (**Fig. 6A-B**). Remarkably, these
favorable alleles were alternative alleles of ‘William 82’, and their
presence was significantly associated with increased 100-seed weight
(~~Supplementary Table 16~~, Student’s *t*-test, *p* \< 0.001). We
observed a positive and significant correlation between the number of
favorable alleles and 100-seed weight (*r* = 0.67, *p* \< 0.001),
explaining 45% of the trait’s variation (**Fig. 6C**). Furthermore,
among all the “non-core collection” accessions (N = 2,150), there was a
significant correlation between the distribution of their number of
favorable alleles and 100-seed weight (*r* = 0.44, *p* \< 0.001, **Fig.
7A**). The discernible pattern of trait variation between core
collection and non-core collection, bearing varying degrees of favorable
alleles, underscores the efficacy and robustness of the core collection
in discerning differences in 100-seed weight (*p* \< 0.001, **Fig.
7B**). This emphasizes that the core collection framework facilitates
the accurate and efficient identification of genomic regions associated
with yield-related genes. In summary, the cumulative evidence,
encompassing gene function, GWAS QTLs, and agronomic traits, enhances
our understanding of phenotypic changes and the underlying genetic basis
of vegetable soybeans.

**[[FIGURE 6; inaccessible]{.smallcaps}]**

> **Fig. 6 Selection footprints and favorable alleles in vegetable
> soybean. A** Genomic footprintassociated with the enhancement of
> vegetable soybeans. Each row in the plot represents a peak SNP, and
> each column represents an individual accession. Yellow, green, light
> blue, and grey denote non-favorable alleles (reference allele of
> ‘William 82’), favorable alleles (alternative allele of ‘William 82’),
> heterozygous alleles, and missing alleles, respectively. Accessions
> from the same groups are grouped together, with labels indicated to
> the left of the plot. The selection regions overlapping with
> previously reported quantitative trait loci of genome-wide association
> study are partially labeled with the names of the traits at the
> corresponding peak SNPs. **B** Density distribution of favorable
> alleles in each group. **C** Relationships between the number of
> favorable alleles and phenotypic value for 100-seed weight. *R*^2^
> represents the coefficient of determination, while *r* denotes the
> Pearson correlation coefficient. ^\*\*\*^, *p*-value \< 0.001

**[[FIGURE 7; inaccessible]{.smallcaps}]**

> **Fig. 7 Validation of selection footprints. A** Relationships between
> the number of favorable alleles and 100-seed weight among 2,150
> “non-core collection” accessions (2,095 grain soybeans and 55
> vegetable soybeans). *R*^2^ denotes the coefficient of determination,
> while *r* represents the Pearson correlation coefficient. ^\*\*\*^,
> *p*-value \< 0.001. **B** Box plot illustrating the distribution of
> 100-seed weight based on the top 10% and bottom 10% of 2,150
> accessions (highlighted in brown) and the top 20% and bottom 20% of
> 244 core accessions (highlighted in green) with accumulated favorable
> alleles. Student’s *t*-test, ^\*\*\*^, *p*-value \< 0.001
