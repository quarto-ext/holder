# Holder Extension For Quarto

Quarto extension to create placeholder images (based on <https://github.com/imsky/holder>).

> Quarto 1.5 will include a built in placeholder shortcode which should work in most output format: https://prerelease.quarto.org/docs/authoring/placeholder.html

## Installing

```bash
quarto add quarto-ext/holder
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

Specify a size and optionally text for the placeholder as follows:

```markdown
{{< holder 300x300 >}}
{{< holder 300x300 "hello" >}}
```

You can also include holder.js options (e.g. `theme`, `bg`, `align`, etc.):

```markdown
{{< holder 300x300 "hello" theme="sky" >}}
{{< holder 300x300 "hello" align="left" >}}
```

See the documentation on Holder [placeholder options](https://github.com/imsky/holder#placeholder-options) for the details and usage of various options.

## Examples

This page includes some examples that demonstrate various holder options: <https://quarto-ext.github.io/holder/>.
