# *arboreum*
## Preliminary PCAs  
### 012 coded vcf file (11,159 loci; 494 individuals)

Broken down by country: 

294 Brazil

144 Costa Rica

56 Panama

### The original PCA which included all 494 individuals, including *P. tuberculatum* : 

![PCA_prelim_arboreum_accessionLabelled](https://user-images.githubusercontent.com/30299787/103432396-fbfe7d80-4b92-11eb-8a0c-7f11e3750568.jpg)

### Remove *P. tuberculatum* and rerun PCA : 

![PCA_prelim_arboreumNoPT_groups](https://user-images.githubusercontent.com/30299787/103464982-e1d8b280-4cec-11eb-96f2-27eba56c012b.jpg)

What strikes me is that after removing *P. tuberculatum*, the PA and CR individuals that were originally associated with BR individuals [Accessions #'s 4731 (CR), 4746 (CR), and 1039 (PA)] are now distinguished from them in PC space. This makes sense given that Eric noted that the typical BR morphology was distinct from that found in PA and CR. 

#### Colored by accession:

![PCA_prelim_arboreumNoPT_byaccession](https://user-images.githubusercontent.com/30299787/103499212-243ce500-4dfc-11eb-8c18-c684e6483ffe.jpg)

### PCA of Group 1:
![PCA_prelim_arboreumGroup1](https://user-images.githubusercontent.com/30299787/103464933-68d95b00-4cec-11eb-92d9-67b2731a02d1.jpeg)

Though the Costa Rican individuals cluster together and are distinct from Panamanian individuals, these clusters do not look super different from one another. 

### PCA of Group 2: 

![PCA_prelim_arboreumGroup2](https://user-images.githubusercontent.com/30299787/103464897-1b5cee00-4cec-11eb-9b5d-fa7147332a8b.jpeg)

Unlike Group 1, the Costa Rican population (green) looks distinct from the Panamanian population (yellow). 

### PCA of Group 3 (the Costa Rican endemic variety): 

![PCA_prelim_CostaRicaNoPT_bypop_map](https://user-images.githubusercontent.com/30299787/103499431-e096ab00-4dfc-11eb-8a29-de2e3ab44b68.jpg)

### PCA of Group 4 (the Brazilian populations): 

![PCA_prelim_BrazilNoPT_bypop_map](https://user-images.githubusercontent.com/30299787/103448462-f4041380-4c4e-11eb-881e-95ce6f0f0f11.jpg)

The diverged populations on the right hand of the plot were collected from the eastern coast (see map). The majority of our populations were collected from Brasília. Scroll down to the bottom for this same PCA but with points colored according to percent missingness. 

#### Plot each population on its own:

![PCA_prelim_BrazilNoPT_splitbypop](https://user-images.githubusercontent.com/30299787/103448021-455cd480-4c48-11eb-8b2d-3a3b18164059.jpg)

### What happens when we remove those most diverged populations on the right? 

![PCA_prelim_BrazilNoPT_rmDiverge_bypop](https://user-images.githubusercontent.com/30299787/103448131-e8fab480-4c49-11eb-864c-226558ffe809.jpeg)

To me, this looks like evidence for a lack of geographic population genetic structure. 

#### Plot each population on its own: 

![PCA_prelim_BrazilNoPT_rmDiverge_splitbypop](https://user-images.githubusercontent.com/30299787/103448132-eb5d0e80-4c49-11eb-8426-24fd73631f58.jpg)

#### Finally, are any of these patterns cause by missing data? 

![PCA_prelim_BrazilNoPT_missingness](https://user-images.githubusercontent.com/30299787/103432799-d1182780-4b9a-11eb-9ebf-ff6710be97ba.jpg)

It doesn't look like these patterns are due to differences in missingness. 

