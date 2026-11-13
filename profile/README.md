<p align="center">
  <img src="https://raw.githubusercontent.com/quillbench/quillbench/main/docs/logo.svg" width="110" alt="QuillBench logo">
</p>

<h1 align="center">QuillBench</h1>

<p align="center">
  <b>Build benchmark datasets with human annotators.</b><br>
  A config-driven annotation platform for research teams.
</p>

<p align="center">
  <a href="https://pypi.org/project/quillbench/"><img src="https://img.shields.io/pypi/v/quillbench?color=4b6bfb" alt="PyPI"></a>
  <img src="https://img.shields.io/pypi/pyversions/quillbench" alt="Python 3.10+">
  <img src="https://img.shields.io/badge/license-academic%20non--commercial-lightgrey" alt="License: academic, non-commercial">
</p>

---

QuillBench helps a research group turn raw items into a clean, documented benchmark.
Each paper keeps its annotation data in its own folder, described by a single YAML file.
Annotators work in the browser, and the answers go straight into that folder.

### What it does

- **Annotation studies.** Ratings on a slider, label choices, short text answers, and query review tasks, with hidden attention checks and practice items.
- **Writing benchmarks with people.** Annotators read a database schema, write a question and its query, run it, and add it to the benchmark. Near-duplicate questions are rejected automatically.
- **Works with real databases.** PostgreSQL, MySQL/MariaDB, SQLite and Neo4j (Cypher).
- **Quality you can report.** Krippendorff's alpha, Cohen's kappa, check-item pass rates and time per item, with anonymised exports and a generated datasheet.
- **Ready for a lab server.** Runs as a service with nightly backups and optional university (LDAP) sign-in.

### Quick start

```bash
pip install quillbench
quillbench user add YOURNAME --admin
quillbench serve            # http://localhost:8560/quillbench/
```

### Repositories

| Repository | What it is |
|---|---|
| [**quillbench**](https://github.com/quillbench/quillbench) | The annotation platform: Python package, web studio and command-line tool |

### Learn more

- [README and full feature guide](https://github.com/quillbench/quillbench#readme)
- [Admin guide](https://github.com/quillbench/quillbench/blob/main/docs/admin-guide.md)
- [Setting up a shared Ubuntu server](https://github.com/quillbench/quillbench/blob/main/docs/install-ubuntu.md)

---

<sub>Created and maintained by <a href="https://arjunpogaku.github.io">A.C. Pogaku</a>. Free for academic, non-commercial use.</sub>
