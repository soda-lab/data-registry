# Data registry

Directory to store metadata(JSON)

Metadata consisted of following attributes:

**Compulsory**
- key: "researchgraph.org/" + *source* + "/" + *local_id*
- local_id: The local id has to be unique string which can be title of data, indicator id, or doi. 
	- All space replaced to "-"
	- Exclude special character
- source: data source (e.g. abs.gov.au)
- last_updated: last updated date of data (yyyy-mm-dd)
- subjects: list of subjects to represent the data
- title: title of dataset
- publication_year: year of publised data
- url: URL for landing page of data

**Optional**
- asgs: Australian Statistical Geography Standard such as (SA1, GCCSA, S/T)
- license: license of data