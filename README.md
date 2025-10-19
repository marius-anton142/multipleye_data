This repository is part of the MultiplEYE COST Action. It is used for data analysis, comparing different features across
languages, creating interactive graphs and other tools to facilitate the production of descriptive statistics
for languages, improving the representation of low resource languages, and creating a reusable pipeline for
data creation and visualisation.

The main output is a standardized pipeline used for generating cross-lingual features based on
relevant metrics, organized in a static site with easy to visualize graphs. The pipeline is integrated
using workflows for easy reproduction, it is modular based on specific language requirements, and
therefore easy to improve upon and extend by other people. The feature extraction produces csv dumps
which can be curated and modified, and then used for visualizing tables and plots, which should help with
finding anomalies and patterns for different languages. The features can be represented on multiple levels:
doc, page, sentence, and language. Special cases are also identified and treated accordingly, which might
offer a standardized method for dealing with issues involving certain languages (especially regarding
tokenization), useful for other tasks in the future.
