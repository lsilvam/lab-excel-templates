Here are the Excel templates (`.xltx`) that I created and used in the laboratory.

A brief description of each one:
- 01_template_EBs_beating_foci
    - a template to log raw data from embryoid bodies beating foci count with a pre-built plot
- 01a_template_EBs_beating_foci
    - a template to log raw data from embryoid bodies beating foci count following tidy data format to be analyze in R
- 02_template_Bradford_96wellplate
    - a template to paste plate reader data to automatically create a calibration curve, and then to calculate sample protein concentration and sample volumes for Western Blot
- 03_template_primers
    - a template to save information about primers
- 04_template_design_qPCR
    - a template to prepare experimental design of qPCR experiment to automatically calculate mastermix and sample volumes, with a sheet to store raw Cq from the reader
- 05_template_mycoplasma_mastermix
    - a template to calculate mastermix volumes for PCR mycoplama testing using PCR kit from NZYtech
- 06_template_design_hangingDrop_differentitation
    - a template to plan hanging drop differentitiation to termine the number of cells needs as well as the total number of plates for the experiment. And it generates automatically a csv that can be import to a calendar with the important time points of the experiment
- 07_template_qPCR_analysis_ChIP_fold_enrichment
    - a template to calculate ChIP enrichment with pre-built plot, considering the enrichment relative to the % input (or total DNA). It also uses a correction to the Cq of the input.
-  08_template_qPCR_analysis_ddCt_taylor_et_al_2019
   - a template to calculate relative expression of genes following the ddCt method as in [Taylor et al. 2019](https://pubmed.ncbi.nlm.nih.gov/30654913/)
-  09_template_transfection_exp_design
   - a template to calculate amount of DNA (plasmid) and Lipofectime2000 to prepare a transfection mix.
-  10_template_experiment_metadata_microscopy
   - a template to create metadafile to be imported to CellProfiller so that the images are automtically matched to their respective experiment metadata (e.g. experimental groups)
-  11_template_westernBlot_quatification
   - a template to "quantify" western blots with data from ImageJ, with pre-built plot for three experimental conditions and t-test

DISCLAIMER:
These are templates that I created for me, they probably are not error free. Use them at your own risk. If you find errors, please open an issue. 