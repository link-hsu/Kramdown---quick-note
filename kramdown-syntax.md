# kramdown

## Header
## This is header

## Quoteblock
> This is quoteblock
> >Quoteblock can be used nested

> quoteblock for multi-line
> line two

> quoteblock for multi-line
line two
line three

## Code clock
sample for code block
    code block here

~~~ ruby
def what
end
~~~

## Lists
1. this is ul>li-1
2. this is ul>li-2
3. this is ul>li-3
   ul>li-3

There has to be at least one blank line if you want to follow a paragraph with a list:
This is a paragraph.
1. This is NOT a list.

1. This is a list!

* Item one
+ Item two
- Item three

## Definition lists
term
: definition
: another definition

another term
and another term
: and a definition for the term

## Tables
| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Links and Images
A [link](http://kramdown.gettalong.org "hp")
to the homepage.

## Inline Attributes
This is *red*{: style="color: red"}.

*[kramdown_quick_reference](https://kramdown.gettalong.org/quickref.html)*
