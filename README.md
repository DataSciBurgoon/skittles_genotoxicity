Author: Lyle D. Burgoon, Ph.D.
Date: July 30, 2022

# Background

The goal of this analysis is to answer a simple question: If the studies that EFSA identified as showing genotoxicity of TiO2 are true, how many skittles would I need to eat before I need to worry about genotoxicity?

What I can say is that I have examined the studies identified by EFSA. In my opinion, the studies are flawed, and upon critical review, I do not believe that there is any evidence that TiO2 causes genotoxicity, and even if it were to, they do not provide evidence that the genotoxicity is irreversible. The number of samples used in the studies is far too small to make any plausible inferences back to the human population. In one study they only used lymphocytes from a single person. In another case they used lymphocytes from only 20 people -- those are way too few people to be able to make inferences about the human population's response to TiO2.

There were statistical analysis flaws in many of the studies. In one case the authors did not run the samples on duplicate slides -- that is a standard for genotoxicity assays. In all cases where duplicate slides were used, the statistical model used was too simplistic. They need to account for the hierarchical nature of the study, and they did not.

In all cases, the studies were set-up in such a way that there is a high likelihood of sampling bias, which will lead to increased false positives.

In addition, genotoxicity assays are typically samples from samples of samples. What I mean is that when the toxicologists perform the assay, they are taking samples from the larger population of cells. In many cases they are looking at upwards of 50 cells, from a larger population of 100,000-1,000,000 cells. Again, there is a high risk of sampling bias, which leads to increased false positives.

In most of the studies there was not sufficient time for DNA repair operations to start or to finish. Most of the exposures were not for longer than 48 hrs -- and recent studies suggest that it may take 48hrs before DNA is repaired in highly transcriptional genes. 

Let us also not forget that genotoxicity in mature cells is typically not a problem. When it happens, the cell will either die, or the DNA will be repaired. What matters is if the stem cells exhibit genotoxicity that is not repaired. None of these studies looked at stem cells. This is important because stem cells are the ones that are going to pass along DNA mutations due to DNA damage. Today there is a lot of evidence supporting the stem cell theory of carcinogenesis.

# The Analysis

The skittles_genotoxicity.ipynb file contains the analysis in full. In the analysis I am making the assumption that the 80ug/mL concentration of TiO2 causes genotoxicity. I know that there is no evidence for this, but I want to demonstrate that even if 80ug/mL actually did cause genotoxicity, that that level represents such an extremely high dose that it is simply not plausible for a human to reach it.

In other words -- all chemicals are toxic at some dose. That dose may be ridiculously high -- as in the case of genotoxicity and TiO2. In the US we favor a risk-based approach where we use the science of toxicology to identify safe doses, and regulate chemical exposures to occur at those safe doses. 

You can see the rationale for me saying that 80ug/mL is a ridulously high dose that is implausible for humans to ever reach in the skittles_genotoxicity.ipynb file. In Github you just need to load it up in the browser to see the full analysis.