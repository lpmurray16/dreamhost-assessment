# DreamHost Assessment - Logan Murray

## My thought process:

Because this is just a static page I thought it appropriate to use a SSG like Astro as a tool to help me organize my layout into components. Looking at the layout itself it was clear that there were 3 sections/components. So that is exactly what I did. I created three components and incorporated them into the index file (Astro is a great templating language tool check it out at astro.build). I then thought it would be a good idea to create some variables with the given breakpoints and the given colors from the PDf mockup that was provided. I leveraged Sass to also create the same variables just for the sake of consistency, in fact I used Sass to write all of my CSS because I was trying my best to incorporate the BEM style of writing class names and using Sass makes it easier to nest.

## What I would do differently next time:

#### 1. I would create more utility classes in my CSS that can be reused (or incorporate Tailwind or Bulma or Semantic UI) instead of trying to use specific classes for each element.

#### 2. I would refactor my code so that I didn't have to rely on 2 headers based on 2 breakpoints to show and hide due to their locations. In this instance I might be able to leverage the grid system along with media queries.

#### 3. If this were a serious production level project I would have to consider SEO best practices within the markup and accessibility.
