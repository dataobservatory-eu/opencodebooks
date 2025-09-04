# Open Codebooks

**Open, simple, reusable codebooks for coded datasets.**

Open Codebooks is not just a package — it’s a pattern.  
The idea is that **codebooks should be as open and portable as the data they describe**.

- **Hash URIs**: Every category gets a stable, citable identifier.  
- **Minimal**: Define codebooks in a plain CSV or data frame.  
- **Templated**: Render them into human-readable HTML and machine-readable Turtle (SKOS).  
- **Static**: Publish on GitHub Pages, GitLab Pages, or any static host. No server config.  

This repository holds the **templates and workflow definition**.  
The first implementation is in **R**, via the [`rOpenCodebooks`](https://github.com/dataobservatory-eu/rOpenCodebooks) package.  
But the design is language-agnostic: we hope to see implementations in **Python**, **Julia**, and other environments where people work with coded datasets.  

---

## Why?

Surveys, statistics, and research data often use categorical variables.  
To make these datasets **comparable and FAIR**, the categories must be:

- Clearly defined  
- Linked to stable identifiers  
- Published in reusable formats  

Open Codebooks makes this easy — for one question, one dataset, or across a whole survey program.  

---

## Roadmap

- ✅ Reference implementation in R  
- 🔜 Ports to Python and Julia  
- 🔜 Community registry of common codebooks (e.g. agreement scales, trust scales, SDMX extensions)  

---

## License

MIT — free to use, adapt, and port.  
