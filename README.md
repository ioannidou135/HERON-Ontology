# HERON Ontology

**HERON (HEalthcare RObotics oNto logy)** is an upper ontology designed for communication, collaboration, and safety in healthcare robotics environments.

It supports real-time reasoning, policy enforcement, and semantically driven behavior for autonomous robotic agents in healthcare institutions.

This repository provides the complete HERON package, including:
- The OWL ontology in Turtle format
- Sample SPARQL queries
- SHACL validation shapes
- Example code for Python (RDFlib + pySHACL)
- Example code for Java (OWL API)
- Mapping files to HL7 and SUMO concepts

---

## 📦 Contents

| File | Description |
|------|-------------|
| `heron.ttl` | The main HERON ontology in Turtle format |
| `heron_query.rq` | Example SPARQL query on robotic roles and permissions |
| `heron_shapes.ttl` | SHACL constraints for safety and task validation |
| `heron_python_example.py` | Python script for reasoning and SHACL validation |
| `heron_java_example.java` | Java example using OWL API |
| `heron_mapping_HL7.ttl` | Mapping between HERON and HL7 RIM concepts |
| `heron_mapping_SUMO.ttl` | Mapping between HERON and SUMO upper ontology |

---

## 🧠 Reasoning & Validation

- OWL Reasoners: **HermiT**, **Pellet**
- SHACL Engine: Validates compliance with safety and institutional constraints
- Compatible with: **Protégé**, **Apache Jena**, **RDFlib**, **TopBraid**, **OWL API**

---

## 🔗 Citation & License

This ontology was developed in the context of the EU Horizon 2020 ENDORSE project and is published under the **Creative Commons Attribution 4.0 (CC-BY)** license.

**Zenodo link:** [https://doi.org/10.5281/zenodo.14675207](https://doi.org/10.5281/zenodo.14675207)

If you use this ontology, please cite:

> Ioannidou, P. et al., "HERON: An Upper Ontology for Communication, Collaboration and Safety in Healthcare Robotics", *Healthcare Robotics and AI*, MDPI, 2025.

---

## 🛠 How to Use

You can open the `heron.ttl` in [Protégé](https://protege.stanford.edu/), query it with the provided `.rq` file using a SPARQL endpoint, or run the reasoning examples in Python or Java as shown.

---

## 👩‍💻 Contact

For questions or collaboration:
**Penelope Ioannidou** — [penelopeioannidou@gmail.com](mailto:penelopeioannidou@gmail.com)

---

