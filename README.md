# im-reset

这是一份重置样式表。在 [normalize.css](https://necolas.github.io/normalize.css/)(v7.0.0) 的基础上，根据一些使用习惯进行了归零设置，且设置所有元素的 box-sizing 为 border-box，外加一个 clearfix 类。

注：因为设置了`* {box-sizing: border-box}`，所以请在 IE8+ 或移动端使用。如果不是新项目，请慎用，因为杀伤力太大。

```css
html {
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -webkit-tap-highlight-color: transparent;
  height: 100%;
}

body {
  margin: 0;
  font-size: 14px;
  line-height: 1.5;
  color: #333;
  background-color: #fff;
  min-height: 100%;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}

audio,
canvas,
progress,
video {
  display: inline-block;
}

audio:not([controls]) {
  display: none;
  height: 0;
}

progress {
  vertical-align: baseline;
}

[hidden],
template {
  display: none;
}

a {
  background: transparent;
  -webkit-text-decoration-skip: objects;
  text-decoration: none;
  color: #08c;
}

a:active {
  outline: 0;
}

abbr[title] {
  border-bottom: 1px dotted;
  text-decoration: underline;
  text-decoration: underline dotted;
}

b,
strong {
  font-weight: inherit;
}

b,
strong {
  font-weight: bold;
}

dfn {
  font-style: italic;
}

mark {
  background: #ff0;
  color: #000;
}

small {
  font-size: 80%;
}

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sup {
  top: -0.5em;
}

sub {
  bottom: -0.25em;
}

img {
  border: 0;
  vertical-align: middle;
  max-width: 100%;
}

svg:not(:root) {
  overflow: hidden;
}

hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible;
}

pre {
  overflow: auto;
  white-space: pre;
  white-space: pre-wrap;
  word-wrap: break-word;
}

code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}

button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
  vertical-align: middle;
}

button,
input {
  overflow: visible;
}

button,
select {
  text-transform: none;
}

button,
html input[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
}

[disabled] {
  cursor: default;
}

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  border-style: none;
  padding: 0;
}

input {
  line-height: normal;
}

input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}

input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}

input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: border-box;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}

legend {
  border: 0;
  padding: 0;
}

textarea {
  overflow: auto;
  resize: vertical;
  vertical-align: top;
}

optgroup {
  font-weight: bold;
}

input,
select,
textarea,
button {
  outline: 0;
}

textarea,
input {
  -webkit-user-modify: read-write-plaintext-only;
}

input::-ms-clear,
input::-ms-reveal {
  display: none;
}

input::-moz-placeholder,
textarea::-moz-placeholder {
  color: #999;
}

input:-ms-input-placeholder,
textarea:-ms-input-placeholder {
  color: #999;
}

input::-webkit-input-placeholder,
textarea::-webkit-input-placeholder {
  color: #999;
}

.placeholder {
  color: #999;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

td,
th {
  padding: 0;
}

h1, h2, h3, h4, h5, h6, p, figure, form, blockquote {
  margin: 0;
}

ul, ol, li, dl, dd {
  margin: 0;
  padding: 0;
}

ul, ol {
  list-style: none outside none;
}

h1, h2, h3 {
  line-height: 2;
  font-weight: normal;
}

h1 {
  font-size: 18px;
}

h2 {
  font-size: 16px;
}

h3 {
  font-size: 14px;
}

i {
  font-style: normal;
}

* {
  box-sizing: border-box;
}

.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
```