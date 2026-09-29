# Green Building Design with OR Techniques

Source code for:

> Aghapour, R., Jones, E. C. Jr., & Alavi, S. (2024). **Green Building Design Surrogate Optimization: Exploring Off the Shelf Machine Learning and Mixed Integer Programming Integrations.** *Proceedings of the 9th North American Conference on Industrial Engineering and Operations Management*, Washington D.C., June 4–6, 2024. IEOM Society International. https://doi.org/10.46254/NA09.20240139

**Paper (free PDF):** https://ieomsociety.org/proceedings/2024northamerica/139.pdf

Status: published artifact — the notebooks behind the paper's results; not yet verified from a clean clone.

## Contents

| Folder | Surrogate model | Targets |
|---|---|---|
| `CART_Analysis/` | Classification and regression trees | Cost, GWP, HHP, and a multi-target tree |
| `GradienBoost_analysis/` | Gradient boosting (V3 is current; `Archive/` holds V2) | Cost, GWP, HHP, and a multi-target model |
| `RandomForest_analysis/` | Random forest (V2 is current; `Archive/` holds V1) | Cost, GWP, HHP, and a multi-target model |

## How to cite

```bibtex
@inproceedings{aghapour2024greenbuilding,
  author    = {Aghapour, Raziye and Jones, Jr., Erick C. and Alavi, Sarasadat},
  title     = {Green Building Design Surrogate Optimization: Exploring Off the Shelf Machine Learning and Mixed Integer Programming Integrations},
  booktitle = {Proceedings of the 9th North American Conference on Industrial Engineering and Operations Management},
  address   = {Washington D.C., USA},
  year      = {2024},
  publisher = {IEOM Society International},
  doi       = {10.46254/NA09.20240139}
}
```

## License

Code: MIT — see [LICENSE](LICENSE). The paper itself is © IEOM Society International and is not included here.
