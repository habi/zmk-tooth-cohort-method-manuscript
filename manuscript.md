---
author-meta:
- "David Haberth\xFCr"
- Ruslan Hlushchuk
- Thomas Gerhard Wolf
bibliography:
- content/manual-references.json
date-meta: '2020-09-01'
header-includes: "<!--\nManubot generated metadata rendered from header-includes-template.html.\nSuggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html\n-->\n<meta name=\"dc.format\" content=\"text/html\" />\n<meta name=\"dc.title\" content=\"Automatic workflow for the analysis of large batches of micro-tomographic scans of human teeth\" />\n<meta name=\"citation_title\" content=\"Automatic workflow for the analysis of large batches of micro-tomographic scans of human teeth\" />\n<meta property=\"og:title\" content=\"Automatic workflow for the analysis of large batches of micro-tomographic scans of human teeth\" />\n<meta property=\"twitter:title\" content=\"Automatic workflow for the analysis of large batches of micro-tomographic scans of human teeth\" />\n<meta name=\"dc.date\" content=\"2020-09-01\" />\n<meta name=\"citation_publication_date\" content=\"2020-09-01\" />\n<meta name=\"dc.language\" content=\"en-US\" />\n<meta name=\"citation_language\" content=\"en-US\" />\n<meta name=\"dc.relation.ispartof\" content=\"Manubot\" />\n<meta name=\"dc.publisher\" content=\"Manubot\" />\n<meta name=\"citation_journal_title\" content=\"Manubot\" />\n<meta name=\"citation_technical_report_institution\" content=\"Manubot\" />\n<meta name=\"citation_author\" content=\"David Haberth\xFCr\" />\n<meta name=\"citation_author_institution\" content=\"Institute of Anatomy, University of Bern, Switzerland\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0003-3388-9187\" />\n<meta name=\"twitter:creator\" content=\"@habi\" />\n<meta name=\"citation_author\" content=\"Ruslan Hlushchuk\" />\n<meta name=\"citation_author_institution\" content=\"Institute of Anatomy, University of Bern, Switzerland\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0002-6722-8996\" />\n<meta name=\"citation_author\" content=\"Thomas Gerhard Wolf\" />\n<meta name=\"citation_author_institution\" content=\"Department of Restorative, Preventive and Pediatric Dentistry, School of Dental Medicine, University of Bern, Switzerland\" />\n<meta name=\"citation_author_institution\" content=\"Department of Periodontology and Operative Dentistry, University Medical Center of the Johannes-Gutenberg-University Mainz, Mainz, Germany\" />\n<link rel=\"canonical\" href=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/\" />\n<meta property=\"og:url\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/\" />\n<meta property=\"twitter:url\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/\" />\n<meta name=\"citation_fulltext_html_url\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/\" />\n<meta name=\"citation_pdf_url\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"application/pdf\" href=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"text/html\" href=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/v/5bfee12cb093df8e818a292c39a585d8bc9e8c61/\" />\n<meta name=\"manubot_html_url_versioned\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/v/5bfee12cb093df8e818a292c39a585d8bc9e8c61/\" />\n<meta name=\"manubot_pdf_url_versioned\" content=\"https://habi.github.io/zmk-tooth-cohort-method-manuscript/v/5bfee12cb093df8e818a292c39a585d8bc9e8c61/manuscript.pdf\" />\n<meta property=\"og:type\" content=\"article\" />\n<meta property=\"twitter:card\" content=\"summary_large_image\" />\n<link rel=\"icon\" type=\"image/png\" sizes=\"192x192\" href=\"https://manubot.org/favicon-192x192.png\" />\n<link rel=\"mask-icon\" href=\"https://manubot.org/safari-pinned-tab.svg\" color=\"#ad1457\" />\n<meta name=\"theme-color\" content=\"#ad1457\" />\n<!-- end Manubot generated metadata -->"
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Automatic workflow for the analysis of large batches of micro-tomographic scans of human teeth
...






<small><em>
This manuscript
([permalink](https://habi.github.io/zmk-tooth-cohort-method-manuscript/v/5bfee12cb093df8e818a292c39a585d8bc9e8c61/))
was automatically generated
from [habi/zmk-tooth-cohort-method-manuscript@5bfee12](https://github.com/habi/zmk-tooth-cohort-method-manuscript/tree/5bfee12cb093df8e818a292c39a585d8bc9e8c61)
on September 1, 2020.
</em></small>

## Authors



+ **David Haberthür**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-3388-9187](https://orcid.org/0000-0003-3388-9187)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [habi](https://github.com/habi)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [habi](https://twitter.com/habi)<br>
  <small>
     Institute of Anatomy, University of Bern, Switzerland
  </small>

+ **Ruslan Hlushchuk**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-6722-8996](https://orcid.org/0000-0002-6722-8996)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [RuslanHlushchukh](https://github.com/RuslanHlushchukh)<br>
  <small>
     Institute of Anatomy, University of Bern, Switzerland
  </small>

+ **Thomas Gerhard Wolf**<br><br>
  <small>
     Department of Restorative, Preventive and Pediatric Dentistry, School of Dental Medicine, University of Bern, Switzerland; Department of Periodontology and Operative Dentistry, University Medical Center of the Johannes-Gutenberg-University Mainz, Mainz, Germany
  </small>



## Abstract {.page_break_before}

The abstract will be written at the end, here are some key points

- Python
- Only free and open-source software
- Image analysis
- Fully reproducible research
- Efficiently done, already during scan of parts of the batch.
  New scans are just dumped on the script to process.
- Probably not possible manually in the needed time-frame or extremely cumbersome (huge batch-process).
- Everyone can do/check it, show it in Binder!


## Introduction {.page_break_before}

Hereby we present a method to efficiently and reproducibly analyze large batches of teeth.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
