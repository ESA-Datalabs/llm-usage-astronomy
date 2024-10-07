# llm-usage-astronomy
This repository contains the code used for the paper “Delving into the Utilisation of ChatGPT in Scientific Publications in Astronomy” as presented at the [SPAICE 2024 Conference](https://spaice.esa.int/), at ECSAT, Harwell, Oxfordshire, UK.

## Repository Structure

### data
+ count papers ai favs.json: the absolute occurence and its frequency per year for the top 100 AI-favoured words
+ count papers control.json: the absolute occurence and its frequency per year for 100 control words

### notebooks
+ human_vs_llm.ipynb: implementation of how to determine top AI words by token frequency from a dataset
+ llm_in_astronomy.ipynb: implementation of ADS NASA search for top 100 AI words vs 100 control words  

<br/>

+ LICENSE: the license under which you can reuse this code
+ README.md: you are reading it now :)

## Paper
Conference proceedings link: https://zenodo.org/records/13885577

```bibtex
@inproceedings{astarita_2024_13885577,
	doi = {10.5281/zenodo.13885577},
	month = oct,
	publisher = {Zenodo},
	title = {Delving into the Utilisation of ChatGPT in Scientific Publications in Astronomy},
        author={Simone Astarita and Sandor Kruk and Jan Reerink and Pablo Gómez}
	url = {https://doi.org/10.5281/zenodo.13885577},
	year = 2024
}
```

If you wish to cite the non-reviewed version (v1), you can get the one from arXiv.
arXiv link: https://arxiv.org/abs/2406.17324 (conference proceedings forthcoming)

```bibtex
@misc{astarita2024delvingutilisationchatgptscientific,
      title={Delving into the Utilisation of ChatGPT in Scientific Publications in Astronomy}, 
      author={Simone Astarita and Sandor Kruk and Jan Reerink and Pablo Gómez},
      year={2024},
      eprint={2406.17324},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2406.17324v1}
}
```
