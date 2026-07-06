---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 3
cv_pdf: UmaRMohanCV.pdf # you can also use external links here
toc:
  sidebar: left
---

<p>Curriculum Vitae <a href="{{ page.cv_pdf | prepend: '/assets/pdf/' | relative_url }}" target="_blank">[PDF]</a></p>

<div class="post">
  <object
    data="{{ page.cv_pdf | prepend: '/assets/pdf/' | relative_url }}#pagemode=none"
    width="100%"
    height="1000"
    type="application/pdf"
  >
    <p>Your browser can't display embedded PDFs.
       <a href="{{ page.cv_pdf | prepend: '/assets/pdf/' | relative_url }}">Download the PDF</a> instead.</p>
  </object>
</div>
