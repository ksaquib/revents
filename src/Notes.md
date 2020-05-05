##  _this_ word would become italic.
##  This will **really** get your point across.

## Place the asterisks **_on the outside_**, just to make it more legible.

# Header 1(used rarely)
## Header 2
### Header 3
#### Header 4
##### Header 5 
###### Header 6 (used rarely)

##### There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ).

[Search for it.](www.google.com)

[You're **really, really** going to want to see this.](www.dailykkitten.com)

#### The Latest News from [the BBC](www.bbc.com/news)

### The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:
Do you want to [see something fun][a fun place]?

[a fun place]: www.google.com

### he difference between links and images is that images are prefaced with an exclamation point ( ! ).

![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)

### Although you don't need to add alt text, it will make your content accessible to your audience, including people who are visually impaired, use screen readers, or do not have high speed internet connections.

[Black cat][Black]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

###  A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. For example:

I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

### You can also place a caret character on each line of the quote.


>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...

>His _father_ told him that story: his father looked at him through a glass: he had a hairy face.

>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon **Saquib**.

### To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ). Each list item also gets its own line. For example, a grocery list in Markdown might look like this:

* Milk
* _Egg_
* S**al**mon
* Butter

### An ordered list is prefaced with numbers, instead of asterisks. Take a look at this recipe:

1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl

### Nested List

* Tintin
  * >A reporter

* Haddock
  * A sea captain

### This is what's known as a hard break; what our poetry asks for is a soft break. You can accomplish this by inserting two spaces after each new line. This is not possible to see, since spaces are invisible, but it'd look something like this 
### To break to a new line use two spaces 

Do I contradict myself?  
Very well then I contradict myself,  
(I am large, I contain multitudes.)  

### Horizontal Line 
---
`code`

## Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

## Fenced Code Block 

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

~~Saquib~~

### Task List 

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

