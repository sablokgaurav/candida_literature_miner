# candida_iterature_miner
I just coded this function and this prepares the candida literature for the machine learning. Although prepared for candida, it can be used for any specific term that you want to search in pubmed. fetch count is the number of the recent papers that you want to fetch from the pubmed for that particular species or topic. Added yesterday the integratation of the langagueserver model for tuning the literature and explainer.

```
candidaLiteratureMiner(term = "candida", fetch_count = 10)
[('37579689',
  'The studies on metal complexes as potential antifungals are of growing interest because they may be the answer to increasingly effective defense mechanisms. Herein we present two new copper(I) iodide or thiocyanide complexes with 2,9-dimethyl-1,10-phenanthroline (dmp) and diphenylphosphine derivative of 1-(4-methoxyphenyl)piperazine (4MP): [CuI(dmp)4MP] (1-4MP) and [CuNCS(dmp)4MP] (2-4MP) - their synthesis, as well as structural and spectroscopic characteristics. Interestingly, while 4MP and its oxide derivative (4MOP) show a very low or no activity against all tested Candida albicans strains (MIC50 ≥ 200 μM against CAF2-1 - laboratory control strain, DSY1050 - mutant without transporters Cdr1, Cdr2, Mdr1; isogenic for CAF2-1, and fluconazole resistant clinical isolates), for 1-4MP and 2-4MP MIC50 values were 0.4 μM, independently on the complex and strain tested. Determination of the viability of NHDF-Ad (Normal Adult Human Dermal Fibroblasts) cell line treated with 1-4MP and 2-4MP showed that for both complexes there was only a 20% reduction in the concentration range ¼ to 2 × MIC50 and the 70% at 4 × MIC50. Subsequently, the MLCT based luminescence of the complexes in aqueous media allowed to record the confocal micrographs of 1-4MP in the cells. The results show that it is situated most likely in the vacuoles (C. albicans) or lysosomes (NHDF-Ad).'),
 ('37577210',
  'Background and aim:\n        \n      \n      Human infections caused by Candida albicans are common and range in severity from relatively treatable skin and mucosal conditions to systemic, fatal invasive candidiasis. The treatment of fungal infections is challenged by major obstacles, including the scarcity of effective therapeutic options, the toxicity of available medications, and the escalating antifungal resistance. Hence, there exists an urgent need to develop new classes of antimicrobial agents. This study was conducted to investigate the effect of KW-23 peptide against standard and resistant strains of C. albicans alone and in combination with fluconazole.\n    \n\n\n          Materials and methods:\n        \n      \n      A conjugated ultrashort antimicrobial peptide (KW-23) was designed and synthesized. KW-23 was challenged against standard and multidrug-resistant C. albicans alone and in combination with fluconazole using standard antimicrobial and checkerboard assays. The toxicity of the peptide was examined using hemolytic assays.\n    \n\n\n          Results:\n        \n      \n      KW-23 positively affected the standard and resistant Candidal strains (at 5 and 15 μg/mL respectively), exhibiting potent synergistic antimicrobial activity against the standard strain when combined with fluconazole. The effect of the combination was additive against the resistant strain (0.6 μg/mL). Furthermore, the peptide exhibited negligible toxicity on human erythrocytes.\n    \n\n\n          Conclusion:\n        \n      \n      KW-23 and its combination with fluconazole could be a promising candidate for developing anticandidal agents.'),
 ('37577059',
  'Purpose of review:\n        \n      \n      For human fungal pathogens, sensory perception of extracellular pH is essential for colonisation of mammalian tissues and immune evasion. The molecular complexes that perceive and transmit the fungal pH signal are membrane-proximal and essential for virulence and are therefore of interest as novel antifungal drug targets. Intriguingly, the sensory machinery has evolved divergently in different fungal pathogens, yet spatial co-ordination of cellular components is conserved.\n    \n\n\n          Recent findings:\n        \n      \n      The recent discovery of a novel pH sensor in the basidiomycete pathogen Cryptococcus neformans highlights that, although the molecular conservation of fungal pH sensors is evolutionarily restricted, their subcellular localisation and coupling to essential components of the cellular ESCRT machinery are consistent features of the cellular pH sensing and adaptation mechanism. In both basidiomycetes and ascomycetes, the lipid composition of the plasma membrane to which pH sensing complexes are localised appears to have pivotal functional importance. Endocytosis of pH-sensing complexes occurs in multiple fungal species, but its relevance for signal transduction appears not to be universal.\n    \n\n\n          Summary:\n        \n      \n      Our overview of current understanding highlights conserved and divergent mechanisms of the pH sensing machinery in model and pathogenic fungal species, as well as important unanswered questions that must be addressed to inform the future study of such sensing mechanisms and to devise therapeutic strategies for manipulating them.'),
 ('37576760',
  "Background and aim:\n        \n      \n      Fungal zoonoses are an economic and public health concern because they can cause various degrees of morbidity and mortality in animals and humans. To combat this issue, alternative natural antifungals, such as products derived from rice protein hydrolysates or rice antifungal protein/peptide are being considered because they are highly bioactive and exhibit various functional properties. Thailand is a leading rice producer and exporter. Among the various cultivated rice varieties, Sangyod rice (Oryza sativa L.) is exclusively indigenous to Thailand's Phatthalung province; it has a Thai geographical indication tag. Here, we investigated whether the Phatthalung Sangyod rice seeds have bioactive antifungal peptides.\n    \n\n\n          Materials and methods:\n        \n      \n      Antifungal activity in four Sangyod rice seed extracts (SYPs) - namely, (1) the crude lysate, SYP1; (2) the heat-treated lysate, SYP2; (3) the heat- and pepsin digested lysate, SYP3; and (4) the heat- and proteinase K-digested lysate, SYP4 - was analyzed. Protein concentrations in these SYPs were determined using the Bradford assay. The total phenolic compound content was determined using the modified Folin-Ciocalteu method in a 96-well microplate. Then, the SYP protein pattern was determined using the sodium dodecyl sulfate-polyacrylamide gel electrophoresis. Subsequently, using the agar well diffusion method, the antifungal properties of these SYPs were tested against ten medically important pathogenic fungi. The minimal inhibitory concentration (MIC) and minimal fungicidal concentration values were determined for the active SYPs - SYP2-4. Finally, the clinical safety of SYP4 was determined using a hemolytic assay (using canine red blood cells [RBCs]).\n    \n\n\n          Results:\n        \n      \n      The crude lysate SYP1 did not show antifungal activity against any of the ten tested pathogenic fungi. Surprisingly, hydrolysates SYP2, SYP3, and SYP4 displayed antifungal properties against the ten tested pathogenic fungi. Thus, heat and enzymatic hydrolysis seem to transform the bioactivity of the crude protein extract - SYP1. Further, SYP4 shows the most effective antifungal activity. It completely inhibited Cryptococcus neoformans, Talaromyces marneffei yeast phase, Trichophyton mentagrophytes, and Trichophyton rubrum. A partial inhibitory action on Candida albicans and Microsporum gypseum was possessed while showing the least activity to C. neoformans. SYP4 was nontoxic to canine RBCs. Hemolysis of canine RBCs was undetectable at 1 × MIC and 2 × MIC concentrations; therefore, it can be safely used in further applications.\n    \n\n\n          Conclusion:\n        \n      \n      These results indicate that heat and proteinase K hydrolyzed SYP is a very potent antifungal preparation against animal and human fungal pathogens and it can be used in future pharmaceuticals and functional foods."),
 ('37576685',
  'Nanoemulgel (NEG) pharmaceutical formulations are gaining popularity because of their ability to serve both as a nanoemulsion and as a gel. These products are well-known for their ease of use, spreadability, controlled release, and ability to hydrate dry skin. Natural essential oils have been shown to promote the cutaneous permeability of topical formulations, enhancing medication safety and efficacy. Herein, we developed NEG for the enhanced permeation of ketoconazole against candidiasis using clove oil (clove-oil-NEG) or eucalyptus oil (eucalyptus-oil-NEG), using the gelling agents carbopol 943 and hydroxypropyl methylcellulose (HPMC). We tested various excipients to increase the solubility of ketoconazole and formulate a nanoemulsion (NE). We measured the NE droplet particle size, shape, entrapment efficiency, and drug release. Furthermore, the physicochemical properties of the optimized nanoemulsion formulation were characterized by techniques such as Fourier transform infrared (FT-IR) spectroscopy and X-ray diffraction (XRD) analysis. The NEs were loaded into gels to form NEGs. NEGs were characterized for drug content, homogeneity, rheology, spreadability, and antifungal activity against Candida albicans, both in vitro and in vivo. Optimized ketoconazole NEG preparations consisted of either 15% clove oil or 20% eucalyptus oil. Droplet sizes in the optimized NEs were <100 nm, and the polydispersity indexes were 0.24 and 0.26. The percentages of ketoconazole released after 24 h from the clove-oil-NEG and eucalyptus-oil-NEGs were 91 ± 4.5 and 89 ± 7%, respectively. Scanning electron microscopy (SEM) showed that the NEGs had a smooth, uniform, and consistent shape and internal structural organization. The drug contents in the clove-oil-NEG and eucalyptus-oil-NEG were 98.5 ± 2.2 and 98.8 ± 3.4%, respectively. Permeation values of ketoconazole from clove-oil-NEG and eucalyptus-oil-NEG were 117 ± 7 and 108.34 ± 6 μg cm-2, respectively. The ketoconazole NEG formulations also had higher levels of fungal growth inhibition than a marketed formulation. Finally, in vivo studies showed that the NEGs do not irritate the skin. Ketoconazole NEG with either 15% clove oil or 20% eucalyptus oil is stable with better efficacy than ketoconazole alone due to excellent dispersion, drug dissolution, and permeability and thus might be recommended for the effective and safe treatment of candidiasis.'),
 ('37576624',
  'Improving lipophilicity for drugs to penetrate the lipid membrane and decreasing bacterial and fungal coinfections for patients with cancer pose challenges in the drug development process. Here, a series of new N-alkylated-2-(substituted phenyl)-1H-benzimidazole derivatives were synthesized and characterized by 1H and 13C NMR, FTIR, and HRMS spectrum analyses to address these difficulties. All the compounds were evaluated for their antiproliferative, antibacterial, and antifungal activities. Results indicated that compound 2g exhibited the best antiproliferative activity against the MDA-MB-231 cell line and also displayed significant inhibition at minimal inhibitory concentration (MIC) values of 8, 4, and 4 μg mL-1 against Streptococcus faecalis, Staphylococcus aureus, and methicillin-resistant Staphylococcus aureus compared with amikacin. The antifungal data of compounds 1b, 1c, 2e, and 2g revealed their moderate activities toward Candida albicans and Aspergillus niger, with MIC values of 64 μg mL-1 for both strains. Finally, the molecular docking study found that 2g interacted with crucial amino acids in the binding site of complex dihydrofolate reductase with nicotinamide adenine dinucleotide phosphate.'),
 ('37576453',
  'Plantago lanceolata and Sida ovata have been used as medicinal plants for centuries to cure numerous diseases. This study aimed to evaluate antifungal activity of P. lanceolata and S. ovata leaf extracts against dermatomycotic fungi. Crude extracts from leaves of both plants were prepared using methanol and ethyl acetate. Phytochemical screening of both plants leaves was performed. Antifungal activity of crude extracts was evaluated against three dermatomycotic fungi (Candida albicans, Malassezia furfur, and Malassezia globosa). In addition, minimum inhibitory concentration (MIC) of the extracts was determined by microbroth dilution method. Maximum inhibition zone of 32.00 ± 11.64 mm was exhibited when combined ethyl acetate extract of both plants was applied against M. globosa. Best effect of MIC was demonstrated by ethyl acetate extract against most tested dermatomycotic fungi. Average MIC of ethyl acetate and methanol extracts ranged as follows: (0.19 ± 0.00 to 0.65 ± 0.00 mg/mL and 0.19 ± 0.00 to 0.52 ± 0.22 mg/mL) and (0.65 ± 0.22 to 1.56 ± 0.00 mg/mL and 0.19 ± 0.00 to 0.52 ± 0.00 mg/mL), respectively. Their synergistic effect was better than the effect of individual plant leaf extract. Minimum fungicidal concentration (MFC) values varied across the fungal pathogens when extracts from both plants and their combinations were used. The findings from the current study support the traditional use of P. lanceolata and S. ovata against dermatomycotic fungal infections, which could potentially be exploited for the treatment of superficial infection in humans.'),
 ('37576197',
  "Yolk-shell-based silica-coated silver nanoparticles are prominently used in the biomedical field aas well as bare silver nanoparticles for various biological applications. The present work narrates the synthesis and silica coating of metallic silver nanoparticles and investigates their antibacterial, antifungal, and anticancerous activity. Both synthesized nanoparticles were characterized by TEM, and SEM-EDX. The average size of silver nanoparticles was 50 nm, while after coating with silica, the average size of silica-coated silver nanoparticles was 80 nm. The nanoparticles' antibacterial, antifungal, and anticancer properties were comparatively examined in vitro. Agar well diffusion method was employed to explore the antibacterial activity against gram-positive bacteria (Bacillus cereus) and gram-negative bacteria (Escherichia coli) at different concentrations and antifungal activity against Candida Albicans. To understand the minimum concentration of both nanoparticles, we employed the minimum inhibitory concentration (MIC) test, against bacterial and fungal strains, which was dose dependent. We learned that bare silver nanoparticles showed high antibacterial activity, whereas silica-coated silver nanoparticles surpassed their antifungal capability over bare silver nanoparticles against Candida albicans. The anticancer activity of the as-prepared nanoparticles was executed in opposition to the prostate cancer cell (PC-3) line by MTT assay, which showed meaningful activity. Following this, flow cytometry was also effectuated to learn about the number of apoptotic and necrotic cells. The results of this study demonstrate the dynamic anti-cancerous, antibacterial, and antifungal activities of bare silver nanoparticles and silica-coated silver nanoparticles for a long-lasting period."),
 ('37573268',
  'Treatment of anogenital warts (AGWs) is challenging. Candida antigen immunotherapy has been proven to be a safe and relatively effective therapeutic modality; nevertheless, some patients may experience a partial or no response. Combining Candida antigen with other immunotherapies has been proposed to improve the cure rate. Immunotherapy with human papillomavirus (HPV) vaccines has been tried with conflicting outcomes. This study aimed to assess the efficacy and safety of intralesional Candida antigen, either alone or in combination with intralesional bivalent or quadrivalent HPV vaccines, for treating multiple AGWs. Eighty patients with multiple AGWs were included and randomly assigned to four equal groups: group A treated with intralesional Candida antigen only; group B treated with intralesional bivalent HPV vaccine (Cervarix) and Candida; group C treated with intralesional quadrivalent HPV vaccine (Gardasil) and Candida; and group D (control) treated with intralesional saline. Complete clearance of lesions was detected in 40%, 20%, and 60% of patients in Candida monotherapy, Cervarix/Candida, and Gardasil/Candida groups, respectively, whereas 40%, 60%, and 20% of patients in the three groups, respectively, showed partial response. Only 10% of the control group had a partial response. Therapeutic outcomes were significantly better in the three treatment groups compared to the control group, with no statistically significant difference between the Candida monotherapy group and the combination groups, but the response was significantly better in the Gardasil/Candida group than in the Cervarix/Candida group. No statistically significant difference was found between the studied groups regarding the development of side effects. Moreover, no recurrence was detected in any of the groups throughout the 3-month follow-up period. Based on our results, combining intralesional HPV vaccines with Candida antigen immunotherapy may have no significant benefit for treating multiple AGWs. Candida antigen may be recommended as a relatively effective and inexpensive therapeutic modality. The combination of Gardasil and Candida was also effective but very expensive. The results of the Cervarix/Candida combination were unsatisfactory. This clinical trial was registered and approved prospectively by the ethical review board at Faculty of Medicine, Zagazig University.'),
 ('37573133',
  "Vulvovaginal candidiasis (VVC) is an inflammatory disease primarily infected by Candida albicans. The condition has good short-term treatment effects, high recurrence, and seriously affects the quality of life of women. Metabolomics has been applied to research a variety of inflammatory diseases. In the present study, the vaginal metabolic profiles of VVC patients and healthy populations (CTL) were explored by a non-targeted metabolomics approach. In total, 211 differential metabolites were identified, with the VVC group having 128 over-expressed and 83 under-expressed metabolites compared with healthy individuals. Functional analysis showed that these metabolites were mainly involved in amino acid metabolism and lipid metabolism. In addition, network software analysis indicated that the differential metabolites were associated with MAPK signaling and NF-κB signaling. Further molecular docking suggested that linoleic acid can bind to the ACSL1 protein, which has been shown to be associated with multiple inflammatory diseases and is an upstream regulator of the MAPK and NF-κB signaling pathways that mediate inflammation. Therefore, our preliminary analysis results suggest that VVC has a unique metabolic profile. Linoleic acid, a significantly elevated unsaturated fatty acid in the VVC group, may promote VVC development through the ACSL1/MAPK and ACSL1/NF-κB signaling pathways. This study's findings contribute to further exploring the mechanism of VVC infection and providing new perspectives for the treatment of Candida albicans vaginal infection.")]
```

Gaurav Sablok \
Frontiers: https://loop.frontiersin.org/people/33293/overview \
ORCID: https://orcid.org/0000-0002-4157-9405 \
WOS: https://www.webofscience.com/wos/author/record/C-5940-2014 \
Github:https://github.com/sablokgaurav \
Linkedin: https://www.linkedin.com/in/sablokgaurav/
