This project uses Astro web framework throughout. Be sure to use the Astro framework format for importing components, for example: 'import BaseLayout from "../layouts/BaseLayout.astro";'. 

Layout files are stored in the 'src/layouts' directory. Layout files are used to define the structure of a page, and can be used to wrap other components. Layout files can be used to display frontmatter data, such as the title and description of a page. Frontmatter data is written in YAML format and is placed at the top of a Markdown file between sets of three dashes.

Inline Javascript, including arrow functions, can be used in Astro files without a '<script>' tag as long as it's wrapped in curly braces. For example: '{skills.map((skill) => <li class="skill">{skill}</li>)}'.

import.meta.glob() will return an array of objects, one for each blog post.