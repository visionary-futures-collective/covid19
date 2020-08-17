# VFC COVID-19 response

Website for Visionary Futures Collective COVID-19 response project.

Visit our website!: https://visionary-futures-collective.github.io/covid19/

## Adding new pages to the site

Make a new .md in the base of the repository with some basic metadata. For example, resources.md:

```
---
layout: default
title: Resources
permalink: /resources
---
This is some text for the resources page.
```
Note that these pages aren't really public yet, as there isn't a nav bar yet. 
Also important to note is that, after modifying the page, the landing page is now in index.html rather than \_includes/about.html. To add the new page to the nav bar, you'll need to add it to \_includes/navbar.html using the template there.
