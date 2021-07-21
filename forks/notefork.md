[markdown guide](https://markdownmonster.west-wind.com/docs/_53a0pfz0t.htm)

# CSS Notes

[MDN CSS Index](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index)

[CSS Test Harness](test.csswg.org/harness/)
>this is a test of CSS conformance.

[Current CSS W3 News](w3.org/Style/CSS/current-work)

# Flexbox
## flex containers
## flex item
## default properties
## Two types of CSS Statements
### <src href="#at-rules">at-rules</a>
### rule sets
<section title="article">
<h2 id="at-rules">At-Rules</h2>
  - at-keyword '@' followed by <strong>Identifier</strong> <example>@import @page</example> <br>
  -  at rule inlcudes everything until <strong>sem-colon `;`</strong> or the next <u>block</u> <br>
- <example>
  - <code>@import "subs.css";
    h1 {color: blue }</code> <br>
  - <important>but it does not work with: </important>
    <code>@media print { @import "print-main.css"} body { font-size: 10pt} </code>
  - Cannot have an at-rule identifier inside another
     one. <br>
  - <def style="color:green">escaped character</def>
     : quotes - the second quote excapes text. Must have a <strong>block</strong> that starts with a <emphasis>'{ '</emphasis> and ends with a '}'
     - <emphasis>Declaration bock = left curly '{' brace + semi-colon ';' seperated declarations + right curly '}' brace </emphasis>
   - Ignore COMMAS
     </section>
<p>
Block-start & inline-start of labsolutely-positioned box within the static-position rectangle: content box.</p>

The *content box* is the *alignment container* of the static-position offsets of an **absollutely-positioned** box.

<Note class="note" style="background:green;"> this is a note</Note>
## Properties block level Element
> pseudo-elements
>   <element>:before
>   <element>:after
> font properties
> text-decoration
> text-transform
> letter-spacing
> word-spacing
> line-height
> flot
> vertical-align (only if flote is none)
> margin properties
> padding properties
> border properties
> colorproerty
> background properties
