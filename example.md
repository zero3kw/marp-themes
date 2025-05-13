---
marp: true
theme: class
paginate: true
size: 16:9
---

<div class="container">
  <div class="child"></div>
</div>

<div class="triangle_left"></div>
<div class="triangle_bottom"></div>

https://placehold.jp/ccc/ccc/150x150.png

![center](https://placehold.jp/ccc/ccc/150x150.png?css=%7B%22clip-path%22%3A%22%20polygon(50%25%200%2C%200%20100%25%2C%20100%25%20100%25)%22%7D)

---

<!-- _class: title -->

# **Slide Template**

YYYY/MM/DD
Your Name

---
# <!-- fit --> Fitting header

---
<!-- _class: lead -->

Section Title

---

# h1 Heading :sunglasses:
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

---

# Paragraphs

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

First line with two spaces after.
And the next line.

First line with the HTML tag after.<br>
And the next line.

---

# Emphasis

## Bold

I just love **bold text**.

## Italic

Italicized text is the *cat's meow*.

## Bold and Italic

This text is ***really important***.

~~Strikethrough~~

---

## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

---
# Fragmented list

## Bullet list

- First item
- Second item
  - Indented item
- Third item

## Ordered list

1. First item
1. Second item
1. Third item

---

Text text text[^1]
Text text text[^2]

[^1]: ^1
[^2]: ^2

> [^1]: This is the footnote.
> [^2]: This is the footnote.

---

# Multi 2columns in Marp slide

<div class="2columns">
<div>

## Column 1
- List 1
  - List 2
    - List 3

</div>
<div>

## Column 2
- List 1
  - List 2
    - List 3

</div>
</div>

---

# Multi 3columns in Marp slide

<div class="3columns">
  <div>

## First
- List 1
  - List 2
    - List 3

  </div>
  <div>

## Second
- List 1
  - List 2
    - List 3

  </div>
  <div>

## Third
- List 1
  - List 2
    - List 3

  </div>
</div>

---

# Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

---

# Tables

<div class="2columns">
  <div>

## First
| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

  </div>
  <div>

## Second
| 左揃え | 中央揃え | 右揃え |
| :----- | :------: | -----: |
| 1      |    2     |      3 |
| 4      |    5     |      6 |

  </div>
</div>



---

# Task Lists

:white_check_mark: Write the press release
:white_large_square: Update the website
:white_large_square: Contact the media

---

# Automatic URL Linking

https://www.example.com

# Disabling Automatic URL Linking

`https://www.example.com`

---
# iframe

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3213.071648444671!2d139.14176551527757!3d36.359043380041854!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x601eee4184f6138d%3A0xe462235debd529db!2z5YWx5oSb5a2m5ZyS5YmN5qmL5Zu96Zqb5aSn5a2m!5e0!3m2!1sja!2sjp!4v1646892557470!5m2!1sja!2sjp" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

---
# Notes

<div class="note info">

###### hoge

:bulb: Do not push the big red button.


</div>

<div class="note warn">

:warning: Do not push the big red button.

</div>

<div class="note alert">

:no_entry: Remember to appreciate the little things in life.

</div>

---

# Admonitions

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

---

<!-- _header: Embed Youtube -->

<iframe width="100%" height="100%" src="https://www.youtube-nocookie.com/embed/-QFxG9qDLoo?rel=0&controls=0&loop=1&playlist=-QFxG9qDLoo" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

---

<!-- _header: Embed video -->

<video width="100%" height="100%" src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4" autoplay muted>

---

# Arrows

<div class="2columns">
  <div>

<div class="triangle_left" style="margin: 100px auto;"></div>

  </div>
  <div>

# I have an apple:apple:.

<div class="triangle_bottom" style="margin: auto auto;"></div>

# I have a pineapple:pineapple:.

  </div>
</div>

---
# Math typesetting

## Inline math

Render inline math such as $ax^2+bc+c$.

## Math block

$$ I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx $$

$$
f(x) =
  \int_{-\infty}^\infty
  \hat f(\xi)\,e^{2 \pi i \xi x}
  \,d\xi
$$
