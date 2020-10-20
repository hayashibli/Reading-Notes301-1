# Responsive Web Design and Regular Expressions.

## Regex.

![img](https://i.morioh.com/2020/02/13/facbadfb91b9.jpg)

Regular expressions (regex or regexp) are extremely useful in **extracting information from any text** by searching for one or more matches of a specific search pattern (i.e. a specific sequence of ASCII or unicode characters), fields of application range from validation to parsing/replacing strings, passing through translating data to other formats and web scraping.

One of the most interesting featuers is that once you've learned the syntax, you can actually use this tool in (almost) all programming languages.

**Anchors ^ and \$**

|   Regex    |                         Usage                         |
| :--------: | :---------------------------------------------------: |
|    ^The    |        matches ant string that start with The         |
|   end\$    |         matches ant string that ends with end         |
| ^The end\$ | exact string match (start with The and ends with end) |
|    roar    |     match any string that has the text roar in it     |
|    roar    |     match any string that has the text roar in it     |

---
**Character classes**

| Regex |                               Usage                               |
| :---: | :---------------------------------------------------------------: |
|  \d   |            matches a single character that is a digit             |
|  \D   |               matches a single non-digit character                |
|  \w   | matches a word character (alphanumeric character plus underscore) |
|  \s   | matches a word character (alphanumeric character plus underscore) |
|   .   |                       matches any character                       |

---



## CSS Grid.
![img](https://media.blogg.fsh.se/2018/07/css-grid.jpeg)

CSS Grid Layout (aka “Grid”), is a two-dimensional grid-based layout system that aims to do nothing less than completely change the way we design grid-based user interfaces. CSS has always been used to lay out our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance). Flexbox helped out, but it’s intended for simpler one-dimensional layouts, not complex two-dimensional ones (Flexbox and Grid actually work very well together). Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.
