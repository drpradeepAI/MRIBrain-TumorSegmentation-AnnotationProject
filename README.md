🧠 MRI Brain Tumor Segmentation — Annotation Project

It’s written in the same sleek, globally impressive style as your X-ray and CT releases — highlighting research clarity, freelancing appeal, and dataset professionalism.

🧠 MRI Brain Tumor Segmentation — Annotation Project

Medical AI Data Annotation Portfolio | CVAT-Based Segmentation Dataset

A curated dataset of 50 MRI brain scans annotated for tumor segmentation using CVAT.
This project demonstrates a complete medical computer vision workflow — from raw data curation to pixel-level tumor segmentation — designed for AI model development, validation, and educational research.

📁 Included Folders

raw_data/ → 50 unannotated MRI brain scans

annotated_data/ → COCO, VOC, and PNG segmentation exports

metadata/ → Dataset descriptors and mapping files

screenshots/ → Visual documentation and export proofs

🔍 Annotation Details
Attribute	Description
Tool	CVAT (Computer Vision Annotation Tool)
Task Type	Semantic Segmentation
Segmentation Classes	tumor, background
Annotation Type	Polygonal + Mask Segmentation
Export Formats	COCO JSON, Pascal VOC XML, PNG Masks
Resolution	512 × 512 px
Color Mode	Grayscale
Dataset Size	50 MRI brain images
Primary Use	Medical AI model training, validation, and demonstration
🧠 Applications

Tumor boundary detection and morphological segmentation

U-Net, MONAI, and DeepLab model training and benchmarking

Educational visualization of radiological annotation workflows

Freelance medical dataset packaging and demonstration

Research reproducibility and documentation projects

⚙️ Data Workflow Summary
Step	Description
1. Data Preparation	MRI brain scans curated and standardized for annotation
2. Annotation (CVAT)	Manual tumor segmentation using polygon and brush tools
3. Exporting Formats	Converted to COCO JSON, Pascal VOC XML, and PNG mask formats
4. Documentation	Project screenshots, workflow reports, and metadata
5. Validation	Visual and logical QA for accuracy and consistency
🧰 Recommended Tools
Task	Recommended Tools
Annotation	CVAT, ITK-SNAP, 3D Slicer
Visualization	FiftyOne, OpenCV, matplotlib
Model Training	MONAI, U-Net, Detectron2, TensorFlow OD API
Validation	Dice, IoU, Hausdorff Distance metrics
🔗 Compatibility
Framework	Format	Folder
PyTorch / Detectron2	COCO JSON	annotated_data/COCO
YOLOv5–YOLOv8	YOLO TXT	annotated_data/YOLO
CVAT	XML	annotated_data/cvat_xml
MONAI / U-Net	PNG Masks	annotated_data/segmentation_masks
📜 License

Licensed under the MIT License.
© 2025 Dr. Pradeep Shanmugam — MedDataForAI (Udyam Registered MSME, Government of India)

🔖 Citation (APA Style)

Shanmugam, P. (2025). MRI Brain Tumor Segmentation — Medical AI Data Annotation Project (v1.0).
MedDataForAI (Udyam Registered MSME, Government of India).
Available at: https://github.com/drpradeepAI/MRIBrain-TumorSegmentation-AnnotationProject
