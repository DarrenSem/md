# md - Markdown cheatsheet

***MarkDown*** cheatsheet - my combination of the popular ones commonly seen + some ChatGPT responses


1. **Headers**

  ```
  # This is an <h1> tag
  ## This is an <h2> tag
  ### This is an <h3> tag
  #### This is an <h4> tag
  ##### This is an <h5> tag
  ###### This is an <h6> tag
  ```
# This is an <h1> tag
## This is an <h2> tag
### This is an <h3> tag
#### This is an <h4> tag
##### This is an <h5> tag
###### This is an <h6> tag


2. **Emphasis**

  ```
  *This text will be italic*
  _This will also be italic_

  **This text will be bold**
  __This will also be bold__

  _You **can** combine them_

  ~~Strikethrough~~

  Horizontal Rule:
  ___
  ```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

~~Strikethrough~~

Horizontal Rule:
___


3. **Unordered List**

  ```
  - Item 1
  - Item 2
    - Item 2a
  ...with no line break this continues onto the next line keeping same indent as 2a
    - Item 2b
    -
  ^ ending with a bare empty bullet item (on level 2)
  ```

  ```
  + Item 1
  + Item 2
    + Item 2a
  ...with no line break this continues onto the next line keeping same indent as 2a
    + Item 2b
    +
  ^ ending with a bare empty bullet item (on level 2)
  ```

  ```
  * Item 1
  * Item 2
    * Item 2a
  ...with no line break this continues onto the next line keeping same indent as 2a
    * Item 2b
    *
  ^ ending with a bare empty bullet item (on level 2)
  ```
- Item 1
+ Item 2
  * Item 2a
...with no line break this continues onto the next line keeping same indent as 2a
  - Item 2b
  -
^ ending with a bare empty bullet item (on level 2)


4. **Task Lists / TODO / Checkboxes**

  ```
  - [x] Item 1 with filled in checkbox
  - [ ] Item 2 empty unchecked
  - [ ] Item 3
    - [X] Item 3a with UpperCase 'X' for filled in checkbox
    - [x]
  this still continues onto the next line keeping same indent as its parent -- which is just the text `[x]` instead of converting into a checkbox (on level 2)
  BUT[x]--with whitespace ON ITS RIGHT SIDE-- in the middle of a line:[x] < will convert to a new checkbox **while omitting all that came before it**
  ```
- [x] Item 1 with filled in checkbox
+ [ ] Item 2 empty unchecked
* [ ] Item 3
  - [X] Item 3a with UpperCase 'X' for filled in checkbox
  - [x]
this still continues onto the next line keeping same indent as its parent -- which is just the text `[x]` instead of converting into a checkbox (on level 2)
BUT[x]--with whitespace ON ITS RIGHT SIDE-- in the middle of a line:[x] < will convert to a new checkbox **while omitting all that came before it**


5. **Ordered List**

  ```
  1. Item 1
  4. Item 2
  2. Item 3
     5. Item 5 under #3 (3 spaces needed, not just 2?)
     7. Item 6 under #3
  ```
1. Item 1
4. Item 2
2. Item 3
   5. Item 5 under #3 (3 spaces needed, not just 2?)
   7. Item 6 under #3


6. **Links**

  ```
  http://github.com - automatic!
  [GitHub](http://github.com)
  [GitHub](http://github.com "title text too!")
  ```
http://github.com - automatic!
[GitHub](http://github.com)
[GitHub](http://github.com "title text too!")


7. **Images**

  ```
  Format: ![Alt Text](url)
  ![GitHub Logo](/images/logo.png)

  ![GitHub Logo](/images/logo.png "title text too -- visible when you hover, different than Alt Text, esp. helpful for a _broken link_ 'image' AKA no image actually shown.")

  ![alt-text:   pfp for https://github.com/mathiasbynens](https://avatars.githubusercontent.com/u/81942?v=4 "title-hover:   Mathias' pfp")
  ```
Format: ![Alt Text](url)

![GitHub Logo](/images/logo.png)

![GitHub Logo](/images/logo.png "title text too -- visible when you hover, different than Alt Text, esp. helpful for a _broken link_ 'image' AKA no image actually shown.")

![alt-text:   pfp for https://github.com/mathiasbynens](https://avatars.githubusercontent.com/u/81942?v=4 "title-hover:   Mathias' pfp")


8. **Blockquotes**

  ```
  As Kanye West said:

  > We're living the future so
  > the present is our past.
  > Blockquotes can also be nested...
  >> ...by using additional greater-than signs right next to each other...
  > > > ...or with spaces between arrows.
  ```
As Kanye West said:

> We're living the future so
> the present is our past.
> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


9. **Inline code**

  ```
  Inline `code` has `back-ticks around` it.
  ```
Inline `code` has `back-ticks around` it.


10. **Multiline Code**

  ```
  \```js
  /* multi-line code
     comment.
  */
  var foo = function (bar) {
    return bar++;
  };

  console.log(foo(5));
  \```
  ```
```js
/* multi-line code
   comment.
*/
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```


11. **Tables**

  ```
  | Formatting  | Syntax    | Example |
  | ----------- | --------- | ------- |
  | Italic      | `* *` or `_ _` | *italic*  |
  | Bold        | `** **` or `__ __`  | **bold** |

  Right aligned columns

  | Option | Description (right-aligned) |
  | ------:| -----------:|
  | data   | path to data files to supply the data that will be passed into templates. |
  | engine | engine to be used for processing templates. Handlebars is the default. |
  | ext    | extension to be used for dest files. |
  ```
| Formatting  | Syntax    | Example |
| ----------- | --------- | ------- |
| Italic      | `* *` or `_ _` | *italic*  |
| Bold        | `** **` or `__ __`  | **bold** |

Right aligned columns

| Option | Description (right-aligned) |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


`-END OF LINE.`
