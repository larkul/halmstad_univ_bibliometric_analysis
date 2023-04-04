# Bibliometric analysis, Halmstad University
Publications 2003-2022


folder data contains:
1. hh_eid_2003-2022.csv - file with scopus eid used in the jupyter notebook (halmstad_scopus_asjc.ipynb) to fetch scoupus data via API
2. hh_scopus_2003-2022_raw.xlsx - data generated via jupyter notebook (halmstad_scopus_asjc.ipynb) 
3. hh_scopus_2003-2022_final.xlsx - data sorted on asjc subject areas
4. plots in png and html. top 20 most frequent asjc and codes used in the 2019 study made at the university. These plots are generated in the jubypter notebook halmstad_univ_bibliometric_analysis.ipynb, opens in google colab and can be edited there to fetch other information from the data in hh_scopus_2003-2022_final.xlsx

folder bibliometrix contians:
data for Halmstad University as a whole, and the six asjc subject areas with most publications. Network maps in html for keywords, authors, organisations. Thematic maps and a report in xlsx with different indicators. 

bibliometrix data created in R and the package bibliometrix: for more info about the package and the indicators, see: https://www.bibliometrix.org/vignettes/Introduction_to_bibliometrix.html

Jupyter notebook script for fetching data from Scopus is based on following: 
Santos, Breno Santana; Silva, Ivanovitch; Ribeiro-Dantas, Marcel da Câmara; Alves, Gisliany; Endo, Patricia Takako; Lima, Luciana. COVID-19: A scholarly production dataset report for research analysis. Data in Brief, Volume 32, 2020, DOI:10.1016/j.dib.2020.106178.
