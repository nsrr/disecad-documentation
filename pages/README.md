## About

DISE-CAD, Characterizing Mechanisms of Upper Airway Obstruction During Drug-Induced Sleep Endoscopy (DISE) is a 5-year prospective clinical trial sponsored by the NIH/NHLBI that was conducted at the University of Pennsylvania (originating institution). The dataset includes 33 patients to date, all of whom have an implanted Inspire hypoglossal nerve stimulator (eligibility criteria) for treatment of OSA. These patients have undergone DISE (including CPAP titration and stimulation with Inspire), MRI of the upper airway, a split-night PSG (half-night baseline, half-night with Inspire), craniofacial photos, and tongue force measurements. Data includes physiology from DISE and PSG (e.g. respiratory signals, airway pressure, airflow), video grading via VOTE score, demographics, anthropometrics, and baseline OSA characteristics derived from PSG (e.g. AHI, ODI). These data are being used to determine what factors might predict a successful response to HGNS/Inspire surgery.

The DISE-CAD dataset on NSRR includes the following data: demographics, anthropometry, sleep study results, and DISE findings. Signal data (EDF) from the DISE procedures are available for 32/33 subjects.

## Methods

### Inclusion criteria

Adults 22+ years old, implanted with MRI-conditional Inspire device (model 3028 or later), compliant with therapy (20+ hours/week over 2+ weeks), Inspire remote model 2500 or later.

### Exclusion criteria 

MRI contraindications (e.g. claustrophobia, implants other than HGNS, foreign bodies, etc), Inspire implant model 3024, Inspire remote model 3032, history of falling asleep while driving resulting in an accident or "near miss" within 1 year prior to device implantation, inability to sleep in the supine position, history of severe difficulty initiating or maintaining sleep in the sleep lab, pregnant women.

### Equipment

Polysomnography: Alice 6

Drug-induced sleep endoscopy: Nox Medical Noxturnal Software with A-1 HST and C-1 Access Point, Millar PCU-2000 for pharyngeal manometry, Siemens MRI scanner

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

### Covariate/phenotype datasets (CSV)

The [covariate dataset files](:files_path:/datasets) (**disecad-dataset-0.1.0.csv** and **disecad-harmonized-dataset-0.1.0.csv**) contain 33 rows respectively.

The dataset columns are described in the accompanying data dictionary files. The variables data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 1=Male, 2=Female), which are described in the domains data dictionary file. 

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/disecad-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team. Key variables include:

  <table>
    <tr><td><b>Variable</b></td><td><b>Label</b></td></tr>
    <tr><td><a href=":variables_path:/nsrr_age">nsrr_age</a></td><td>Subject age</td></tr>
    <tr><td><a href=":variables_path:/nsrr_sex">nsrr_sex</a></td><td>Subject sex</td></tr> 
    <tr><td><a href=":variables_path:/nsrr_bmi">nsrr_bmi</a></td><td>Body mass index (BMI)</td></tr> 
  </table>

### DISE procedure raw signal data

[Raw signal data](:files_path:/original/EDFs) from the DISE procedures are available as European Data Format (EDF) files.

### Original covariate dataset and documentation

The DISE-CAD contributor [provided original documentation and data](:files_path:/original) from their REDCap data collection project. The NSRR did not extract all covariates and event-level data into the covariate/phenotype datasets described above. DISE-CAD requestors may wish to extract additional data from the original (source) dataset.

## Access and usage restrictions

The DISE-CAD dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Dedhia RC, Seay EG, Schwartz AR. Beyond VOTE: The New Frontier of Drug-Induced Sleep Endoscopy. ORL J Otorhinolaryngol Relat Spec. 2022;84(4):296-301. doi: 10.1159/000518660. Epub 2021 Sep 27. PMID: 34818232; PMCID: PMC8957630.](https://pubmed.ncbi.nlm.nih.gov/34818232/)
>
> [Harkins T, Tangutur A, Keenan BT, Seay EG, Thuler E, Dedhia RC, Schwartz AR. Pharyngeal Manometry and Upper Airway Collapse During Drug-Induced Sleep Endoscopy. JAMA Otolaryngol Head Neck Surg. 2024 Oct 1;150(10):869-876. doi: 10.1001/jamaoto.2024.2559. PMID: 39207817; PMCID: PMC11362972.](https://pubmed.ncbi.nlm.nih.gov/39207817/)

Users must include the following text in any Acknowledgements:

> The DISE-CAD study was supported by National Institutes of Health grant R01HL144859. The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002). 

## Changelog

*May 2025*

- Make DISE-CAD dataset available for data requests

## References

- DISE-CAD GitHub Data Dictionary: http://github.com/nsrr/disecad-data-dictionary
- DISE-CAD GitHub Documentation: https://github.com/nsrr/disecad-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
