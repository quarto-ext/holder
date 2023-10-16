# Holder Extension For Quarto

Quarto extension to create placholder images (based on <https://github.com/imsky/holder>).

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

See the documention on Holder [placeholder options](https://github.com/imsky/holder#placeholder-options) for the details and usage of various options.
