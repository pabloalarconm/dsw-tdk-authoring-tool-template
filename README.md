# FAIR Assessment Authoring Tool
---

**Jinja2-based template** for authoring and registering FAIR Assessment Components:

* FAIR Benchmark
* FAIR Metric
* FAIR Test
* FAIR Benchmark Algorithm
  
## Templating options

- **RDF templating**: following the [FTR](https://github.com/OSTrails/FAIR_testing_resource_vocabulary) semantic model.
- **JSON templating**: following the [FAIRsharing](https://fairsharing.org/API_doc) API specification for registry creation.


## Contributors
* Pablo Alarcón-Moreno 
  - ORCID: 0000-0001-5974-589X
  - GitHub: @pabloalarconm
  - Email: pablo.alarcon@upm.es 

## Changelog

### 1.4.1

- RDF syntax bug from `1.4.0` fixed.

### 1.4.0

- Lack of organisation and metric ID uses FAIRshairng ID.

### 1.3.0

- Minor error with FAIR Principles in Turtle serialization.

### 1.2.0

- Landing page URL as dcterms:identifier in Turtle

### 1.1.0

- Metrics include Benchmark URL at Turtle
- non-DOI Metric/FAIR Principles URLs added at Turtle

### 1.0.1

- Github URL changed to Github Pages
- DCAT types included for FDP submission

### 1.0.0

- Template for Github and FAIRsharing submision.
- Compliance with FTR 1.2.0

## License

This template is released under CC0. Read the LICENSE file for details.