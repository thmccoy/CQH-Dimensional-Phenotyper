# CQH Dimensional Phenotyper

### About

A tool for pulling [NIMH RDoC](https://www.nimh.nih.gov/research-priorities/rdoc/index.shtml) informed transdiagnostic phenotypes from medical documentation.

This code is described in [High Throughput Phenotyping for Dimensional Psychopathology in Electronic Health Records](https://doi.org/10.1016/j.biopsych.2018.01.011). This approach to RDoC symptom estimates conceptually follows that reported in [A Clinical Perspective on the Relevance of Research Domain Criteria in Electronic Health Records](https://doi.org/10.1176/appi.ajp.2014.14091177) but with an increased focus on ease of distribution.

 This software has been applied in:
 
   - [Genome-wide Association Study of Dimensional Psychopathology Using Electronic Health Records](https://doi.org/10.1016/j.biopsych.2017.12.004)
   - [Stratifying risk for dementia onset using large-scale electronic health record data: a retrospective cohort study](https://doi.org/10.1016/j.jalz.2019.09.084)
   - [Research Domain Criteria scores estimated through natural language processing are associated with risk for suicide and accidental death](https://doi.org/10.1002/da.22882)
   - [Association between child psychiatric emergency room outcomes and dimensions of psychopathology](https://doi.org/10.1016/j.genhosppsych.2019.04.009)
   - [Differences among Research Domain Criteria score trajectories by Diagnostic and Statistical Manual categorical diagnosis during inpatient hospitalization](https://doi.org/10.1371/journal.pone.0237698)
   - [Electronic Health Record Documentation of Psychiatric Assessments in Massachusetts Emergency Department and Outpatient Settings During the Coronavirus Disease 2019 (COVID-19) Pandemic](https://doi.org/10.1001/jamanetworkopen.2020.11346)
   - [Mapping of Transdiagnostic Neuropsychiatric Phenotypes Across Patients in Two General Hospitals](https://doi.org/10.1016/j.jaclp.2021.01.002)
   - [Mood Disorders and Outcomes of COVID-19 Hospitalizations](https://doi.org/10.1176/appi.ajp.2020.20060842)


### Usage

This was developed on `Python 2.7` and depends only on the standard lib. It accepts standard in, as such:

	cat your_document.txt | python2 CQHDimensionalPhenotyper.py
	
For any serious usage you are likely to want to treat `CQHDimensionalPhenotyper.py` as a library wrapped in your own project specific batch data handling.
