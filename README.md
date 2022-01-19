# atlas-singularity
<p align="justify">

**Introduction:**
    This is the singularity image of the metagenome atlas (v2.8.1). For further information about the pipeline https://metagenome-atlas.readthedocs.io/en/latest/

**To make image file from def file using singularity**

`sudo singularity build atlas-2.8.1.sif atlas-2.8.1.def`

**Run singularity image**

`singularity exec atlas-2.8.1.sif atlas --help`

Usage: atlas [OPTIONS] COMMAND [ARGS]...

  ATLAS - workflows for assembly, annotation, and genomic binning of
  metagenomic and metatranscriptomic data.

  For updates and reporting issues, see: https://github.com/metagenome-atlas/atlas

Options:
  --version   Show the version and exit.
  -h, --help  Show this message and exit.

Commands:
  download  download reference files (need ~50GB)
  init      prepare configuration file and sample table for atlas run
  run       run atlas main workflow

**For citation**
ATLAS: a Snakemake workflow for assembly, annotation, and genomic binning of metagenome sequence data. Kieser, S., Brown, J., Zdobnov, E. M., Trajkovski, M. & McCue, L. A. BMC Bioinformatics 21, 257 (2020). doi: 10.1186/s12859-020-03585-4
