MuralDH
DOI: https://doi.org/10.5061/dryad.bnzs7h4jd

Brief Summary
The MuralDH dataset is a comprehensive collection of high-quality images for the digital restoration of Dunhuang murals. It includes over 5000 pre-processed images, curated to support research in digital art restoration, computer vision, and cultural heritage preservation. This dataset is divided into segments including damaged mural segmentation, high-resolution mural images, and images processed for super-resolution studies. The collection, designed to assist in the development and testing of digital restoration algorithms, aims to bridge traditional art with modern technology, ensuring the longevity and accessibility of these invaluable cultural treasures.

Description of the Data and File Structure
The dataset is structured as follows:

Damaged Mural Segmentation Dataset: 1000 images annotated for specific types of damage such as cracks, flaking, and fading. Each file is named according to its specific damage type and contains annotations at the pixel level.
High-Quality Mural Images: 500 images, each prepared for super-resolution processing. These are lower-resolution images that have been downscaled from the original high-resolution scans.
Super-Resolution Dataset: A subset of the High-Quality Mural Images that have been further processed for super-resolution studies.
Each image file is stored in PNG format, ensuring high-quality, lossless compression. Files are organized in folders corresponding to their dataset segment, and filenames follow a consistent naming convention to indicate their content and purpose.

Missing data or incomplete images are marked with a specific code (e.g., NA for not available) in the accompanying metadata file. This file also provides a detailed description of each image, including its original location, the period it depicts, and any relevant historical or cultural notes.

Sharing/Access Information
The MuralDH dataset is hosted on Dryad but can also be accessed through the following link for direct download and further information:

Access Link: http://example.com/muraldh-access
Data Derivation Sources
This dataset was compiled from various sources, including digital archives and collaborations with cultural heritage organizations. Each image has been carefully selected and processed to meet the research needs while adhering to copyright and preservation guidelines.

Code/Software
The dataset comes with a set of Python scripts for basic image processing tasks, including image resizing, format conversion, and initial analysis. These scripts were developed using Python 3.8, with dependencies on popular libraries such as NumPy for numerical operations, PIL for image processing tasks, and Matplotlib for generating visualizations.
