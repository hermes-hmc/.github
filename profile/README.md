HERMES is a language-independent set of tools and practices to help you implement "continuous software publishing", creating publications from your software automatically.


## Why this is great

A software publication is about creating a publication about the entity the software represents. The software becomes a citable entity, referable in yours and others publications. Furthermore, Software publications promotes

- **sustainability** (what again?)
- **reproducibility** (I used release/commit xyz for process abc)
- **academic credit** (especially if your software is not primary subject of publications, created using it)
- **fair for research software** (FAIR4RS) principles

## How HERMES improves Software Publishing

State of the art of SP works by bridging GitHub with Zenodo and providing several meatadata you wll be able to automatically create a publcation on Zenodo.
This "pull based workflow" is limited by certain factors: code must be accessible, less control over extracted metadata, dependent on single service (Zenodo).

HERMES turns this process upside-down by integrating software publication into your CI/CD pipelines where you define the events, the targets and the scope for your
software publication.

## How it works

![https://docs.software-metadata.pub/en/latest/](https://docs.software-metadata.pub/en/latest/_images/workflow-overview.svg)

The workflow is described in detail in the [hermes-hmc/workflow](https://github.com/hermes-hmc/workflow) repository.

## Is there an example?

An example configuration can be viewed in the [hermes-hmc/showcase](https://github.com/hermes-hmc/showcase) repository.
