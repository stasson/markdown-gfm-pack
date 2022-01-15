# markdown-gfm-pack

Github & Gitlab Flavoured Markdown Essential Pack

## Extension pack

### GFM Preview

- [Markdown Preview GitHub Styling] - CSS that makes the preview match GitHub's
  markdown style.

- [Markdown Emoji] - Adds `:emoji:` support to the markdown preview.

- [Markdown Checkboxes] - Adds `- [ ] tasklist` support to the markdown preview

- [Markdown yaml Preamble] - Adds support for rendering the yaml frontmatter as
  a table. Be sure to set `"markdown.previewFrontMatter": "show"`

- [Markdown Footnotes] - Adds `[^1]` footnote syntax support to VS Code's
  built-in Markdown preview

- [Mermaid Support] -Adds Mermaid diagram and flowchart support to VS Code's
  builtin markdown preview

- [PlantUML Support] - Rich PlantUML support with markdown integration

- [Math Support] - TeX math rendering in markdown

### Lint & formatting

- [Prettier] - code formatter

- [Markdownlint] - Markdown linting and style checking

- [Code spell checker] - for code and markown

### Misc. utils

- [Markdown Shortcuts] - Handy shortcuts for editing Markdown

- [Markdown TOC] - Generate TOC (table of contents)

- [Excell To Markdown Tables] - Copy Excel data and convert to Markdown table
  format

- [docs-images] - image compression and resizing

## Configuration

- `.vscode/settings.json`

  ```json
  {
    "markdown-toc.depthFrom": 2,
    "markdown-toc.depthTo": 3,
    "mdmath.delimiters": "gitlab"
  }
  ```

- `.editorconfig`

  ```text
  [*.{md,txt}]
  max_line_length = 80
  indent_style = space
  indent_size = 2
  trim_trailing_whitespace = false
  ```

- `.prettierrc`

  ```json
  {
    "singleQuote": true,
    "semi": false,
    "proseWrap": "always"
  }
  ```

## Markdownlint

| Inline config                           | Syntax                                      |
| --------------------------------------- | ------------------------------------------- |
| Disable all rules                       | `<!-- markdownlint-disable -->`             |
| Enable all rules                        | `<!-- markdownlint-enable -->`              |
| Disable one or more rules by name       | `<!-- markdownlint-disable MD001 MD005 -->` |
| Enable one or more rules by name        | `<!-- markdownlint-enable MD001 MD005 -->`  |
| Capture the current rule configuration  | `<!-- markdownlint-capture -->`             |
| Restore the captured rule configuration | `<!-- markdownlint-restore -->`             |

> see the
> [configuration section](https://github.com/DavidAnson/markdownlint#configuration)
> and the
> [rules](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md) for
> more

<!-- LINKS -->

[markdown preview github styling]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles
[markdown emoji]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji
[markdown preview github styling]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles
[markdown checkboxes]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-checkbox
[markdown yaml preamble]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-yaml-preamble
[markdown footnotes]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-footnotes
[mermaid support]:
  https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid
[plantuml support]:
  https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml
[math support]:
  https://marketplace.visualstudio.com/items?itemName=goessner.mdmath
[prettier]:
  https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
[markdownlint]:
  https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint
[code spell checker]:
  https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
[markdown shortcuts]:
  https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts
[markdown toc]:
  https://marketplace.visualstudio.com/items?itemName=huntertran.auto-markdown-toc
[excell to markdown tables]:
  https://marketplace.visualstudio.com/items?itemName=csholmq.excel-to-markdown-table
[docs-images]:
  https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-images
