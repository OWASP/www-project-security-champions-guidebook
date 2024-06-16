# OWASP Security Champions Guide

Proof of concept to use MKDocs to host our content (besides the OWASP project page).
Inspired by https://github.com/OWASP/API-Security and following the setup of https://github.com/OWASP/Top10/tree/master/2021.

## Building a local copy on Windows
Install python
python3 -m pip install -r requirements.txt
python3 -m pip install mkdocs

### Test it locally

python3 -m mkdocs serve to run website on http://127.0.0.1:8000/
python3 -m mkdocs build to generate site content for deployment