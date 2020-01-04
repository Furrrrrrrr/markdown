# Markdown For Typora
## Block Elements
### Paragraph and line breaks
###### This is an H6

**Markdown** 

[Daring Fireball](http://daringfireball.net/)

`Return`  around by `~`

``` markdown

```

> This is a blockquote with two paragraphs. This is first paragraph.
>
> This is second pragraph. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.



> This is another blockquote with one paragraph. There is `three empty line` to seperate two blockquote.

* star`*`

+ add `+`

- minus`-`

1. red
2. green
3. blue

- [ ] incomplete task list item  `- [ ]`

- [x] completed task list item `-[x]`

```javascript
function test() {
  console.log("notice the blank line before this function?");
}
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```java
@Data
@Entity
public class Book {
}
```

*LaTeX* around by`*`

**latex** around by`**`

***latex*** around by `***`



input `$$` and press the `Return` key, accepts *Tex/LaTex* source. More details [here](https://support.typora.io/Math/)
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

| First Header | Second Header | jfldjglfdsjgl |
| :----------: | :-----------: | :-----------: |
| Content Cell | Content Cell  |               |
| Content Cell | Content Cell  |               |