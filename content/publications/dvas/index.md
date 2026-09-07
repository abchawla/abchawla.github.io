---
title: 'DVAS: Dynamic Vulnerability-Aware Scheduling for HPC Clusters using Splunk-Driven Access Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- me
- Indrakshi Ray

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-07-08T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 31st ACM Symposium on Access Control Models and Technologies"
publication_short: "SACMAT 26"

abstract: High Performance Computing (HPC) environments are increasingly being considered as high-value target for attackers. Vulnerabilities identified in such environments cannot be immediately patched because of the need for high system availability and long-running workflows. If jobs execute on vulnerable nodes, the value of the output produced are suspect. Moreover, if vulnerable nodes are completely excluded from job allocation, the throughput of the system is affected. Towards this end, we propose DVAS, a dynamic vulnerability-aware scheduling mechanism that aims to maximize throughput taking into account the risk caused by vulnerabilities. DVAS correlates real-time vulnerability telemetry with user behavioral profiling to calculate a probabilistic risk score which is used as a dynamic attribute for controlling access to compute nodes in an HPC cluster. DVAS is implemented using our proposed Secure Job Admission (SJA) algorithm that uses Splunk analytics. We use an asynchronous architecture that decouples the Policy Decision Point (PDP) from the Policy Enforcement Point (PEP), achieving a mean enforcement latency of 0.88ms. Our evaluation on a 25-node cluster shows that DVAS reduces risk exposure by 98% while maintaining 91.8% utilization, significantly outperforming traditional ''drain-and-patch'' strategies. We also propose a measure called Security-Weighted Throughput (SWT) of a cluster that maps security into an operational cost and determines the throughput taking into account the untrustworthiness of results produced by execution on a node containing exploitable vulnerabilities.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Intermittent Runtime
  - Intermittent Computing
  - Runtime Monitoring


# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3750555.3811898

# Custom links
links:
  - type: pdf
    url: "https://doi.org/10.1145/3750555.3811898"
  #- type: code
  #  url: "hhttps://github.com/tinysystems/ARTEMIS"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
