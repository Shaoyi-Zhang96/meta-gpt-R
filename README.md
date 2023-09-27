# meta-gpt-R
This package integrates GPT-3.5-turbo into R to checks if genes can be related to traits and provides plausible biological explanations.

**required file formate:**

![image](https://github.com/Shaoyi-Zhang96/meta-gpt-R/assets/94341094/0b1a98cc-087b-49be-a4a1-d3f622979889)


first column is the trait abbreviation (full trait name also accepted). Second column is the cell type information, third column are the genes of interest of particular trait in the particular cell type. There can be multiple genes for each trait/celltype pair, package is programmed to flatten it automatically. 

If the trait provided in in abbreviation form, please provide a look up table in the form of this:

![image](https://github.com/Shaoyi-Zhang96/meta-gpt-R/assets/94341094/5b3698c0-94bb-4a63-b1f2-6cfddf2c7c94)




