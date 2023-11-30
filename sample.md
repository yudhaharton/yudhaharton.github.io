---
title: Sample Page
feature_text: |
  A demo of Markdown and HTML includes
feature_image: "https://picsum.photos/2560/600?image=873"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://wwww.google.com "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://wwww.google.com "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="wwww.google.com" %}

{% include button.html text="A button with icon" link="https://twitter.com" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://wwww.google.com" %}
{% include button.html text="A button with icon" link="https://twitter.com/" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/){% endraw %}
```

### Video include

{% include video.html id="RDE6Uz73A7g" title="The Hunger Games: The Ballad of Songbirds & Snakes (2023) Official Trailer" %}

``` html
{% raw %}{% include video.html id="RDE6Uz73A7g" title="The Hunger Games: The Ballad of Songbirds & Snakes (2023) Official Trailer
" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://assets.playgroundai.com/921fa7b2-0dc8-4e22-bc55-035f319f57dc.jpg" alt="Image with just alt text" %}{% endraw %}
```
