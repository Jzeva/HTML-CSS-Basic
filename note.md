# HTML

The difference between span and p:

The span element is inline element, and it will not start on new line.
And p is block level element, and it will start on new line.

The src attribute of img has to be relative.

The href attribute of a tag  stands for "Hyper reference".

The blockquote tag specifies a section that is quoted from another source

### Link Tag:
```
https://www.w3schools.com/tags/tag_link.asp

The <link> tag defines the relationship between the current document and an external resource.

The <link> tag is most often used to link to external style sheets or to add a favicon to your website.

The <link> element is an empty element, it contains attributes only.
```


# CSS

### Selector
 Pseudo selector is more specific than general selector. 
```css
first-child: 
if use first-child selector to ul and li, it should be like this:

li: first-child{
    xxx
}

nth-child(n){
    xxx
}
```
Style the h tag which is the only child of its parent element.
```css
h:only-child{
    xxx
}
```


Style the a tag following the h2 tag
```css
h2 + a {
    xxx
}
```
Style the button following the textarea #and they have the same parent element#
```css
textarea ~ button{
    xxx
}
```

Style every single li which is the direct child of the ul
```css
##Child Selector
ul > li{
    xxx
}
```

//style every single li inside the ul
```css
##Descent Selector
ul li{
    xxx
}
```
