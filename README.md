# SL2E-Dependency-Treebank

## Basic information
This repository includes the Dependency Treebank of Spoken L2 English (SL2E).

## Annotation guidelines
All
Fine-grained part of speech tags (XPOS) were based on the Penn Treebank Tagset and were manually annotated from scratch by at least two annotators. The XPOS annotation guidelines <a href="https://kristopherkyle.github.io/L2-Annotation-Project/anno_overview.html" target="_blank">can be found here</a>. Dependency annotations followed the Universal Dependencies (version 2.0) and were also manually annotated from scratch by at least two trained annotators.  Dependency annotation guidelines <a href="https://kristopherkyle.github.io/L2-Annotation-Project/dep_anno_overview.html" target="_blank">can be found here</a>. 

Universal part of speech tags (UPOS) were added to the portion of the treebank that includes dependency annotation using a probabilistic model trained using both L1 and L2 sections of the English UD treebanks (EWT, GUM, GUMReddit, Pronouns, PUD, and ESL). Automatic tagging accuracy was .9885 (macro accuracy), and all tags acheived an f1 above .97. Subsequent manual fixes to the UPOS tags were also made.

## Citation
If you use the treebank in your research, please cite the following paper:
Kyle, K., Eguchi, M., Miller, A., & Sither, T. (2022). *A dependency treebank of spoken second language English*. In *Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics: Innovative Use of NLP for Building Educational Applications (BEA 2022)*, pp. 39-45., Seattle, USA. Association for Computational Linguistics. <a href="https://aclanthology.org/2022.bea-1.7.pdf" target="_blank">pdf</a>

## To Do
Add more information about POS Treebank and Dependency Treebank

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
