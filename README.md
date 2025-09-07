# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
---
<!-- Paragraph with line break -->
This is the first line.    
And this is the second line.

---
<!-- Bold -->
I just love **bold text**.

---
<!-- Italic -->
Italicized text is the *cat's meow*.

---
<!-- Bold and Italic -->
This text is ***really important***.

---
<!-- Blockquotes -->
> Dorothy followed her through many of the beautiful rooms in her castle.

---
<!-- Blockquotes with Multiple Paragraphs -->
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---
<!-- Nested Blockquotes -->
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---
<!-- Blockquotes with Other Elements -->
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

---
<!-- Ordered Lists -->
1. First item  
2. Second item  
3. Third item 
	1. Indented item  
	2. Indented item
4. Fourth item

---
<!-- Unordered Lists -->
- First item  
- Second item  
- Third item 
	- Indented item  
	- Indented item  
- Fourth item

* First item  
* Second item  
* Third item  
* Fourth item

+ First item  
+ Second item  
+ Third item  
+ Fourth item

---
<!-- Code -->
At the command prompt, type `nano`.

---
<!-- Links -->
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

---
<!-- Adding Titles -->
<!-- You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL. -->
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

---
<!-- URLs and Email Addresses -->
<https://www.markdownguide.org>  
<fake@example.com>

---
<!-- Formatting Links -->
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

---
<!-- Reference-style Links -->
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[2]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Two"
[3]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Three'
[4]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Four)
[5]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Five"
[6]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Six'
[7]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Seven)

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][6], and that means comfort.

---
<!-- Images -->
![The San Juan Mountains are beautiful!](https://upload.wikimedia.org/wikipedia/commons/e/eb/Ash_Tree_-_geograph.org.uk_-_590710.jpg "San Juan Mountains")

---
<!-- Linking Images -->
[![The San Juan Mountains are beautiful!](https://upload.wikimedia.org/wikipedia/commons/e/eb/Ash_Tree_-_geograph.org.uk_-_590710.jpg "San Juan Mountains")](https://upload.wikimedia.org/wikipedia/commons/e/eb/Ash_Tree_-_geograph.org.uk_-_590710.jpg)

---
<!-- Tables -->
| Syntax       | Description |
| ---   | ---  |
| Header | Title |
| Paragraph | Text |

---
<!-- Alignment -->
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

---
<!-- Fenced Code Blocks & Syntax Highlighting -->
<!-- Depending on your Markdown processor or editor, you’ll use three backticks (```) or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines! -->
``` json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

---
<!-- Footnotes -->
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

---
<!-- Heading IDs -->
### My Great Heading {#custom-id}

---
<!-- Linking to Heading IDs -->
[Heading IDs](#heading-ids)

---
<!-- Definition Lists -->
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>

---
<!-- Definition Lists -->
~~The world is flat.~~ We now know that the world is round.

---
<!-- Task Lists -->
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

---
<!-- Using Emoji Shortcodes -->
Gone camping! :tent: Be back soon.  
That is so funny! :joy:

---
<!-- Highlight -->
I need to highlight these <mark>very important words</mark>.

---
<!-- Subscript -->
H<sub>2</sub>O

---
<!-- Superscript -->
X<sup>2</sup>

---
<!-- Disabling Automatic URL Linking -->
`http://www.example.com`
