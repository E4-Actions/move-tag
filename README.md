# GitHub Action - Move Tag

## Usage

### Inputs

- `commitish`: Any branch or commit SHA the Git tag is created from, unused if the Git tag already exists.
- `tag_name`: The name of the tag. This should come from the webhook payload, `github.GITHUB_REF` when a user pushes a new tag.