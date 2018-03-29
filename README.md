This repository contains the CoNLL-UL formatted morphological analysis of
the version 2.1 of the [UD Turkish treebank](https://github.com/UniversalDependencies/UD_Turkish).

The files were generated with 
[Trmorph version 2](https://github.com/coltekin/TRmorph/tree/trmorph2)
with the following command line:

```
./tools/conllu2conllul <input file> -o <output file>
```
a best guess of `goldId`, and OoV words are also marked in the MISC field of conllul files
(using the `-g` switch of the above command).

## Citation

Amir More, Özlem Çetinoğlu, Çağrı Çöltekin, Nizar Habash, Benoît Sagot,
Djamé Seddah, Dima, Taji and Reut Tsarfaty (2018)
[CoNLL-UL: Universal Morphological Lattices for Universal Dependency Parsing.](http://coltekin.net/cagri/papers/more2018.pdf)
In: Proceedings of the Eleventh International Conference
on Language Resources and Evaluation (LREC'18) 

```
@inproceedings{more2018,
 author  = {More, Amir and  Ã‡etinoÄŸlu, Ã–zlem and  Ã‡Ã¶ltekin, Ã‡aÄŸrÄ± and  Habash, Nizar and  Sagot, BenoÃ®t and  Seddah, DjamÃ© and  Taji, Dima, and  Tsarfaty, Reut},
 year  = {2018},
 title  = {{CoNLL-UL}: Universal Morphological Lattices for {U}niversal {D}ependency Parsing},
 booktitle  = {Proceedings of the Eleventh International Conference on Language Resources and Evaluation ({LREC'18})},
}
```

