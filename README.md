# Gendered cities: Studying urban gender bias through street names	
	
| Variables | Description |
|-----------|--------------------------------------------------|
| mun_code | Municipality code (INE). |
| year | Year. |
| male | Number of streets honoring a man. |
| male_nr | Number of streets honoring a man, excluding religious streets. |
| female | Number of streets honoring a woman. |
| female_nr | Number of streets honoring a woman, excluding religious streets. |
| st | Total number of streets in each municipality. |
| fs | Female share in street names, calculated as male_nr/ (male_nr+female_nr)*100. |
	
## Note about methodology	
The algorithm to classify streets by their gender (if any) is not error-free, but to the extent that errors identifying female streets are similar in relative magnitude to errors identifying male streets, errors offset one another and do not bias the female share. For this reason, errors in the female share indicator are expected to be small in large municipalities but can be high in small municipalities.	
For more details about the methodology of the algorithm, see the article below.	
We focus on the list of municipalities existing in 2001 (the first year with available data on street names). For comparability purposes over time, we have not considered municipal segregations since then; that is, when a municipality becomes independent from another, we continue to consider the original joint entity before the segregation. Regarding municipal unions, we do consider the new municipality as if it had existed since 2001.	
	
## Citation:	
Gutiérrez-Mora, D., & Oto-Peralías, D. (2022). Gendered cities: Studying urban gender bias through street names. Environment and Planning B: Urban Analytics and City Science, 49(6), 1792-1809. https://doi.org/10.1177/23998083211068844 	
