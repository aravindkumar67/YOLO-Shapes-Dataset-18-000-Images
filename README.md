# YOLO Shapes Dataset — 18,000 Images

A synthetic object-detection dataset for training and evaluating YOLO models.

## Dataset overview

- **Images:** 18,000
- **Classes:** 60
- **Training:** 14,400 images
- **Validation:** 1,800 images
- **Testing:** 1,800 images

## Object categories

The dataset combines six colors, five shapes, and two apparent-size categories.

- **Colors:** red, blue, green, yellow, orange, purple
- **Shapes:** cube, cuboid, sphere, cone, cylinder
- **Size categories:** small, big

## Format

YOLO object-detection labels use normalized bounding-box coordinates:

`class_id x_center y_center width height`

The complete dataset archive includes `data.yaml`, image folders, label folders, and a dataset manifest.

## Limitations

This dataset is synthetic. Real-camera performance has not been validated, and model accuracy has not yet been established. Please inspect annotations and evaluate the model on a separate real-world test set before deployment.

## Download

The full dataset ZIP will be linked here once it is hosted and publicly accessible.
