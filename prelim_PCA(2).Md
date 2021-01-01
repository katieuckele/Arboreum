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

![PCA_prelim_arboreumNoPT](https://user-images.githubusercontent.com/30299787/103432337-2ef44180-4b92-11eb-8b3c-a65ef4976873.jpg)

What strikes me is that after removing *P. tuberculatum*, the PA and CR individuals that were originally associated with BR individuals [Accessions #'s 4731 (CR), 4746 (CR), and 1039 (PA)] are now distinguished from them in PC space. This makes sense given that Eric noted that the typical BR morphology was distinct from that found in PA and CR. 

### Looking at the Costa Rican endemic variety separately: 

![PCA_prelim_CostaRicaNoPT_bypop_map](https://user-images.githubusercontent.com/30299787/103447576-ef852e00-4c41-11eb-9f42-b56761238363.jpg)

### Looking at Brazil populations separately: 

![PCA_prelim_BrazilNoPT_bypop](https://user-images.githubusercontent.com/30299787/103432798-ceb5cd80-4b9a-11eb-9512-ebb75c514fdc.jpeg)

This is kind of a mess, but there is still so much structure even when looking at just BR. It's crazy. Scroll down to the bottom for this same PCA but with points colored according to percent missingness. 

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

