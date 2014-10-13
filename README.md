

This is a reconstruction of the metabolic network of the yeast _Saccharomyces
cerevisiae_ as described in the article:  
**The genome-scale metabolic model iIN800 of Saccharomyces cerevisiae and its validation: a scaffold to query lipid metabolism.**   
Nookaew I, Jewett MC, Meechai A, Thammarongtham C, Laoteng K, Cheevadhanarak
S, Nielsen J, Bhumiratana S. _BMC Syst Biol._ 2008 Aug 7;2:71; PMID:
[18687109](http://www.ncbi.nlm.nih.gov/pubmed/18687109) ,doi:
[10.1186/1752-0509-2-71](http://dx.doi.org/10.1186/1752-0509-2-71)  
Abstract:  
BACKGROUND: Up to now, there have been three published versions of a yeast
genome-scale metabolic model: iFF708, iND750 and iLL672. All three models,
however, lack a detailed description of lipid metabolism and thus are unable
to be used as integrated scaffolds for gaining insights into lipid metabolism
from multilevel omic measurement technologies (e.g. genome-wide mRNA levels).
To overcome this limitation, we reconstructed a new version of the
Saccharomyces cerevisiae genome-scale model, iIN800 that includes a more
rigorous and detailed description of lipid metabolism.  
RESULTS: The reconstructed metabolic model comprises 1446 reactions and 1013
metabolites. Beyond incorporating new reactions involved in lipid metabolism,
we also present new biomass equations that improve the predictive power of
flux balance analysis simulations. Predictions of both growth capability and
large scale in silico single gene deletions by iIN800 were consistent with
experimental data. In addition, 13C-labeling experiments validated the new
biomass equations and calculated intracellular fluxes. To demonstrate the
applicability of iIN800, we show that the model can be used as a scaffold to
reveal the regulatory importance of lipid metabolism precursors and
intermediates that would have been missed in previous models from
transcriptome datasets.  
CONCLUSION: Performing integrated analyses using iIN800 as a network scaffold
is shown to be a valuable tool for elucidating the behavior of complex
metabolic networks, particularly for identifying regulatory targets in lipid
metabolism that can be used for industrial applications or for understanding
lipid disease states.

The SBML was downloaded from the BioMet Toolbox page( [
`http://129.16.106.142/models.php?c=S.cerevisiae`
](http://129.16.106.142/models.php?c=S.cerevisiae) ) of Jens Nielsen's Lab for
Systems Biology at Chalmers University ( [ `http://www.sysbio.se/`
](http://www.sysbio.se/) ). The parameters _LOWER_BOUND_ and _UPPER_BOUND_
were added as defined in the BioOpt file available from the same page. One
error was corrected _R_PIxtO_ (Excretion of phosphate) _LOWER_BOUND_ was
changed from 1000 to 0. Parameters FLUX_VALUE were then calculated as defined
in "Flux balance analysis: a geometric perspective.", Smallbone K and
Simeonidis E, 2009 (J Theor Biol. 2009;258(2):311-5, pmid:
[19490860](http://www.ncbi.nlm.nih.gov/pubmed/19490860) ).

Technical notes:

  * The compartments included here have no volume defined; there are no reliable estimates available for those volumes yet.
  * There are no kinetic functions defined for the reactions because this model only represents the chemical structure of the network (stoichiometry).
  * Reactions for uptake and excretion are defined for some of the metabolites. All uptake reactions are constrained to zero flux and all excretion reactions are unconstrained.
  * All genes are assigned to the cytosol. This has no physiological meaning, but it is necessary for the structure of the model.
  * Biomass equations are available for carbon-limited and nitrogen-limited growth. The nitrogen-limited biomass equation is constrained to zero flux.
  * A few reactions are meant to be used to simulate the effect of for example increased ATP production. They are constrained to zero flux.

This SBML representation of the yeast metabolic network is made available
under the Creative Commons Attribution-Share Alike 3.0 Unported Licence (see
[www.creativecommons.org](http://www.creativecommons.org) ).

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

