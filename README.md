# Active Learning Pipeline

[![Earth ArXiv Preprint
DOI](https://img.shields.io/badge/%F0%9F%8C%8D%F0%9F%8C%8F%F0%9F%8C%8E%20EarthArXiv-doi.org%2F10.31223%2FX5JW23-%23FF7F2A)](https://doi.org/10.31223/X5JW23)

These codes are the glue, they:

- do inference with the ML model ([WashoverML](https://github.com/UNCG-DAISY/WashoverML)) and save scores.
- join inferences with [Coastal Image Labeler](https://github.com/UNCG-DAISY/Coastal-Image-Labeler) data to display on [Storm Impact Map](https://github.com/UNCG-DAISY/StormImpactMap).
- decide which images need hand labeling on the [Coastal Image Labeler](https://github.com/UNCG-DAISY/Coastal-Image-Labeler).
- generate gradCAM images
- Build new models with newly labeled data
- test against the hurricane michael data
- manage csvs
- ....
