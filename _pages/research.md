---
title: "Valerie De Ana - Research"
layout: textlay
excerpt: "Valerie De Anda -- Research"
sitemap: false
permalink: /research/
---

# Research and Projects

# Current 

#### Reconstructing microbial genomes to understand the metabolic potential of marine sediments




#### MEBS

How can we organize and simplify complex genomic data to better understand the metabolism of diverse microbial taxa? This was the major research question behind the development of MEBS [**M**ultigenomic **E**ntropy **B**ased **S**core](https://academic.oup.com/gigascience/article/6/11/gix096/4561660). It works by synthesizing multiple sources of data on the metabolism of interest (e.g., genes, microbial taxa, and elemental reactions) under the mathematical framework of the Kullback-Leibler divergence, also known as relative entropy H’. An H’ value is assigned to each protein-coding gene (pcg) based on how often the gene is encoded in the genomes of metabolically similar microbial taxa. H’ values close to 0 indicate that a given pcg is widely distributed among microorganisms (e.g., ABC transporters) and is therefore non-informative of the target metabolism. H’ values near or greater than 1 indicate that a given pcg is unique to a group of metabolically similar microbial taxa, whereas negative H’ values indicate a given pcg is not expected to be involved in the target metabolism. MEBS stores the unique pcgs and their H’ values in an internal database, which can then be cross-referenced with genomic and metagenomic input data to obtain a single H’ score for a given metabolic pathway. High H’ scores suggest that microbial taxa can perform the pathways involved in the metabolism of interest.
Currently, the MEBS software has a built-in function that allows users to accurately and quickly evaluate the likelihood that up to thousands of microbial taxa (genomes) or communities (metagenomes) can perform the metabolic reactions involved in C, N, O, S, and Fe cycling. However, a user can also take a more advanced, step-wise, approach to examine additional metabolic reactions (e.g., As cycling). In addition, MEBS includes several tools to help users interpret their results: H’ values of specific metabolic pathways can be mapped on visual reconstructions of microbial phylogenies; microbial taxa or entire communities can be sorted by their metabolic function (e.g., nutrient assimilation); or communities filling certain metabolic niches (e.g., heavy metal degradation) can be mapped at global scales. 




---

# Previous 



**Doctoral research** (2013-2018): Laboratory of  molecular and experimental evolution. Ecology Institute. National Autonomous University of Mexico. Research Advisor: [Valeria Souza](https://loop.frontiersin.org/people/159715/overview)

**Developing  in silico approaches to evaluate the metabolic machinery and network  interactions of microbial communities in response to environmental change**

Changes in the environment caused by human development are severely impacting ecosystems all over the world and yet, the associated impacts on microbial communities are often overlooked. Evaluating the role of microbial communities is critical to understand how perturbations in the environment alter essential biogeochemical reactions that support life on our planet. However, microbial communities are rarely included in studies on biogeochemistry, ecology, climate change, and land-use, and are therefore underrepresented in policy that drives conservation and management decisions. While it is recognized that metabolite exchanges between microbial communities control ecological interactions framing ecosystem diversity and stability, systematic methods to quantify microbial levels of inter-species competition and cooperation are lacking to date. Moreover, it is unclear whether anthropogenic perturbations influence microbial community dynamics and if so, what are the patterns in response to disturbance and is it possible to predict them using computational tools?

The main goal dissertation was to identify microbial community patterns that can be used as bioindicators to signal changes in ecosystem state caused by anthropogenic environmental disturbance. Our data suggest that the mechanisms affecting the stability of microbial mats are linked to (1) the degree of negative interactions during perturbation, (2) the degree that microbial groups interact with each other, creating a large “seed pool” of genetic and taxonomic diversity to perform multiple metabolic functions, and (3) the presence of keystone microorganisms, which carry out essential functions in the community. This is the first study to incorporate [network motifs](https://science.sciencemag.org/content/298/5594/824) to analyze the ecology of microbial mats under [environmental perturbation](https://www.frontiersin.org/articles/10.3389/fmicb.2018.02606/full). Further studies are needed to examine whether the network motifs here are specific to microbial mats in our lagoon systems or are also present in other environments under perturbation. To better understand why some motifs are found in high or low abundances within our microbial mats, we need to further explore the mathematical properties of such networks motifs, but also design experiments of direct microbial interactions to obtain ecological information of the generalist and specialist microbe species in each node.
Assessing the community-wide implications of environmental perturbation and the shifts in microbial network interactions is a critical step towards improving knowledge of the response of microorganisms to anthropogenic and climate-linked change. By implementing  network inference, and the distribution of network motifs in other microbial communities, we can identify correlations between microbial community dynamics and ecosystem processes that govern their functional stability. 


---
[**Undergraduate reseach**(2011-2012)](http://oreon.dgbiblio.unam.mx/F/ER7GDVCUSESCA57BMBKUEX9SA8GH8CXC28QFSTLC27FX1YYE2R-10767?func=full-set-set&set_number=023912&set_entry=000002&format=999): Department of Cellular Engineering and Biocatalysis. Biotechnology Institute. National Autonomous University of Mexico. Research Advisor: [Lorenzo Segovia](http://www.ibt.unam.mx/server/PRG.base?tipo:doc,dir:PRG.curriculum,par:lorenzo)

I analyzed the possibility of obtaining active variants from a non-active chimera product of recombination between domains of the enzymes shikimate dehydrogenase (SDH) and quinate/shikimate dehydrogenase (YdiB) of E.coli, by directed evolution using random mutagenesis. This technique is a very powerful tool to elucidate structure-function relationships of proteins, in addition allows to improve or alter their characteristics. During my bachelor thesis I used mutagenic PCR by modifying the reaction modifications to obtain different rates of mutagenesis. Based on previus studies of evolution directed, we use 3 rates of mutagenesis. The first corresponds to approximately 2 mutations per 1000 base pairs. The second 3.5/1000 bp and the last generates 8.1 mutations per 1000 bp. The mutagenic PCR products were introduced into the pT4 expression vector and the resulting banks were characterized by complementary assays in M9 minimum medium of a strain lacking SDH activity.

<br />
<br />
