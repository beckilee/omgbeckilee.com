---
tags:
  - Documentation
  - Procedure
  - Code samples
  - Policy-as-code
  - Infrastructure-as-code
---

# Regula pre-commit hook

:material-web: [Best viewed on the live website.](https://regula.dev/integrations/pre-commit.html){ target="_blank" rel="noopener noreferrer" }

[![Regula pre-commit hook screenshot](images/thumb-doc-regula-precommit-hook.png)](https://regula.dev/integrations/pre-commit.html){ target="_blank" rel="noopener noreferrer" }

I wrote this **procedure** to explain how to use a pre-commit hook to check infrastructure-as-code for policy violations before the code is committed. An engineer provided the initial `.pre-commit-config.yaml` configuration. I modified the hook slightly, and then I tested it on HashiCorp Terraform and AWS CloudFormation configurations I had written.

!!! abstract "Links"
    <ul class="star-list"><li>[**PDF**](pdfs/doc-regula-precommit-hook.pdf){ target="_blank" rel="noopener noreferrer" }: View a downloadable copy of the original document.</li>
    <li>[**Archived webpage**](https://web.archive.org/web/20230331150609/https://regula.dev/integrations/pre-commit.html){ target="_blank" rel="noopener noreferrer" }: View an archived copy of the document on the Wayback Machine.</li>
    <li class="star-bullet" title="Recommended view">[**Live site**](https://regula.dev/integrations/pre-commit.html){ target="_blank" rel="noopener noreferrer" }: View the document on the live website. Note that the content may have been updated since I wrote it.</li></ul>