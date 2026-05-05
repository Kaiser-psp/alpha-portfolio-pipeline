# Alpha Portfolio Pipeline

## Overview
This pipeline fetches portfolio data from Poly Market and stores snapshots in Google Drive. Metadata and pipeline code are versioned in GitHub.

## Setup
1. **Google Drive**:
   - Folder: [`AlphaPortfolioData`](https://drive.google.com/drive/folders/1wBSlODrJkSnSXd81-vywHGBNjmMraSzw)
   - Share with collaborators as needed.

2. **GitHub**:
   - Repository: `alpha-portfolio-pipeline`
   - Secrets:
     - `GOOGLE_DRIVE_FOLDER_ID`: `1wBSlODrJkSnSXd81-vywHGBNjmMraSzw`

## Usage
- Run `python pipeline/fetch_data.py` to fetch data.
- Run `python pipeline/upload_to_drive.py` to upload to Google Drive.

## Automation
- GitHub Actions runs the pipeline daily at midnight UTC.

## Metadata
- Schema and snapshot history are stored in `metadata/`.

## Cost
- Free (Google Drive + GitHub).