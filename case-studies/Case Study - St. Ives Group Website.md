---
title: St. Ives Group Website
slug: st-ives-group-website
client: St. Ives Group
studio_agency: Workhouse Advertising
url: https://stivesgroup.com.au
year: 2024
role:
  - Developer
---
St. Ives Group is a retirement lifestyle provider with locations across metro Perth and Albany. 

Their website needed to present the benefits of their communities, showcase available properties, and support a large amount of lifestyle, village, event, and informational content.
## The Brief
Following a recent brand refresh for St. Ives Group, Workhouse was tasked with updating the website to better align with the new direction. The existing site, however, had been built on an outdated page builder setup that was not well suited to the new design requirements, so what may have started as a visual update quickly became a much larger rebuild.

The new website used a responsive design created in-house by the Workhouse team, but this was far more than a reskin. The brand refresh changed the way the site needed to present information, which meant existing content had to be reorganised, page structures had to be reconsidered, and the new layouts needed a stronger technical foundation behind them.

The rebuilt site needed to support a wide range of content types, including properties, villages, events, testimonials, FAQs, and a long-running blog archive. Each of these content types needed its own structure, templates, fields, and frontend treatment, which made the project closer to building a content system than simply rebuilding a set of pages.
## My Approach
Given the size of the site, I pushed for a custom WordPress build using the Block Editor rather than relying heavily on a page builder and a stack of theme/plugin dependencies.

The intention was to keep the site lighter, more flexible, and less dependent on bulky third-party tooling. In hindsight, that decision made parts of the build more complicated than expected, but the motivation behind it was sound: this was a large website with a lot of structured content, and I wanted the foundation to be something we could control.
## The Build
The theme was built around WordPress, the Block Editor, custom post types, custom fields, and Tailwind CSS, which was already familiar to the development team at Workhouse. 

WordPress does not play with Tailwind quite as nicely out of the box, so I built a small set of scripts to compile the theme CSS as part of the build workflow. The aim was to make the project fit better with the way the team already worked, rather than treating the WordPress build as a completely separate beast. 

A large part of the work involved translating the in-house design into a responsive WordPress theme and building out the various content structures needed across the site.

The website made heavy use of custom post types and custom data, including:
- events, with dates, times, and supporting details
- testimonials, some with YouTube embeds and related village links
- FAQs using a question-and-answer structure
- properties with detailed custom fields
- villages, used both as a property taxonomy and as rich content pages
- blog posts going back many years

The property section was one of the more involved parts of the project. Properties had a large number of custom fields, external 4K imagery that needed to be loaded and cached, and frontend filtering by bedrooms, bathrooms, price, and village. The filtering was designed to work dynamically and responsively rather than relying on a basic form submission and page refresh.

The village pages also required their own approach. Each village had a large amount of information, and each included points of interest that needed to appear on a custom Google Map implementation. This meant the site needed to combine structured WordPress content with interactive frontend behaviour.
## The Challenge
The main challenge was the scale of the project.

The website was made up of many different content types, each with its own layout, behaviour, and design treatment. Almost every section of the site had been designed with care, which looked great, but also meant there were very few places where a generic template would be enough.

The content migration and reorganisation added another layer of complexity. The new design changed how content was grouped and presented, so development often involved working out how the old content should map into the new structure before the actual build work could happen. In some cases, the content also contained remnants of older page builder tags and formatting that had accumulated over time, which further complicated the migration process.

There were also multiple stakeholders involved, with feedback arriving in smaller batches over time. That meant balancing new development work with ongoing revisions, content changes, and design adjustments as the project progressed.
## The Result
The finished site is a custom WordPress rebuild for a large retirement lifestyle provider, with structured content, responsive layouts, property filtering, village pages, events, testimonials, FAQs, blog content, and interactive map functionality.

It was a substantial build and one of the largest WordPress projects I have worked on. It required a mix of theme development, content modelling, frontend implementation, responsive layout work, custom post type management, and a fair bit of problem-solving around how the site’s content should actually be managed.

It also pushed me deeper into the realities of building large WordPress sites with the Block Editor. The project gave me a much clearer understanding of where the Block Editor works well, where it needs stronger boundaries, and how to approach content-heavy WordPress builds at scale.
## Key Contributions
- Developed a custom responsive WordPress theme for the rebuilt website.
- Helped move the site away from an older page builder structure.
- Implemented the build using the Block Editor and Tailwind CSS.
- Built and managed multiple custom post types, taxonomies, and content structures.
- Developed property listing functionality with custom fields and dynamic filtering.
- Worked with externally hosted property imagery and caching requirements.
- Built village content templates with custom Google Map points of interest.
- Supported a large content reorganisation across the site.