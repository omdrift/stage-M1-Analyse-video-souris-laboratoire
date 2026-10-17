# Laboratory mouse pose estimation and tracking

**Computer Vision research internship · L3i Laboratory · April–June 2025**

Amine Oubaidi · MSc Computer Science, La Rochelle University

Adaptation of a keypoint detection workflow to top-view videos of laboratory mice, with an inspection interface for reviewing poses and tracking outputs.

[Read the internship report (PDF)](Rapport_de_stage_Amine_Oubaidi_M1_INFO.pdf) · [Visual case study](https://oubaidiamine-portfolio.netlify.app/#experience-mice) · [Recommendation letter](https://github.com/omdrift/oubaidiamine-portfolio/blob/main/amine-portfolio/documents/recommandation-l3i-2025.pdf)

## Problem

Track two interacting mice and estimate their anatomical keypoints in laboratory videos. Overlapping animals, changes in appearance and differences between public training footage and the laboratory recordings make detection and identity continuity difficult.

## My contribution

- Reframed the initial tracking task with my supervisor when the originally planned software was unavailable.
- Reviewed animal pose-estimation methods and selected the MARS dataset as a starting point.
- Prepared and annotated laboratory data, adapted Keypoint R-CNN to seven anatomical points per mouse, and experimented with augmentation.
- Ran training experiments on the L3i compute server and inspected difficult interactions and detection failures.
- Built a PyQt5 interface to review predictions and adjust processing parameters; documented the approach and its limitations in the report.

**Stack:** Python · PyTorch · Keypoint R-CNN / ResNet50-FPN · OpenCV · MARS · PyQt5 · Linux

## Inspect the work

![Example of mouse tracking output](https://raw.githubusercontent.com/omdrift/oubaidiamine-portfolio/main/amine-portfolio/images/mice/mice-tracking.png)

The [report](Rapport_de_stage_Amine_Oubaidi_M1_INFO.pdf) describes the research context, data preparation, model adaptation and experimental observations. The [portfolio case study](https://oubaidiamine-portfolio.netlify.app/#experience-mice) presents annotations, pose examples and tracking outputs.

## Repository contents and scope

This repository publishes the internship report. It does not include a runnable training package or the laboratory video dataset. The results describe a research prototype evaluated under the acquisition conditions discussed in the report; difficult interactions and identity continuity remain part of the analysis.

## Contact

[Amine Oubaidi](https://github.com/omdrift) · [Portfolio](https://oubaidiamine-portfolio.netlify.app/) · [Email](mailto:amine.oubaidi010@gmail.com)
