# Somatic Instability
Repository for code associated with the somatic instability analysis from the manuscript "Pathogenic Huntingtin Repeat Expansions in Patients with Frontotemporal Dementia and Amyotrophic Lateral Sclerosis"

Preprint: http://dx.doi.org/10.2139/ssrn.3652331

## File Descriptions

**Input Files**

1. Sample key (tab-delimited .txt file) containing the following columns (no heading) for each region (separate file for each sample): 
	- File path for peak tables (.txt) direct output files from GeneMapper (4.0)
	- Region name
	- Modal peak height (manual verification based on observation of peak table and chromatogram)
	- Modal peak size (manual verification based on observation of peak table and chromatogram) 
2. Peak tables (direct output files from GeneMapper)
3. Heatmap input dataframe (tab-delimited .txt file) containing the following columns (no heading): 
	- Sample name that region corresponds to
	- Region name
	- Instability index for corresponding region

**Somatic_Instability_Analysis.ipynb**

Somatic instability analyses using input files listed above.
