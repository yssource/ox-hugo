+++
title = "Citation Forms"
description = "Demonstrating different styles / forms of citations"
tags = ["pandoc", "citations", "forms"]
draft = false
+++

## Citations in square brackets

The citations withing square brackets will be rendered within
parentheses.

``` org
Blah blah [see @doe99, pp. 33-35; also @smith04, ch. 1].
```

Blah blah (see Doe [1999](#ref-doe99), 4:33--35; also Smith
[2004](#ref-smith04), ch. 1).

``` org
Blah blah [@doe99, pp. 33-35, 38-39].
```

Blah blah (Doe [1999](#ref-doe99), 4:33--35, 38--39).

``` org
Blah blah [@smith04; @doe99].
```

Blah blah (Smith [2004](#ref-smith04); Doe [1999](#ref-doe99)).

## Citations with author name suppressed

A minus sign (`-`) before the `@` will suppress mention of the author in
the citation. This can be useful when the author is already mentioned in
the text.

``` org
Smith says blah [-@smith04].
```

Smith says blah ([2004](#ref-smith04)).

## In-text citations (no square brackets) {#in-text-citations--no-square-brackets}

``` org
@smith04 says blah.
```

Smith ([2004](#ref-smith04)) says blah.

``` org
@smith04 [p. 33] says blah.
```

Smith ([2004](#ref-smith04), 7:33) says blah.

## Actual citations for this test post :)

See Xie ([2017](#ref-addCite17)); ("Bibliographies and Citations /
Citations," [n.d.](#ref-rmdCitations)) for more.

## References {#references}

<div id="refs" class="references">
  <div></div>


<div id="ref-rmdCitations">
  <div></div>

"Bibliographies and Citations / Citations." n.d. In *RMarkdown*.
RStudio.
<https://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html#citations>.

</div>

<div id="ref-doe99">
  <div></div>

Doe, John. 1999. *An Awesome Revelation*. 3rd ed. Vol. 4. 10th Ser. The
address: Publisher Foo.

</div>

<div id="ref-smith04">
  <div></div>

Smith, Adam. 2004. *The Book on Life*. 1st ed. Vol. 7. 99th Ser. The
address: Publisher Bar.

</div>

<div id="ref-addCite17">
  <div></div>

Xie, Yihui. 2017. "Adding Citations to Posts."
<https://blogdown-demo.rbind.io/2017/08/28/adding-citations-to-posts/>.

</div>

</div>
