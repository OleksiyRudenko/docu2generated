# Generated content

The project is used to illustrate generated content import
to a [centralized documentation store](https://github.com/OleksiyRudenko/docu2main)
managed by [Docusaurus 2](https://v2.docusaurus.io/).

The flow:
- build content for publishing (`yarn build`)
- push the content to an orphaned branch (`yarn deploy`)
- trigger import action in the remote centralized documentation store

For demo purposes source files from `src/` are just copied to `build/`
directory.
