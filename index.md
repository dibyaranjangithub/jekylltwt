---
key: vale
title: Index
author: Dibya
date: 9th Nov 2021
layout: template
---

This, `index.md`, is the front matter, Jekyll transformer recognises if the page starts with three `---` and end with three `---` , example:

```
---
author: Dibya
---
```

### This page is written by {{page.author}} on {{page.date}} at {{site.place}} in {{site.when}}

Follwoing is the liquid syntax for _data file:

```
{% for item in list %}
keep doing something till the last item
{% endfor %}

```

{% for item in site.data.datafile %}
- {{item.year}} : {{item.film}}
{% endfor %}

{% include sample_text.md %}

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

#### Steps (Ordered List):

You can keep 1, 2, 3, as serial numbers, and just 1,1,1,1,1 will also show as steps

1. Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
2. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
3. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.


#### Unordered List 
Listed with -, example:

```
- Example
- Example
- Example
```

- Example
- Example
- Example

#### Table:

```
| column heading |
column heading |
|------------------------|-----
-----------------|
| row text | row text |
| row text | row text |
```

| Name | Type | Description |
| ------ | ---- | ------- |
|Example|Example|Example|
|Example|Example|Example|

#### Code Block:

Code block is enclosed within ```

```
// This is a JS example
var test = "Hello";
console.log(test);
```

### Code inline:

Code inline is enclosed within `

`isEnabled:True`
`CTRL`

#### Link:
This is a [link](https://www.google.com/)
