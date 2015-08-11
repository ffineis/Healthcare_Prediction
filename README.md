#Healthcare coverage prediction from 2009-2011 American Community Survey data

In February of this year, I took a programming test for a Chicago analytics company, Civics Analytics. Uhhhh, it went poorly. The test was to supply probabilities for the rows in the ACS dataset with missing healthcare coverage information (i.e. `hicov` was NA). Many months later, I'm giving it a second shot!

###Directories:
####data
1. **HealcareData1.txt**: ACS data used in the subsequent analysis. Alternatively, you can download from https://github.com/kjy/Healthcare/blob/master/HealthcareData1.txt
2. **frank_clean_data.txt**: processed version of HealthcareData1.txt.
3. **train_data.csv**: cleaned, scaled data with all *hicov* data available.
4. **test_data.csv**: cleaned, scaled data with all *hicov* data as NA.
5. **hicov_probs.csv**: predicted probabilities for yes/no *hicov* status for the rows present in *test_data.csv*.


####notebukz
1. **healthcare_demo_data_cleanup.ipynb** : iPython notebook with a walkthrough of the data cleaning procedures. Note that I pull heavily from a similar analysis of this dataset done in R, which can be found at http://rstudio-pubs-static.s3.amazonaws.com/16587_f28745b007e744f784d5358c843a84e5.html
2. **healcare_analysis.ipynb**: iPython notebook that loads the cleaned ACS data and tests several different types of models, along with brief descriptions of a few of the models. Generates *hicov_probs.csv*.






<p>
<p>
<p>
<p>
<p>
Special thanks to Jake for content and to Sarah for flexibility in scheduling!