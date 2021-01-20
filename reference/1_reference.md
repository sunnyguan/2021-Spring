# Reference

This document will keep track of the various tools that I use in my Markdown files to generate cool stuff. Compare the generated PDF as well as the raw Markdown file (make sure to click the `raw` button on Github and not use the built-in viewer).

For example, to get a simple orange box with an orange title, you can use this:

\begin{mybox}{orange}

    \boxtitle{orange}{Theorem 1}

    Note that the blank line separating "begin\{mybox\}" and "boxtitle" is required for the colored title to work.

\end{mybox}

There is also the option to add in a colored "subtitle":

\begin{mybox}{blue}

    \boxtitle{blue}{Definition}
    \boxtitlenb{blue}{(see textbook)}

    Make sure there is no blank space between the title and the subtitle if you want them to be on the same line.

\end{mybox}

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
