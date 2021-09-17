# PerSpellData

A comprehensive parallel dataset designed for the task of spell checking in Persian. Misspelled sentences together with the correct form are produced using a massive confusion matrix, which is gathered from many sources. This dataset contains informal sentences in addition to the formal sentences, and contains texts from diverse topics. Both non-word and real-word errors are collected in the dataset


## Description

An atomic edit is defined as an edit *e* applied to a natural language expression *S* as the insertion, deletion, or substitution of a sub-expression *P* such that both the original expression S and the resulting expression *e(S)* are well-formed semantic constituents (MacCartney, 2009). In this corpus, we release such atomic insertions and deletions made to sentences in wikipedia. __**Please click on the numbers below to download the data**__.

Following are the number of examples by language:

Language | Insertions | Deletions |
---------|------------|-----------|
German  | [3.3](https://storage.googleapis.com/wiki-atomic-edits/german/insertions.tsv.gz)  | [1.9](https://storage.googleapis.com/wiki-atomic-edits/german/deletions.tsv.gz) |
English | [13.7](https://storage.googleapis.com/wiki-atomic-edits/english/insertions.tsv.gz) | [9.3](https://storage.googleapis.com/wiki-atomic-edits/english/deletions.tsv.gz) |
Spanish | [1.4](https://storage.googleapis.com/wiki-atomic-edits/spanish/insertions.tsv.gz)  | [0.9](https://storage.googleapis.com/wiki-atomic-edits/spanish/deletions.tsv.gz) |
French  | [2.0](https://storage.googleapis.com/wiki-atomic-edits/french/insertions.tsv.gz)  | [2.0](https://storage.googleapis.com/wiki-atomic-edits/french/deletions.tsv.gz) |
Italian | [1.0](https://storage.googleapis.com/wiki-atomic-edits/italian/insertions.tsv.gz)  | [0.6](https://storage.googleapis.com/wiki-atomic-edits/italian/deletions.tsv.gz) |
Japanese| [2.2](https://storage.googleapis.com/wiki-atomic-edits/japanese/insertions.tsv.gz)  | [1.3](https://storage.googleapis.com/wiki-atomic-edits/japanese/deletions.tsv.gz) |
Russian | [1.4](https://storage.googleapis.com/wiki-atomic-edits/russian/insertions.tsv.gz)  | [0.9](https://storage.googleapis.com/wiki-atomic-edits/russian/deletions.tsv.gz) |
Chinese | [0.7](https://storage.googleapis.com/wiki-atomic-edits/chinese/insertions.tsv.gz)  | [0.4](https://storage.googleapis.com/wiki-atomic-edits/chinese/deletions.tsv.gz) |
Total   | 25.7 | 17.2|

## Examples

Example of an insertion:

"*She died there after a long illness.*" + "*in 1949*" = "*She died there in 1949 after a long illness.*"

Example of a deletion:

"*She dreams about entering the Black Lodge and about a ring.*" - "*and about a ring.*" = "*She dreams about entering the Black Lodge.*"

For each language we provide two files, one each for insertions and deletions. The files contains the following tab-separated columns:

Column | Data |
:-----:| -----|
1      | Original sentence |
2      | Insertion/deletion|
3      | Edited sentence   |

## Reference 

If you use or discuss this dataset in your work, please cite our paper:

```
@InProceedings{}
```

## Contact

If you have a technical question regarding the dataset or publication, please
create an issue in this repository.
