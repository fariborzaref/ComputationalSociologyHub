# ComputationalSociologyHub

**Computational Methods for the Study of Social Structure**

Fariborz Aref, PhD · [fariborzaref.com](https://fariborzaref.com) · ORCID [0000-0001-6622-1824](https://orcid.org/0000-0001-6622-1824)

---

## Purpose

Computational sociology is not a new discipline. It is the old discipline with new instruments. Marx read factory inspectors' reports because they were the largest dataset his century produced; the questions he asked of them, about who works, who owns, and who bears the cost of economic change, are the questions we now ask of administrative microdata, digitized text, and machine-readable policy corpora. What has changed is scale, and scale changes what can be seen: patterns that are invisible in a hundred cases become legible in a million.

This repository holds the computational layer of my research program on inequality, welfare regimes, and the transformation of work. It is the third of three connected repositories. [QuantitativeSocietyLab](https://github.com/fariborzaref/QuantitativeSocietyLab) contains the statistical models; [QualitativeSocietyLab](https://github.com/fariborzaref/QualitativeSocietyLab) contains the interpretive frameworks; this hub contains the methods that operate at scales neither of the others can reach. Materials are released in stages as the underlying studies move through review and publication.

## The Analytical Program

**Text as Data.** Institutions speak in documents: legislation, party manifestos, agency reports, mission statements. Topic models, embeddings, and dictionary methods here treat those corpora as evidence about institutional ideology and change, designed to interoperate with the close-reading frameworks of the qualitative repository so that scale and meaning discipline one another.

**Networks.** Stratification is relational before it is distributional. Network methods here examine how positions, organizations, and states are tied together, and how advantage travels along those ties.

**Automation, AI, and the Future of Work.** An ongoing project examines how occupational exposure to artificial intelligence interacts with welfare regime type across OECD countries: whether the institutions that buffered earlier economic shocks also buffer this one. The pipeline links occupational exposure scores to comparative microdata, and the code will be released alongside the resulting publications.

**Simulation and Agent-Based Models.** Some social processes can only be understood by growing them. Simulation here serves comparative and policy questions: what macro-level distributions emerge from micro-level rules under different institutional arrangements.

**Reproducible Pipelines.** Every analysis is built as a pipeline from raw source to published figure, so that the path from data to claim is inspectable at every step. Reproducibility is not a technical courtesy; it is the computational form of the discipline's oldest norm, that findings must be checkable by people who do not trust you.

## Planned Architecture

Modules will be added as the corresponding studies conclude:

```
/Text_Analysis        Topic models, embeddings, and corpus construction for institutional text
/Networks             Relational data construction and network analysis
/AI_Labor_Welfare     Occupational AI exposure and welfare regime interaction (in progress)
/Simulation           Agent-based and scenario models for comparative policy analysis
/Pipelines            Reusable workflow templates for reproducible research
```

## Toolchain

`Python` · `R` · `Git` · `LaTeX`

Code is annotated so that the reasoning, not merely the execution, can be reconstructed. Where data licensing prevents redistribution (as with LIS and similar comparative microdata), the repository documents sources, access procedures, and exact processing steps so that replication remains possible for credentialed researchers.

## License

Code is released under the [MIT License](https://opensource.org/licenses/MIT). Documentation and text materials are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite when building on this work.

## Citation

Aref, F. (2026). *ComputationalSociologyHub: Computational methods for the study of social structure* [Computer software]. GitHub. https://github.com/fariborzaref/ComputationalSociologyHub

---

§
