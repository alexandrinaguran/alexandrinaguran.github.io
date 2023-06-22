---
title: "Publications"
permalink: "/publications/"
layout: page
---

# Publications 

 - **Guran, C. N. A.**, Sladky, R., Karl, S., Boch, M., Laistler, E., Windischberger, C., Huber, L., & Lamm, C. (2022). Validation of a new coil array tailored for dog functional magnetic resonance imaging (fMRI) studies. bioRxiv, 2022-06.
 - **Guran, C. N. A.**, Deuker, L., Göttlich, M., Axmacher, N., & Bunzeck, N. (2022). Benefit from retrieval practice is linked to temporal and frontal activity in healthy young and older humans. Cerebral Cortex Communications, 3(1), tgac009.
 - **Guran, C. N. A.**, Lehmann-Grube, J., & Bunzeck, N. (2020). Retrieval practice improves recollection-based memory over a seven-day period in younger and older adults. Frontiers in Psychology, 10, 2997.
 - **Guran, C. N. A.**, Herweg, N. A., & Bunzeck, N. (2019). Age-related decreases in the retrieval practice effect directly relate to changes in alpha-beta oscillations. Journal of Neuroscience, 39(22), 4344-4352.
 - Babayan, A., Erbey, M., Kumral, D., Reinelt, J. D., Reiter, A. M., Röbbig, J., ... **Guran, C. N. A.**, ... & Villringer, A. (2019). A mind-brain-body dataset of MRI, EEG, cognition, emotion, and peripheral physiology in young and old adults. Scientific data, 6(1), 1-21.

# Preprints

- Gold, C., Groessing, A., Ruiz, M., **Guran, A.**, Koçan, A., Kouwer, K., ... & Specht, K. (2023). [Design and implementation of a replication study: The Music for Autism (M4A) binational assessor-blinded randomised crossover trial.](https://www.researchsquare.com/article/rs-2478719/v1)
- **Guran, C. N. A.**, Lonardo, L., Tünte, M. R., Arzberger, K., Völter, C., Hoehl, S., ... & Lamm, C. (2022). [False belief understanding in children and dogs in a nonverbal ambiguous displacement and communication setting.](https://psyarxiv.com/s5ygj/download/?format=pdf) PsyRXiv. 
- Alberghina, D., Bray, E., Buchsbaum, D., Byosiere, S. E., Espinosa, J., Gnanadesikan, G., **Guran, C.N.A.**, ... & Stevens, J. R. (2022). [ManyDogs Project: A Big Team Science Approach to Investigating Canine Behavior and Cognition](https://psyarxiv.com/j82uc/download?format=pdf). PsyRXiv. 


## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
