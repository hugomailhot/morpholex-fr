# MorphoLex-fr
Lexical database for ~38k French words with morphological variables

## Fields and their meaning

See the [paper](#link-to-the-paper) for details on each field.

| Field         | Meaning                                                                                |
|---------------|----------------------------------------------------------------------------------------|
| Word          | Word                                                                                   |
| freq          | Lexical Frequency (from FLP)                                                           |
| n_morphemes   | Number of morphemes                                                                    |
| prs           | Prefix-Root-Suffix signature                                                           |
| canon_segm    | Morphological segmentation of the word, with the canonical allomorphs of each morpheme |
| PREF_PFMF     | Percentage of more frequent words in the morphological family (prefix)                 |
| PREF_FamSize  | Family Size (prefix)                                                                   |
| PREF_Freq_HAL | Cumulative morpheme frequency (prefix)                                                 |
| PREF_length   | length of the prefix (number of letters)                                               |
| ROOT_PFMF     | Percentage of more frequent words in the morphological family (root)                   |
| ROOT_FamSize  | Family Size (root)                                                                     |
| ROOT_Freq_HAL | Cumulative morpheme frequency (root)                                                   |
| SUFF_PFMF     | Percentage of more frequent words in the morphological family (suffix)                 |
| SUFF_FamSize  | Family Size (suffix)                                                                   |
| SUFF_Freq_HAL | Cumulative morpheme frequency (suffix)                                                 |
| SUFF_length   | length of the suffix (number of letters)                                               |


### How to cite
Mailhot, H., Wilson, M. A., Macoir, J., Deacon, S. H., & Sánchez-Gutiérrez, C. (2019). MorphoLex-FR: A derivational morphological database for 38,840 French words. Behavior Research Methods. https://doi.org/10.3758/s13428-019-01297-z

### Link to the paper
https://link.springer.com/article/10.3758/s13428-019-01297-z

### Found a  mistake?
Let us know! Too many databases out there are released with their original flaws and never updated. You can either open an issue ticket on this repo, or write Hugo Mailhot at [hmailhot@ucdavis.edu](hmailhot@ucdavis.edu).
