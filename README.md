# CQH Dimensional Phenotyper

### About

A tool for pulling [NIMH RDoC](https://www.nimh.nih.gov/research-priorities/rdoc/index.shtml) informed transdiagnostic phenotypes from medical documentation.

This code is described in [High Throughput Phenotyping for Dimensional Psychopathology in Electronic Health Records](https://doi.org/10.1016/j.biopsych.2018.01.011) and applied in [Genome-wide Association Study of Dimensional Psychopathology Using Electronic Health Records](https://doi.org/10.1016/j.biopsych.2017.12.004) both of which appear in *Biological Psychiatry*. 

This approach conceptually follows that reported in [A Clinical Perspective on the Relevance of Research Domain Criteria in Electronic Health Records](https://doi.org/10.1176/appi.ajp.2014.14091177) in AJP with an increased focus on ease of distribution.


### Usage

This was developed on `Python 2.7` and depends only on the standard lib. It accepts standard in, as such:

	cat your_document.txt | python2 CQHDimensionalPhenotyper.py
	
For any serious usage you are likely to want to treat `CQHDimensionalPhenotyper.py` as a library wrapped in your own project specific batch data handling.
