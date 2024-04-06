# Markdown Cheat Sheet
This a handy reference guide that provides a quick overview of the formatting options available in Markdown[^1]. This can be useful for anyone who wants to learn the basics of Markdown or needs a refresher on the syntax for things like bold text, italics, headings, and creating lists. With a cheat sheet at your side, you can easily format your text documents and create readable, well-structured content using Markdown.
[^1]: Article based on [Markdown Guide](https://www.markdownguide.org/) 

#### Headings:
# H1: `# H1`
## H2: `## H2`
### H3: `### H3`
#### H4: `#### H3`
### Custom Heading: {#custom-id}
`### My Great Heading {#custom-id}`

#### Styles:
**bold**: `**bold text**`
*italic*: `*italicized text*`
subscript H~2~O: `H~2~O`
superscript	X^2^: `X^2^`

#### Lists:
1. First item - `1. First item`
    1. Sublist - `1. Sublist //add 4 spaces to indent sublist`
    2. Sublist - `2. Sublist //add 4 spaces to indent sublist`
    3. Sublist - `3. Sublist //add 4 spaces to indent sublist`
2. Second item - `2. Second item`
    * Mixed Sublist - `* Sublist //add 4 spaces to indent sublist`
    - Mixed Sublist - `- Sublist //add 4 spaces to indent sublist`
3. Third item - `3. Third item`
    1. Sublist - `1. Sublist //add 4 spaces to indent sublist`
    * Mixed Sublist - `* Sublist //add 4 spaces to indent sublist`
    - Mixed Sublist - `- Sublist //add 4 spaces to indent sublist`

- Bullet list - `- Bullet list`
    - Sublist - `- Sublist //add 4 spaces to indent sublist`
- Bullet list - `- Bullet list`
    - Sublist - `- Sublist //add 4 spaces to indent sublist`

#### Tools:
* Inline code - `code` - just use the backtick (`) in the begining and the end of the code.
* Link - `[title](http://www.example.com)`
* Image - `![alt text](source/to/image.png)`
* > blockquote: `> blockquote`
* Horizontal Rule - `---` :
---

#### Extended
* Fenced Code Syntax:
```
Add three backticks ``` one line up and one line down to your code.
```
* Fenced Code Example:
![Fenced code example](/source/articles/md_img/01.png)
* Table Syntax:
```
| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Header | Title |
| Paragraph | Text |
```

* Table Example:

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

* Footnote Syntax:

```
Here's a sentence with a footnote. [^2]
[^2]: This is the footnote.
```

* Footnote Example:
Here's a sentence with a footnote.[^2]
[^2]: This is the footnote.

* Definition List Syntax:

```
term
: definition
```

* Definition List Example:

First Term
: Single definition.

Second Term
: definition part one.
: definition parte two.

* Strikethrough Sintax:
`~~Strikethough text~~`
* Strikethrough Example:
~~Strikethough text~~

* Task List Sintax:
```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
* Strikethrough Example:
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

* Emoji Sintax[^3]:
` That is so funny! :joy: `
[^3]: You can find a list of emoji shortcodes [here](https://gist.github.com/rxaviers/7360908).
* Emoji Example:
That is so funny! :joy:

* Highlight Sintax:
`I need to highlight these ==very important words==.`
* Highlight Example:
I need to highlight these ==very important words==.

