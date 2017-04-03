## Using Jekyll's _data feature

Jekyll supports a [Data Files](https://jekyllrb.com/docs/datafiles/) feature that lets YAML/JSON files to be loaded and made available as Liquid variables.

### Known Problems with this approach

Because Jekyll is parsing the JSON/YAML, any syntax errors or problems with parsing will cause the site to fail to deploy, and will issue an error email to the owner of the repo.

### Naming conventions

- Please use `.yaml` or `.json` file extensions (lowercase) to ensure compatibility with various Phenopacket tools.
- Please avoid using non-alphanumeric characters in your filename, except for non-space separators such as `-` or `_`.

