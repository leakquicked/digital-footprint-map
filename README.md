# Digital Footprint Map

Categorize manually collected public references.

## Usage
```bash
python digital_footprint_map.py sample.txt
python digital_footprint_map.py sample.txt --output report.json
```

Python 3.10+; standard library only. Reads only a local UTF-8 text file. No network access, scraping, or source-file modification.

## Detection rules
- `social`: info heuristic
- `contact`: review heuristic
- `location`: review heuristic

Results are heuristic and require human validation. Use only public information or data you are authorized to review. Avoid committing personal or confidential data.

## Tests
`python -m unittest discover -s tests -v`
