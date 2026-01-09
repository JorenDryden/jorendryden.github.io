---
layout: page
title: Portfolio
permalink: /portfolio/
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

{% include project-card.html
  title="TurtleShell"
  role="Project Lead"
  image="/turtleshell_main.png"
  alt="TurtleShell main interface"
  description="
  <p>TurtleShell is a locally hosted encryption manager for documents, passwords, and other sensitive data.</p>
  <p>Built primarily in Java using Java cryptography libraries and JavaFX, with an emphasis on secure-by-default behavior and a clean UI.</p>
  "
  links='
    <a href="/turtleshell/">Case study</a>
  '
%}

{% include project-card.html
  title="Another Project"
  role="Developer"
  image="/images/another.png"
  description="
  <p>One paragraph description.</p>
  <p>Second paragraph with key tech.</p>
  "
%}
