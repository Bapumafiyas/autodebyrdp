worker: user:
  name: ishikki
  github: ishikki-akabane

language: "python"
python_version: "3.10"

commands:
  build:
    - "pip install -r requirements.txt"
  package:
    - "nano inxi"
  start:
    - python3 main.py

env:
  - "ENVIRONMENT=production"
