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

Example: `nistspectrum=Fe+II.webdump.dat`
 
    Configuration	  Term	    J	      Prefix	Level (cm-1)	  Suffix
     "3d6.(5D).4s"	  "a 6D"    "9/2"     ""        "0.0000"          ""	
     "3d6.(5D).4s"	  "a 6D"    "7/2"     ""        "384.7872"        ""	
     "3d6.(5D).4s"	  "a 6D"    "5/2"     ""        "667.6829"        ""	
     "3d6.(5D).4s"	  "a 6D"    "3/2"     ""        "862.6118"        ""	
     "3d6.(5D).4s"	  "a 6D"    "1/2"     ""        "977.0498"        ""	
     "3d7"	          "a 4F"    "9/2"     ""        "1872.5998"       ""	
     "3d7"	          "a 4F"    "7/2"     ""        "2430.1369"       ""	
     "3d7"	          "a 4F"    "5/2"     ""        "2837.9807"       ""	
     "3d7"	          "a 4F"    "3/2"     ""        "3117.4877"       ""	
     "3d6.(5D).4s"	  "a 4D"    "7/2"     ""        "7955.3186"       ""	
     "3d6.(5D).4s"	  "a 4D"    "5/2"     ""        "8391.9554"       ""	
     "3d6.(5D).4s"	  "a 4D"    "3/2"     ""        "8680.4706"       ""	
     "3d6.(5D).4s"	  "a 4D"    "1/2"     ""        "8846.7837"       ""	

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
