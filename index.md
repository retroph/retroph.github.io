## About


## Speedrun Stuff
### Discord Bots

### Twitter Bots

{% for account in site.data.twitter %}
- [{{ account.desc }}](https://twitter.com/{{ account.name }})
{% endfor %}

## Twitter List

{% include twitter-bots.html %}

## MISC
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
