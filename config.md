<!--
Add here global page variables to use throughout your website.
-->

+++
author = "Cameron Pfiffer"
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]

# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website

# prepath = "yourproject"

# Add here files or directories that should be ignored by Franklin, otherwise

# these files might be copied and, if markdown, processed by Franklin which

# you might not want. Indicate directories by ending the name with a `/`.

# Base files such as LICENSE.md and README.md are ignored by default.

ignore = ["node_modules/"]

# RSS (the website\_{title, descr, url} must be defined to get RSS)

generate_rss = true
website_title = "JuliaGenAI"
website_descr = "Generative AI in Julia"
website_url = "https://juliagenai.org"
+++

<!--
Add here global latex commands to use throughout your pages.
-->

\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
