
# Batch Connect - OOD Geneious

[![GitHub License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

An interactive app designed for OSC OnDemand that launches Geneious within an Owens batch job.

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job before
  launching the container.
- [XFCE] is used to provide the window manager and terminal access if desired

[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod
[Geneious]: https://geneious.com
[ISU-HPC/ood-geneious]: https://github.com/ISU-HPC/ood-geneious
[XFCE]: https://www.xfce.org/

Use feature branches for each cluster.

