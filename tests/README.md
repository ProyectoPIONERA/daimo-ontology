# Ontology Tests

This folder contains all the **tests designed to verify that the ontology fulfills its defined requirements**.  
These tests ensure that the ontology correctly represents the intended knowledge, satisfies competency questions, and aligns with domain and stakeholder needs.

## 📘 Purpose
The goal of this directory is to store **validation and verification artifacts** that confirm the ontology behaves as expected.  
Testing helps guarantee the **quality, consistency, and completeness** of the ontology with respect to its requirements.

## 📂 Contents
Include here any files or scripts used to test the ontology, such as:

- **Themis tests** — Automated tests written in [Themis](https://themis.linkeddata.es/).
- **SPARQL queries** — To check that competency questions can be answered using the ontology.  
- **SHACL validation reports** — To verify data conforms to ontology constraints.  
- **Automated test scripts** — Implemented in Python, Java, or other languages to run ontology checks.  
- **Test datasets** — RDF or Turtle files used as input for validation.  
- **Test reports** — Documents summarizing results of ontology tests.

## 📄 Accepted Formats
You can use formats such as:
- `.rq` — SPARQL query files  
- `.py`, `.sh`, `.ipynb` — Automated testing scripts  
- `.ttl`, `.rdf`, `.jsonld` — Example data for testing  
- `.md`, `.pdf` — Reports or documentation of test outcomes  

## ⚙️ Best Practices
- Align each test with a **specific requirement or competency question**.  
- Keep test files **versioned** alongside ontology updates.  
- Automate testing where possible (e.g., GitHub Actions or CI workflows).  
- Document the expected outcomes of each test for reproducibility.  
- Store test data separately from production or example data.

## 🗂️ Notes
- This folder is for **requirement validation and ontology testing only** — not for implementation files or SHACL shapes themselves.  
- Consider organizing subfolders, e.g.:
  - `/competency-questions/`  
  - `/automated-tests/`  
  - `/reports/`