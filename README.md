# Computer Vision & Structural Recognition Methods

University coursework (Igor Sikorsky KPI, Applied Mathematics): classical image processing with OpenCV and NumPy (often implemented both with library calls and by hand), followed by object detection and neural-network image classification.

**Stack:** Python, OpenCV, NumPy, SciPy, scikit-image, scikit-learn, TensorFlow / Keras, Ultralytics YOLOv8

## Notebooks

| # | Notebook | Task | Methods |
|---|----------|------|---------|
| 1 | [01_color_channels.ipynb](01_color_channels.ipynb) | Color spaces | Channel splitting and recombination (RGB / BGR / GRB…) |
| 2 | [02_color_balancing.ipynb](02_color_balancing.ipynb) | Color correction | Intensity histograms, White Patch, Gray World, Scale-by-Max |
| 3 | [03_pixel_ops_filters_morphology.ipynb](03_pixel_ops_filters_morphology.ipynb) | Basic image operations, library vs. from-scratch implementations | Inversion, brightness shift, channel decomposition, blending, median filter, dilation, erosion, Sobel filter, watermark embedding & removal |
| 4 | [04_edge_detection_canny_hough.ipynb](04_edge_detection_canny_hough.ipynb) | Edge and line detection | Canny edge detector, Hough transform, K-Means |
| 5 | [05_color_quantization_dithering.ipynb](05_color_quantization_dithering.ipynb) | Color quantization | Fixed-palette quantization with error measurement (RMSE), Floyd–Steinberg dithering, K-Means palette |
| 6a | [06_detection/06a_face_detection_haar.ipynb](06_detection/06a_face_detection_haar.ipynb) | Face detection | Haar cascades, robustness tests (hats, glasses, multiple faces) |
| 6b | [06_detection/06b_yolov8_object_tracking.ipynb](06_detection/06b_yolov8_object_tracking.ipynb) | Object detection & tracking on video | YOLOv8n detection + tracking, frame-by-frame video processing |
| 7a | [07_traffic_signs/07a_traffic_sign_mlp_classifier.ipynb](07_traffic_signs/07a_traffic_sign_mlp_classifier.ipynb) | Binary traffic-sign classification (~4.5k images) | Preprocessing, fully connected network in Keras, comparison of architectures — **accuracy ≈ 0.96** |
| 7b | [07_traffic_signs/07b_gtsrb_dataset_exploration.ipynb](07_traffic_signs/07b_gtsrb_dataset_exploration.ipynb) | Dataset analysis before training | Class distribution, image size and brightness statistics |
| 8a | [08_cifar10_cnn/08a_cifar10_cnn_baselines.ipynb](08_cifar10_cnn/08a_cifar10_cnn_baselines.ipynb) | CIFAR-10 image classification (10 classes) | Several CNN architectures, reproducible seeds, learning curves, per-class accuracy — **test accuracy ≈ 0.70** for the baseline CNN |
| 8b | [08_cifar10_cnn/08b_cifar10_cnn_regularization.ipynb](08_cifar10_cnn/08b_cifar10_cnn_regularization.ipynb) | Fighting overfitting | Dropout, Batch Normalization, Early Stopping; train vs. validation comparison |
| 9 | [09_poisson_image_editing.ipynb](09_poisson_image_editing.ipynb) | Inpainting & seamless cloning | Gradient-domain editing solved as a sparse least-squares system (SciPy sparse) |
| 10 | [10_keystroke_dynamics_auth.ipynb](10_keystroke_dynamics_auth.ipynb) | Biometric authentication by typing rhythm | Keystroke timing profile (mean / std), statistical threshold test |
| 11 | [11_char_bigram_text_analyzer.ipynb](11_char_bigram_text_analyzer.ipynb) | Statistical text analysis | Character-bigram frequency model with a small Tkinter GUI |
| M1 | [mkr1_document_corner_detection.ipynb](mkr1_document_corner_detection.ipynb) | Find document corners in a photo | Harris corner detector, corner selection heuristics |
| M2 | [mkr2_document_alignment_homography.ipynb](mkr2_document_alignment_homography.ipynb) | Rectify a photographed document | Affine transform vs. homography — homography gives correct perspective alignment |

## Notes
- Images, videos, and datasets are not included in the repository because of their size.
