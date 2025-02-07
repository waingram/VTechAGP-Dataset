# VTechAGP: An Academic-to-General-Audience Text Paraphrase Dataset

## Variable Descriptions
This dataset contains the following columns:

- **identifier_url**: Persistent identifier (CNRI handle) for the ETD.  
- **title**: Title of the ETD.  
- **abstract**: Regular abstract for the ETD.  
- **abstract_general**: General audience abstract for the ETD.  
- **subject_terms**: List of subject terms for the ETD.  
- **discipline**: Field of study for the degree awarded.  
- **department**: Name of the academic department.  
- **degree**: Degree awarded.  
- **degree_level**: Level of the degree (e.g., 'doctoral' or 'masters').  
- **type**: Type of ETD (e.g., 'thesis' or 'dissertation').  

## Methodology
This dataset was collected from Virginia Tech's institutional repository,  
[VTechWorks](https://vtechworks.lib.vt.edu/), using the Open Archives  
Initiative Protocol for Metadata Harvesting (OAI-PMH) on September 22, 2023.

## Citing This Dataset
If you use this dataset in your research, please cite the following paper:  

```bibtex
@article{ming2024vtechagp,
  author       = {Ming Cheng and
                  Jiaying Gong and
                  Chenhan Yuan and
                  William A. Ingram and
                  Edward A. Fox and
                  Hoda Eldardiry},
  title        = {VTechAGP: An Academic-to-General-Audience Text Paraphrase Dataset and Benchmark Models},
  journal      = {CoRR},
  volume       = {abs/2411.04825},
  year         = {2024},
  doi          = {10.48550/arXiv.2411.04825},
  eprinttype   = {arXiv},
  eprint       = {2411.04825}
}
```

## Ethical & Usage Considerations
- **Publicly Available Data**: All ETD metadata in this dataset was collected from publicly available sources in compliance with institutional repository policies.  
- **Attribution**: Users of this dataset should respect citation norms
  and acknowledge the original authors of the ETDs when appropriate.  

## Acknowledgment
This project was made possible in part by the Institute of Museum and Library Services  
[LG-256638-OLS-24](https://www.imls.gov/grants/awarded/lg-256638-ols-24).

## License
This dataset is released under the [Open Data Commons Attribution License (ODC-By)](https://opendatacommons.org/licenses/by/summary/).