# NightCandle-markdown-theme-for-pdf-doc

use vscode markdown-pdf extension

you can add math eqquations support in your markdown file by adding the following code into the template.html file located at

``` bash

/Users/<username>/.vscode/extensions/yzane.markdown-pdf-1.4.1/template/template.html

```

``` html

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });</script>

```
