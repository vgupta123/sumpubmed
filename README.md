<p align="center"><img width="80%" src="logo.png" /></p>

**SumPubMed : Summarization Dataset of PubMed Scientific Article**
SumPubmed is a dataset for abstractive summarization over scientific article. The dataset use the [PubMed dataset](https://catalog.data.gov/dataset/pubmed) to create a summarization dataset. PubMed comprises more than 26 million citations for biomedical literature from MEDLINE, life science journals, and online books. Citations may include links to full-text content from PubMed Central and publisher web sites. 

We downloaded 33,772 documents identified as BMC literature. BMC (BIO MED CENTRAL) literature incorporates BMC health services research papers related to medicine, pharmacy, nursing, dentistry, health care, and so on for SumPubMed creation. 

***DataSet Structure***
After downloading, you have multiple sub-folders with several txt files. Datasets contains the following four folders as described below :

``` 
shorter_abstract: final short summary of the text
abstract: long summary of the text (background, results, conclusions)
line_text: text with a single sentence in a line
text: contain the PubMed text in the raw form 
```

***Recomended Citation***
Please cite the below paper if you intent to use the dataset for your research.

```
@article{bharti2020,
  title={SumPubMed: Summarization Dataset of PubMed Scientific Article},
  author={Bharti, Prerna and Gupta, Vivek and Nokhiz, Pegah and Karnick, Harish},
  year={2020}
}
```
*** LICENCE***
Carefully read the LICENCE and the Datasheet for non-academic usage. This dataset is licensed under the terms of the MIT license. Feel free to use the dataset for non-commercial purpose.