# Lists

The Aquent site supports several different types of lists, both standard, and modified. Standard lists include any markup with `<ol>`, `<ul>`, and `<dl>`.

## Bullet coloring

For `<ul>` elements, bullets are either strictly `$orange` or `$neutral-8` per our color standards and SASS variables. Bullets are neutral-8 on orange backgrounds, and orange everywhere else. These colors will change automatically based on the use of acceptable wrapper classes for orange backgrounds.

## Custom Lists

### Counter Lists

Counter lists use a custom, large, orange ordered counter in place of the tradition `list-style` numeral. These lists also present with an increased font size.

#### Footnotes

To create a footnotes list, it must also be a counter list. As such, it requires a `counter` class along with the additional class: `footnote`. The primary difference is the usage of a bracket wrapper around the numeral.

If a `<ul>` is used within a footnote element, these bullets _will break pattern_ with normal bulleted lists and will display as `$neutral-3` gray.

#### No Bullet
Both ordered and unordered lists can have their bullet/counter removed when necessary by applying the `no-bullet` class.