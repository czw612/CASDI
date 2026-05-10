# CASDI: Coronary Artery Stenosis Degree Interval Dataset

CASDI is a coronary artery stenosis detection dataset for X-ray angiography (XRA) images. It is designed for stenosis localization and stenosis degree interval classification.

## Dataset Description

The CASDI dataset contains XRA images annotated with stenotic lesion bounding boxes and stenosis degree interval labels. Each annotation provides the location of a stenotic lesion and its corresponding severity interval.

The preview subset can be downloaded from the GitHub Releases section.

This repository currently provides only a small anonymized subset of CASDI for data-format preview. The complete CASDI dataset will be publicly released after the corresponding paper is accepted.

## Classes

| Class ID | Label | Stenosis degree |
|---|---|---|
| 0 | P0_50 | < 50% |
| 1 | P50_70 | 50%--69% |
| 2 | P70_90 | 70%--89% |
| 3 | P90_99 | 90%--99% |
| 4 | P100 | 100% |

## Annotation Format

The annotations follow the YOLO object detection format:

```text
class_id x_center y_center width height
