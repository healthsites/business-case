# The Business Case for Accurate Baseline Health Facility Data

Documentation: [CC BY 4.0](LICENSE-docs.md) · Code: [BSD-3-Clause](LICENSE) · Health facility data: ODbL 1.0 (© OpenStreetMap contributors)

What does inaccurate health facility data cost, who pays for it, and why hasn't anyone fixed it?

This repository holds the research, method and results of a student partnership between [healthsites.io](https://healthsites.io) and the Computational Social Science (CSSci) programme at the University of Amsterdam. The team compares an official facility list with the healthsites.io / OpenStreetMap dataset for one country, measures the discrepancy, and converts it into a cost estimate.

**Start with the [wiki](https://github.com/healthsites/business-case/wiki)** for the research framing, project plan, data sources and guardrails.

## Contents

```text
docs/        # Report drafts, stakeholder analysis, data source annotations
notebooks/   # The analysis notebook: raw import → matched data → cost estimate
data/        # Small, shareable derived datasets (raw downloads are git-ignored)
```

## Running the notebook

```bash
git clone https://github.com/healthsites/business-case.git
cd business-case
python3 -m venv venv
source venv/bin/activate          # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter lab notebooks/
```

## Licensing

| What | Licence | You may | You must |
|---|---|---|---|
| Documentation, wiki, report, slides | [CC BY 4.0](LICENSE-docs.md) | Share and adapt, including commercially | Credit the authors, link the licence, say what you changed |
| Code and notebooks | [BSD-3-Clause](LICENSE) | Use, modify, redistribute | Keep the copyright notice |
| healthsites.io / OSM data extracts | [ODbL 1.0](https://opendatacommons.org/licenses/odbl/) | Use and adapt | Credit "© OpenStreetMap contributors"; share adapted databases under ODbL |

Contributors agree that their contributions are published under these licences.

## How to cite

Use the **Cite this repository** button on GitHub, or see [`CITATION.cff`](CITATION.cff).

## Contributing

1. Create a branch: `git checkout -b topic/short-description`
2. Commit your changes with a clear message.
3. Open a pull request against `main`.

Never commit patient-identifying or facility-security-sensitive information. See the [Guardrails](https://github.com/healthsites/business-case/wiki/Guardrails) page.

## Contact

- Issues: GitHub Issues
- Website: [healthsites.io](https://healthsites.io)
