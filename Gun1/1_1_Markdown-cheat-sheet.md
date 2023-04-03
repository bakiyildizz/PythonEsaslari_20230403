# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


```javascript
function test() {
console.log("look ma’, no spaces");
}
```

```shell
> py
> print("merhaba")
> help("print")

```

Shell:      console, shell
Bash:       bash, sh, zsh
PowerShell: powershell, ps
DOS:        dos, bat, cmd

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Klavye tuşları
<kbd>Ctrl+Shift+F1</kbd>

### Matematiksel ifadeler
https://rmd4sci.njtierney.com/math
$x^2$
$\int$
$\infty$

$\int_0^\infty x^{-\alpha}$

* $\frac{1}{2}$
* $\sum_{i=1}^{n}$
* $\sqrt{p}$



### Task List (Bu jupyter de olmadı)

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


### Matrix üretmek için
$$
\left[
	\begin{array}{cc} 
		m11&m12 \\
		m21&m22
	\end{array}
\right] 
$$
