# Codeforces-Sheet-Generator

It's a simple script to generate a mushup on code forces, the script will accept the public problem urls only or polygon problems.

## Requirements

- Copy the `.env.example` file and rename it to `.env` and provide the required environment variables.
  - CODEFORCES_HANDLE
  - CODEFORCES_PASSWORD
  - SHEET_NAME
  - SHEET_DURATION
- Copy the urls of the problems to `Problems_Links.txt`

```bash
# install requirements
pip3 install -r requirements.txt
```

## Running the script

```bash
python3 Sheet_Generator.py
```
