Hello World! 

Welcome to the attempt at mining NCBI for microgravity analoges. 
There are so many open-source microgravity analogue platform now available i thought it was time for a review of the literature. 

Below is a great example from NASA-funded Space Biology researcher Prof Karl Hasestein. 
![examplw figure from KArl](https://github.com/dr-richard-barker/Microgravity_analogue_review/assets/8679982/8d3621a1-1fed-40f6-8b52-65d640ba5d97)

But where do RPM's fit into the broader and older microgravity analogue ecosystem? 

Here are the results and the ipython note book that was used to mine the literature for papers related to microgravity analogues. 
This included a search for RPM, 2D clinostat, slow rotating wall vessels. 

The goal was/is to assess the amount of open information that exists about these types of microgravity analogues. 

query = "('RPM' or 'random positioning machine' or 'Random Positioning Machine')"
query = "('2D clinostat' or 'clinostat' or 'Clinostat')" 
query = "('slow fall rotating vessel' or 'slow wall rotating vessel' or 'rotating wall vessel')"

This can be done through the NCBI webpage like this (not you can change the "RPM" ,or "random+positioning+machine" in the URL to search for other concepts).

https://pubmed.ncbi.nlm.nih.gov/?term=%27RPM%27+or+%27random+positioning+machine%27&page=1

We then compiled more information about the PMID, title, abstract, authors, keywords, publication year, journal title and publication type. 
See the ipython notebook to test for yourself. 

Preliminary analysis from Rtutor.ai (Thanks Prof Ge)
![DRB 3D clinostat methods review](https://github.com/dr-richard-barker/Microgravity_analogue_review/assets/8679982/46697904-b4c4-4395-97f0-d2f3731cc182)


My big question is how many false positives are in this dataset? 

Can you find a clever way to analyse these **17411** papers (Titles, abstracts, journals) to identify which are truly microgravity analogue experiments and remove the false positives from this dataset?  

Good Luck
