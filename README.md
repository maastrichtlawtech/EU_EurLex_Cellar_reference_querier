# EU_EurLex_Cellar_reference_querier

This repository allows you to build a network of EU law(s) based on references from and / or to certain EU law(s), EU case law, or other documents published on EUR-Lex / CELLAR. You select one or more CELEX IDs as input, after which all references from and / or to the input will be searched. By increasing the source depth and / or target depth, you can increase the degree of separation. For instance, a target depth = 2 means that the references in the input documents to other EU documents will be searched, along with the references in the referred documents. A source depth = 2 entails that the references to the input document(s) will be identified, along with the references to the references that cite the input document(s).

The code can be used to find relevant or applicable EU documents given certain input documents.

Do not forget to create the folder structure mentioned in the notebook if you want to write the results to files.

The code is released under an Apache 2.0 license. An acknowledgment would be appreciated.