---
id: intro
title: Import generated content from external repo
---

# Docu 2 Import generated content

Generated content from
[generated content emulation project](https://github.com/OleksiyRudenko/docu2generated)
will be imported into [docu2main](https://github.com/OleksiyRudenko/docu2main)
documentation demo site managed by [Docusaurus 2](https://v2.docusaurus.io/).

Files from `src/` are published by copying to `build/`
and pushing to an orphaned branch, which triggers importing mechanism.
Those that are not assigned any `id`s can be referred to by their
file names without extensions.
