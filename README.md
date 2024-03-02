# Useful Commands and Scripts
This repository contains all the commands and scripts which are useful. I keep forgetting them so putting them here for future reference. These are the commands which are not used very frequently but are very handy whenever there is a need. 

## 1. Download files from Google Drive using curl
Replace the `fileId` with the id of the file in google drive and `filename` with the name you want to save your file with.
```bash
curl -L "https://drive.usercontent.google.com/download?id={fileId}&confirm=xxx" -o {filename}
```

