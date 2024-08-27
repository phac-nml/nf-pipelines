# Nextflow pipelines

This repository contains a list of Nextflow pipelines.

# Pipelines

| Name    | Repository                 | Description      | Run in Nextflow with provided test data |
|---------|----------------------------|------------------|---|
| iridanextexample | <https://github.com/phac-nml/iridanextexample> | A pipeline to help integrate Nextflow with IRIDA Next. | `nextflow run phac-nml/iridanextexample -profile test,docker --outdir results` |
| Mikrokondo | <https://github.com/phac-nml/mikrokondo> | A simple pipeline for bacterial assembly and quality control. | `nextflow run phac-nml/mikrokondo -profile test,docker --outdir results` |
| SNVPhyl | <https://github.com/phac-nml/snvphylnfc> | A pipeline for whole-genome phylogenetic analysis | `nextflow run phac-nml/snvphylnfc -profile test,docker --outdir results` |
| fetchdatairidanext | <https://github.com/phac-nml/fetchdatairidanext> | A pipeline for downloading reads from NCBI. | `nextflow run phac-nml/fetchdatairidanext -profile test,docker --outdir results` |
| speciesabundance | <https://github.com/phac-nml/speciesabundance> | Estimate the relative abundance of sequence reads originating from different species in a sample. | `nextflow run phac-nml/speciesabundance -profile test,docker --outdir results` |
| gasclustering | <https://github.com/phac-nml/gasclustering> | Clusters provided wg/cgMLST profiles for samples (in JSON format) and provides cluster addresses and a visualization of the dendrogram + metadata. | `nextflow run phac-nml/gasclustering -profile test,docker --outdir results` |
| gasnomenclature | <https://github.com/phac-nml/gasnomenclature> | Assigns new wg/cgMLST-derived cluster addresses to samples within the context of previously defined cluster addresses. | `nextflow run phac-nml/gasnomenclature -profile test,docker --outdir results` |
| staramrnf | <https://github.com/phac-nml/staramrnf> | Identifies AMR from passed assembled genomes using the StarAMR software. | `nextflow run phac-nml/staramrnf -profile test,docker --outdir results` |
| arboratornf | <https://github.com/phac-nml/arboratornf> | Groups samples by provided metadata values and provides summary statistics of wg/cgMLST allelic distances and metadata values. | `nextflow run phac-nml/arboratornf -profile test,docker --outdir results` |

# Development

To develop a new pipeline, please refer to the [Pipeline standards][pipeline-standards] guide.

# License

Text in this repository is licensed under the **Creative Commons Attribution 4.0 International** <https://creativecommons.org/licenses/by/4.0/> license. Licenses for each pipeline are specific to the respective repositories.

[pipeline-standards]: https://github.com/phac-nml/pipeline-standards
