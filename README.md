
<!-- README.md is generated from README.Rmd. Please edit that file -->
NegationDataset
===============

This repository provides annotations of negation scopes for 500 sentences from IMDb movie reviews. The dataset is labeled manually by two external persons (Annotator A and Annotator B). Each sentence contains at least one explicit negation phrase from the list of Jia et al. (2009). The labeled sentences can, for example, be used in machine learning models that aim at learning accurate negation scopes for sentiment analysis. Details are available from the following reference.

-   Pröllochs, Feuerriegel and Neumann (2017): Understanding Negations in Information Processing: Learning from Replicating Human Behavior, Working Paper, Chair for Information Systems Research, University of Freiburg, Germany.

Details
-------

This library contains the following resources in CSV format.

-   **Negation Labels Annotator A:** This file contains the annotations from Annotator A (sentences\_annotator\_a.csv).
-   **Negation Labels Annotator B:** This file contains the annotations from Annotator B (sentences\_annotator\_b.csv).

The individual columns of each resource are as follows:

-   **Id:** This column assigns a unique Id to each sentence.

-   **Sentence:** This column contains the sentences that are labeled by the two human annotators.

-   **IsNegated:** This column contains the negation pattern for each sentence. The value *T* denotes that a word is marked as *negated* by the human annotator, whereas *F* denotes that the word is marked as *not negated*.

License
-------

**NegationDataset** is released under the [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2017 Nicolas Pröllochs & Stefan Feuerriegel
