# NIST_ASD_Data

## Overview
This repository provides Python tools for retrieving and processing atomic structure data from the [NIST Atomic Spectra Database (ASD)](https://physics.nist.gov/PhysRefData/ASD/). It enables users to query energy levels, transition probabilities, and spectral line data, facilitating research in atomic physics, astrophysics, and radiative transfer modeling.

## Features
- Query NIST ASD for atomic energy levels and transitions.
- Parse and structure retrieved data for easy analysis.
- Export data in structured formats for further processing.
- Support for Non-LTE radiative transfer applications.

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/afloers/NIST_ASD_Data.git
cd NIST_ASD_Data
pip install -r requirements.txt
```

## Usage
### Querying NIST ASD Data
Run the main script to fetch atomic structure data:

```bash
python fetch_nist_asd.py --element Fe --ion 2
```

This command retrieves data for doubly ionized iron (Fe II).

### Exporting Data
The retrieved data can be saved as CSV or JSON for further use:

```bash
python fetch_nist_asd.py --element Fe --ion 2 --output format=json
```

## Dependencies
- Python 3.x
- `requests` (for web queries)
- `pandas` (for data processing)

Install dependencies using:

```bash
pip install -r requirements.txt
```

## License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments
Data is sourced from the NIST Atomic Spectra Database. For citation and proper use, refer to the official [NIST ASD documentation](https://physics.nist.gov/PhysRefData/ASD/).

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.
