# Ontology Development Repository

This repository contains all the resources required for the **development, documentation, validation, and implementation of an ontology**.  
It serves as the central workspace for managing every stage of the ontology lifecycle — from requirements gathering and conceptualization to implementation, testing, and validation.

---

## 📘 Purpose
The purpose of this repository is to provide a **structured and consistent environment** for ontology engineering.  
It ensures that all essential components are stored, versioned, and accessible in one place, while maintaining flexibility for different naming conventions across projects.

---

## 📂 Repository Structure

The repository should contain (at least) the following folders:

| Folder | Description |
|--------|--------------|
| **requirements/** | Contains all requirement documents used to define the ontology’s scope, competency questions, and use cases. |
| **conceptualization/** | Stores diagrams and other resources representing the conceptual model of the ontology (e.g., class hierarchies, relationships). |
| **implementation/** | Contains the actual ontology implementation files in formats such as `.owl`, `.rdf`, `.ttl`, or `.jsonld`. |
| **shapes/** | Contains the SHACL shapes used to define and validate ontology constraints. |
| **examples/** | Includes examples that demonstrate how to instantiate or apply the ontology in real data scenarios. |
| **tests/** | Stores tests (e.g., Themis, SPARQL, or automated scripts) to verify that the ontology fulfills its requirements. |

> ⚠️ **Note:**  
> The exact folder names may vary between repositories. For this reason, a configuration file (`.config`) must be included to specify the **relative paths** to each folder.

---

## ⚙️ Configuration File (`.config`)

A `.config` file is required at the root of the repository.  
This file defines the **relative paths** to each key folder, ensuring that tools, scripts, and automated workflows can locate them regardless of custom naming conventions.

Example `.config` structure:
```ini
[paths]
requirements = ./requirements
conceptualization = ./diagrams
implementation = ./ontology
shapes = ./shacl-shapes
examples = ./rdf-examples
tests = ./tests
```
## 🧩 Ontology Conceptualization Image
Every ontology development repository should include, in this root README, a visual representation of the ontology conceptualization.
This image helps users and contributors quickly understand the ontology’s structure, key concepts, and relationships.
- The image should be located in the conceptualization folder.
- Accepted formats: .svg, .png, or .drawio.
- It should be referenced in this README using Markdown syntax, for example:

![Ontology Conceptualization Diagram](diagrams/diagram.png)

## 🗂️ Notes
- Keep the repository well-documented and modular.
- Each subfolder should contain its own README.md explaining its contents and purpose.
- Use version control and branching strategies to manage ontology evolution.
- Ensure the conceptualization image is updated whenever the ontology structure changes.

## Funding

This work has received funding from the PIONERA project (Enhancing interoperability in data spaces through artificial intelligence), a project funded in the context of the call for Technological Products and Services for Data Spaces of the Ministry for Digital Transformation and Public Administration within the framework of the PRTR funded by the European Union (NextGenerationEU)

<div align="center">
  <img src="funding_label.png" alt="Logos financiación" width="900" />
</div>

