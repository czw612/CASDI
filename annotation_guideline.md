# Annotation Guideline

The CASDI dataset is annotated for coronary artery stenosis localization and stenosis degree interval classification in X-ray angiography images.

## Annotation Type

Each stenotic lesion is annotated using a bounding box.

The annotation follows the YOLO object detection format:

```text
class_id x_center y_center width height
