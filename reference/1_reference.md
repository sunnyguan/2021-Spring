# Reference

This document will keep track of the various tools that I use in my Markdown files to generate cool stuff. Compare the generated PDF as well as the raw Markdown file (make sure to click the `raw` button on Github and not use the built-in viewer).

For example, to get a simple orange box with an orange title, you can use this:

:::orange
\boxtitle{orange}{Title}

Some text here
:::

There is also the option to add in a colored "subtitle":

:::blue
\boxtitle{blue}{Theorem} \boxsubtitle{blue}{1.12}

$1+1=2$
:::

For more generic tcolorbox, you can try:

:::note
A note
:::

:::definition
A definition
:::

:::theorem
A theorem
:::

:::warning
A warning
:::

These are faster to write, but doesn't allow you to customize the title.
