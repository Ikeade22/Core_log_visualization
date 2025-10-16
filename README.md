# Core_log_visualization
A Python focuses on organizing and visualizing well log data for reservoir characterization.
It extracts well names, depth information, and image paths from structured data files, then generates a comprehensive dataset (CSV file) that includes file paths, top and bottom depths, and image URLs for each well.

The project also demonstrates how to automate image uploads to Google Drive and generate shareable URLs for easy access and visualization.

It serves as a practical workflow for geoscientists and data scientists working on digital core analysis, well log interpretation, or reservoir studies.

Key Features:

Automated extraction of well name, top depth, and bottom depth from image filenames.

Dynamic creation of a clean, structured dataset using pandas.

Optional integration with Google Drive API to upload and generate shareable image URLs.

CSV export for use in Excel, Google Sheets, or Power BI.

Built-in .gitignore setup to prevent large image folders from being pushed to GitHub.

Technologies Used:

Python (pandas, os, IPython.display)

Jupyter Notebook / VS Code

Git & GitHub

Google Drive API (for cloud integration)

Project Structure:
LECTURE_HUB_NEW/
│
├── well_data_script.ipynb          # Main processing notebook
├── well_data_with_images.csv       # Generated dataset
├── .gitignore                      # Git ignore rules
├── venv/                           # Virtual environment (ignored)
├── well_ 6506_12_6/                # Local image folder (ignored)
└── README.md                       # Project description
