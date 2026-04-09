# Fabric Dummy Data Generator — Documentation

Welcome to the documentation for the **Fabric Dummy Data Generator (FDDG)**.

## Overview

FDDG is an open-source project that generates realistic fake data for Microsoft Fabric demos and training. It models a fictional company — **Rockline Supplies** — a construction materials wholesaler operating across multiple physical locations.

The generated data includes:

- **Master data**: products, customers, suppliers, locations, employees
- **Transactional data**: sales orders, purchase orders, inventory movements

## Getting Started

- [Setup Guide](setup.md) — prerequisites and initial configuration
- [Data Model](data-model.md) — schema reference for all generated entities
- [Notebooks](notebooks.md) — how to run the seeding and incremental load notebooks

## Project Structure

```
fabric-dummy-data-generator/
├── docs/               # Project documentation
├── .github/            # Contributing guidelines and repo instructions
├── notebooks/          # Microsoft Fabric Python notebooks
└── README.md
```

## Key Concepts

### Initial Load

The initial load seeds the Lakehouse with a full set of master data and a historical backfill of transactions.

### Incremental Load

Incremental loads simulate ongoing business activity, appending new transactions so your demo data stays fresh over time.

## Further Reading

Refer to the individual sections in the sidebar for deeper dives into each area of the project.
