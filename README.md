# MMF-Tracker: Multi-modal Multi-level Fusion for 3D Single Object Tracking (TIV 2023)

This is the official code release of "Multi-modal Multi-level Fusion for 3D Single Object Tracking"

## Abstract
3D single object tracking plays an important role in computer vision and autonomous driving. The mainstream methods mainly rely on point clouds to achieve geometry matching between target template and search area. However, textureless and incomplete point clouds make it difficult for single-modal trackers to distinguish objects with similar structures. To overcome the mentioned limitations of geometry matching, we propose a Multi-modal Multi-level Fusion Tracker (MMF-Track), which exploits the image texture and geometry characteristic of point clouds to track 3D target. Specifically, we first propose a Space Alignment Module (SAM) to align RGB images with point clouds in 3D space, which is the prerequisite for constructing inter-modal associations. After that, in feature interaction level, we present a Feature Interaction Module (FIM) based on dual-stream structure, which enhances intra-modal features in parallel and constructs inter-modal semantic associations. Meanwhile, in order to refine each modal feature, we propose a Coarse-to-Fine Interaction Module (CFIM) to realize the hierarchical feature interaction at different scales. Finally, in similarity fusion level, we introduce a Similarity Fusion Module (SFM) to aggregate geometry and texture similarity from the target. Extensive experiments show that our method achieves competitive performance on KITTI and NuScenes datasets.

## Method

## Code
Coming soon...
