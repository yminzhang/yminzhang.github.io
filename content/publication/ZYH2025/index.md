---
title: 'Federated Heavy Hitter Analytics with Local Differential Privacy'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Qingqing Ye
  - Haibo Hu 

# Author notes (optional)

# date: '2025-02-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2025 ACM Conference on Management of Data (SIGMOD)*
publication_short: In *SIGMOD 2025*

# abstract: Federated heavy hitter analytics enables service providers to better understand the preferences of cross-party users by analyzing the most frequent items. As with federated learning, it faces challenges of privacy concerns, statistical heterogeneity, and expensive communication. Local differential privacy (LDP), as the de facto standard for privacy-preserving data collection, solves the privacy challenge by letting each user perturb her data locally and report the sanitized version. However, in federated settings, applying LDP complicates the other two challenges, due to the deteriorated utility by the injected LDP noise or increasing communication/computation costs by perturbation mechanism. To tackle these problems, we propose a novel target-aligning prefix tree mechanism satisfying ϵ-LDP, for federated heavy hitter analytics. In particular, we propose an adaptive extension strategy to address the inconsistencies between covering necessary prefixes and estimating heavy hitters within a party to enhance the utility. We also present a consensus-based pruning strategy that utilizes noisy prior knowledge from other parties to further align the inconsistency between finding heavy hitters in each party and providing reasonable frequency information to identify the global ones. To the best of our knowledge, our study is the first solution to the federated heavy hitter analytics in a cross-party setting while satisfying the stringent ϵ-LDP. Comprehensive experiments on both real-world and synthetic datasets confirm the effectiveness of our proposed mechanism.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Data Privacy

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

# slides: example


---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
