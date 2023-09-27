# meta-gpt-R
This package integrates GPT-3.5-turbo into R to bulk checks if genes can be related to traits and provides plausible biological explanations. It can submit an unlimited numver of gene-trait pairs at once so you would not have to manually submit queries to chatgpt.

**required file formate:**

![image](https://github.com/Shaoyi-Zhang96/meta-gpt-R/assets/94341094/0b1a98cc-087b-49be-a4a1-d3f622979889)


first column is the trait abbreviation (full trait name also accepted). Second column is the cell type information, third column are the genes of interest of particular trait in the particular cell type. There can be multiple genes for each trait/celltype pair, package is programmed to flatten it automatically. 

**If the trait provided in in abbreviation form, please provide a look up table in the form of this:**
For this particular metaanalysis, it is not needed since I have already inputted the dictionary###

abbreviation = c("ALS", "PD", "AD", "ASD", "BiPo", "SZ", "SI", "DPW", "CPD", "AI", "SC"),
  full_name = c("Amylotropic lateral sclerosis", "Parkinson’s disease", "Alzheimer’s disease", "Autism Spectrum Disorder", "Bipolar Disorder", "Schizophrenia", "Smoking cessation", "alcohol", "smoking", "smoking age", "Smoking cessation")

**In order to run this code, you will need your own Openai API key, which can be obtained here:**

https://platform.openai.com/

After you signup and log in to openai, click "personal" (top right), from the drop down menu click "manage account", click "API keys" (left mid screen). Here you can create your new API key, copy/paste it and store it in a secure location for later use. You will also have to chekc the "billing" section to see if you have any remaining balance, refill if needed.

**After you are done here, please got to the code part of this repository. **

