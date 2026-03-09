# PrivCORPUS: 
This repository contains sanitised Privacy Policy (PP) and Google Play Data Safety (DS) Declaration resrouces as detailed below.

## Related Publications
Refer to the following publications for detailed explanations

01. PrivPRISM [link to be updated]
02. PrivXXXXXX [to be updated]

## Repository Structure
```text
├── PP_Games_TXT/                   # A collection of 7770 game PP santised text
│   ├── <app_id>_policy.txt/        
├── PP_Generic_TXT/                 # A collection of 6540 non-game PP santised text
│   ├── <app_id>_policy.txt/  
├── DS_Games/                       # Sanitised version of the DS declarations of games
│   ├── <app_id>_data_safety.txt/   # Only the follwing tags are added in begining of each line, other metadata not modified
│   │   ├──<d_prac>                 # Tag represents: Data collection, sharing or security
│   │   │   ├──<d_detl>             # Tag represents: An explanatory text
│   │   │   ├──<d_cata>             # Tag represents: Data item categories, e.g. Location
│   │   │   │   ├──<d_attr>         # Tag represents: Data item attributes, e.g. Fine Location
│   │   │   │   │   ├──<d_val>      # Tag represents: Data purpose, e.g. App Functionality
├── DS_Generic/                     # Sanitised version of the DS declarations of non-games, follows similar tagging
```
Note: Please contact the authors if you requre access to .APK files.
Contact: bpin9254@sydney.edu.au

## Citation
If you use the datasets or frameworks in this repository for your research, please cite the corresponding papers:
```text
@misc{silva2026privprism,
      title={{PrivPRISM}: Automatically Detecting Discrepancies Between Google Play Data Safety Declarations and Developer Privacy Policies}, 
      author={Bhanuka Silva and Dishanika Denipitiyage and Anirban Mahanti and Aruna Seneviratne and Suranga Seneviratne},
      year={2026},
      eprint={},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={}, 
}
```

## Update History
2026.03.10 - Initial upload of the corpus
To be uploaded - Raw HTML files for PP and DS (contact authors if you require the resources prior to release)