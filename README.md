# Active Learning Pipeline

These codes are the glue, they:

- do inference with the ML model ([WashoverML](https://github.com/UNCG-DAISY/WashoverML)) and save scores.
- join inferences with [Coastal Image Labeler](https://github.com/UNCG-DAISY/Coastal-Image-Labeler) data to display on [Storm Impact Map](https://github.com/UNCG-DAISY/StormImpactMap).
- decide which images need hand labeling on the [Coastal Image Labeler](https://github.com/UNCG-DAISY/Coastal-Image-Labeler).

-generate gradCAM images
-Build new models with newly labeled data
-test against the hurricane michael data
-manage csvs
-....