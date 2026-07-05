---
title: Celsius Living - Piarra Waters Website
slug: celsius-living-piarra-waters-website
client: Celsius Property Group
studio_agency: Simtail Solutions
url: https://piarawaters.celsiusliving.com.au/
year: 2023
role:
  - Developer
---
Piarra Waters was a residential land estate website for Celsius Living. It was a polished marketing site with a fair bit of complexity behind it, especially around the interactive property map and the layered visual treatment used throughout the design.

This was a fun project to work on because it had a strong visual direction, but still left me with a lot of tricky implementation problems to solve. The design was vibrant, colourful, and visually detailed, so the site needed to feel lively and polished while still making the estate information, lot details, documents, and enquiry pathways easy to navigate.
## The brief
The site needed to present the Piarra Waters estate clearly for prospective buyers. With several housing developments competing for attention in the surrounding area, the site needed to help the estate feel distinct. That meant showing the lifestyle and location benefits of the development, while also giving users a practical way to explore available lots and access supporting documents.

A key part of the brief was the interactive lot map. Users needed to be able to browse lots, filter them, view individual property details, and access the relevant blueprint or enquiry link without being pushed through a traditional page-by-page structure. The client also needed the ability to release lots in stages, so the site had to support ongoing updates as new properties became available.
## The challenge
The hardest part of this project was making the design behave responsively. A lot of the page layouts relied on transparent SVG overlays, layered imagery, and carefully positioned visual elements. Some graphic elements had to be expanded, and in a few cases new ones had to be created, so the design could handle different screen sizes and layout edge cases without feeling patched together.

It looked simple once it worked, but it took a lot of tuning to stop things from drifting, overlapping, or falling apart across different screen sizes.

One unexpected part of the process was how often the design had to be tested at very large screen sizes. Some stakeholder feedback came from reviewing the site on conference room projectors and 4K monitors, which exposed layout issues that would not have been obvious at standard desktop widths.

## The build
The main technical feature was the interactive property map. Each clickable section of the map represented an individual property lot, and each one was connected to a WordPress custom post type with custom fields for details such as area, frontage, address, and supporting documents. The individual lot URLs were hidden, because these records were not meant to behave like normal public pages. They existed to power the map and browsing experience.

From the map, users could click on a lot tile to open a modal showing the relevant details. That modal included the lot information, a link to the lot plan, and a pathway to enquire. Filtering options were also included so users could narrow the available lots more easily.
## The outcome
For me, Piarra Waters stands out as a project where the visual design and technical structure had to support each other closely. The site needed to feel vibrant and polished, but it also needed to work as a practical tool for browsing lots, viewing documents, and making enquiries.

The finished site gave Celsius Living a strong presentation tool for the estate, while giving prospective buyers a clearer way to explore available properties. It also gave the client a structure that could support staged lot releases, rather than locking everything into a static brochure-style website.

It is also the kind of project I enjoy: taking a visually detailed design, working through the awkward implementation details, and turning it into something that feels straightforward for the person using it.
## Key contributions
- Developed the interactive property map used to browse individual estate lots.
- Connected each clickable map section to structured property data using WordPress custom post types and custom fields.
- Added property details including area, frontage, address, supporting documents, and enquiry pathways.
- Built modal-based lot details so users could explore properties without leaving the map experience.
- Added filtering options to help users narrow the available lots.
- Supported staged lot releases by structuring the site around editable property records.
- Implemented responsive layouts using layered SVG overlays and supporting graphic elements.
- Integrated mixed content types including video, YouTube embeds, infographic images, and PDF document repositories.