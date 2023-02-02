# Python Container Action Template

Quix Library readme importer.
Import readmes from the Quix Library into MKdocs.

## Usage

Use to add readme.md files from Quix Library to MKDocs

### Example workflow

```yaml
    - name: Quix Library readme importer
      uses: SteveRosam/QuixReadmeAction@Master
      with:
        GIT_URL: "https://github.com/quixio/quix-library"
        REPO_PATH: "./repo"
        DOCS_PATH: "./docs"
        REPLACEMENT_PLACEHOLDER: "      - 'ConnectorsGetInsertedHere': ''"
        README_DEST: "docs/docs/library_readmes/connectors"
```

### Inputs


### Outputs

## Examples

### Using the optional input

### Using outputs
