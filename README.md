# Nextflow pipelines

This repository contains a list of Nextflow pipelines.

# Pipelines

| Name    | Repository                 | Description      |
|---------|----------------------------|------------------|
| IRIDA Next Integration Pipeline | <https://github.com/phac-nml/iridanext-example-nf> | A pipeline to help integrate Nextflow with IRIDA Next. |
| Mikrokondo | <https://github.com/phac-nml/mikrokondo> | A simple pipeline for bacterial assembly and quality control. |
| SNVPhyl | <https://github.com/phac-nml/snvphylnfc> | A pipeline for whole-genome phylogenetic analysis |
| fetchdatairidanext | <https://github.com/phac-nml/fetchdatairidanext> | A pipeline for downloading reads from NCBI. |
| speciesabundance | <https://github.com/phac-nml/speciesabundance> | Estimate the relative abundance of sequence reads originating from different species in a sample. |
| gasclustering | <https://github.com/phac-nml/gasclustering> | Clusters provided MLST profiles for samples (in JSON format) and provides cluster addresses and a visualization of the dendrogram + metadata. |
| gasnomenclature | <https://github.com/phac-nml/gasnomenclature> | Assigns new MLST-derived cluster addresses to samples within the context of previously defined cluster addresses. |
| clustersplitter (in-development) | <https://github.com/phac-nml/clustersplitter/tree/dev> | Groups samples by provided metadata values and provides summary statistics of allelic distances and metadata values. |
| staramrnf (in-development) | <https://github.com/phac-nml/staramrnf/tree/dev> | Identifies AMR from passed assembled genomes using the StarAMR software. |

# Development

To develop a new pipeline, please refer to the [Pipeline standards][pipeline-standards] guide.

# License

Text in this repository is licensed under the **Creative Commons Attribution 4.0 International** <https://creativecommons.org/licenses/by/4.0/> license. Licenses for each pipeline are specific to the respective repositories.

[pipeline-standards]: https://github.com/phac-nml/pipeline-standards
