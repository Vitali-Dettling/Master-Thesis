# Master-Thesis

**Usage of a microservice oriented architecture to distribute database tables in Scale Out installations**

**Author:** Vitali Dettling (51995)  
**Institution:** Hochschule Karlsruhe – University of Applied Sciences  
**In cooperation with:** SAP SE  
**Date:** 10 March 2018  
**Reviewers:** Prof. Dr. Haneke, Prof. Dr. Waldhorst  
**Supervisor:** Dr. Hoffmann

## Abstract

The distribution of tables in a HANA scale-out landscape depends on many factors such as table size, table usage in joins, frequency of joins and transferred volumes during joins, number of partitions, etc. Constraints must be considered so as not to disturb query runtimes. The algorithms to find the optimal distribution have to consider many variants and handle high volumes of tables.

SAP’s Data Distribution Optimizer (DDO), delivered with SAP HANA Data Warehousing Foundation, was originally based on SAP HANA extended services classic (XS Classic). With the introduction of SAP HANA extended services advanced (XS Advanced), new architectural concepts became possible. This thesis formulates a concept for a microservice-oriented architecture for DDO and validates it with a prototype implemented in Node.js.

## Repository Contents

- `docs/` — Thesis PDF and DOCX
- `images/` — Cover, university logo, and key diagrams (Monolith vs Microservices, etc.)

## Keywords

SAP HANA, scale-out, Data Distribution Optimizer (DDO), microservices, XS Advanced, Node.js, database table distribution, hierarchical clustering
