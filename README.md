HEADERS
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

EMPHASIS
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*

LISTS
* Item 1
* Item 2
 * Item 2a
 * Item 2b

Ordered
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b

IMAGES
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

LINKS
http://github.com - automatic!
[GitHub](http://github.com)

BLOCKQUOTES
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.

BACKSLASH ESCAPES
Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formaing syntax.
\*literal asterisks\*

Markdown provides backslash escapes for
the following characters:
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash mark
+ plus sign
- minus sign (hyphen)
. dot
! exclamation mark

USERNAME @MENTIONS
Typing an @ symbol, followed by
a username, will notify that person
to come and view the comment.
This is called an “@mention”,
because you’re mentioning the
individual. You can also @mention
teams within an organization.

ISSUE REFERENCES
Any number that refers to an Issue or
Pull Request will be automatically
converted into a link.
#1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1

EMOJI
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
GitHub supports emoji!
To see a list of every image we
support, check out
www.emoji-cheat-sheet.com

FENCED CODE BLOCKS
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```
Markdown coverts text with four leading spaces into a code block; with GFM you can
wrap your code with ``` to create a code block without the leading spaces. Add an
optional language identifier and your code will get syntax highlighting.

TASK LISTS
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)

TABLES
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2