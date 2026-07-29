# ARK Ontologies

This repository contains the ontologies and SKOS terminologies developed for the Access Risk Knowledge (ARK) platform, documented with [WIDOCO](https://github.com/dgarijo/Widoco) and published via [GitHub Pages](https://adapt-ark.github.io/ark-ontology/).

## Ontologies & Terminologies

| Name | Description | Docs | OWL | TTL | JSON-LD | N-Triples |
|---|---|---|---|---|---|---|
| ARK Cube | Concepts and relationships used in the CUBE analysis tool | [Docs](ARKCube/index-en.html) | [owl](ARKCube/ontology.owl) | [ttl](ARKCube/ontology.ttl) | [jsonld](ARKCube/ontology.jsonld) | [nt](ARKCube/ontology.nt) |
| ARK Platform | Concepts and relationships used to model users, data classifications & access controls on the ARK Platform | [Docs](ARKPlatform/index.html) | [owl](ARKPlatform/ontology.owl) | [ttl](ARKPlatform/ontology.ttl) | [jsonld](ARKPlatform/ontology.jsonld) | [nt](ARKPlatform/ontology.nt) |
| ARK Amarach Report Ontology | Concepts and relationships used in the Amarach report | [Docs](ARKAmarach/index-en.html) | – | [ttl](ARKAmarach/ontology.ttl) | – | [nt](ARKAmarach/ontology.nt) |
| ARK Risk Terminology | Risk terms used on the ARK Platform and in the socio-technical risk management domain | [Docs](ARKRiskTerminology/index.html) | – | [ttl](ARKRiskTerminology/terms.ttl) | – | – |
| ARK Health Terminology | Health terminologies, taken from the HSE Integrated Risk Management Policy, used in the ARK system | [Docs](ARKHealthTerminology/index.html) | – | [ttl](ARKHealthTerminology/healthTerms.ttl) | – | – |
| ARK Platform Terminology | Terms used on the ARK Platform | [Docs](ARKPlatformTerminology/index.html) | – | [ttl](ARKPlatformTerminology/ARKPlatformTerms.ttl) | – | – |
| ARK Controls Ontology | Control OWL classes, extracted from various standard documents, used in ARK | [Docs](ARKControlsOntology/index.html) | [owl](ARKControlsOntology/ontology.owl) | [ttl](ARKControlsOntology/ontology.ttl) | [jsonld](ARKControlsOntology/ontology.jsonld) | [nt](ARKControlsOntology/ontology.nt) |
| ARK Control Terminology | Control terminology used on the ARK Platform | [Docs](ARKControlTerminology/index.html) | [owl](ARKControlTerminology/ontology.owl) | [ttl](ARKControlTerminology/ontology.ttl) | [jsonld](ARKControlTerminology/ontology.jsonld) | [nt](ARKControlTerminology/ontology.nt) |
| ARK Cybersecurity Terminology | Cybersecurity terms extracted from standard sources and expressed in SKOS | [Docs](CybersecurityTerminology/index.html) | [owl](CybersecurityTerminology/ontology.owl) | [ttl](CybersecurityTerminology/ontology.ttl) | [jsonld](CybersecurityTerminology/ontology.jsonld) | [nt](CybersecurityTerminology/ontology.nt) |
| ARK Logging Ontology | Ontology used to generate and manage network/audit logs | [Docs](ARKLoggingOntology/index.html) | [owl](ARKLoggingOntology/ontology.owl) | [ttl](ARKLoggingOntology/ontology.ttl) | [jsonld](ARKLoggingOntology/ontology.jsonld) | [nt](ARKLoggingOntology/ontology.nt) |
| Hospital Adverse Incidents Categories & Subcategories | Categories and subcategories of clinical adverse incidents, defined by our partner hospital in Ireland | [Docs](HAdvIncCats/index.html) | – | [ttl](HAdvIncCats/AIRCatSubcatTerms.ttl) | – | – |
| HSE ERM Control Ontology | OWL classes used to instantiate Controls, based on the HSE Enterprise Risk Management framework | [Docs](HSE-ERM-ControlOntology/index.html) | [owl](HSE-ERM-ControlOntology/ontology.owl) | [ttl](HSE-ERM-ControlOntology/ontology.ttl) | [jsonld](HSE-ERM-ControlOntology/ontology.jsonld) | [nt](HSE-ERM-ControlOntology/ontology.nt) |
| NIOSH Control Ontology | OWL classes used to instantiate Controls, based on the NIOSH framework | [Docs](NIOSH-ControlOntology/index.html) | [owl](NIOSH-ControlOntology/ontology.owl) | [ttl](NIOSH-ControlOntology/ontology.ttl) | [jsonld](NIOSH-ControlOntology/ontology.jsonld) | [nt](NIOSH-ControlOntology/ontology.nt) |

## Updating an ontology

1. Clone the repository to your local machine.
1. Update the ontology (owl/ttl source files).
1. Regenerate the documentation into its folder using [WIDOCO](https://github.com/dgarijo/Widoco) (jar available in the repository).
1. Commit and push to `main` — GitHub Pages redeploys automatically.
