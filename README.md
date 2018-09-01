# Step_of_Markdown
Learn GitHub Markdown step by step

## Headings
Add one to six # symbols and a single space.

`# The largest heading`

`## The second largest heading`

`###### The smallest heading`
# The largest heading
## The second largest heading
###### The smallest heading

## Styling text
`**This is bold text**`
**This is bold text**

`__This is bold text__`
__This is bold text__

`*This text is italicized*`
*This text is italicized*

`_This text is italicized_`
_This text is italicized_

`~~This was mistaken text~~`
~~This was mistaken text~~

`**This text is _extremely_ important**`
**This text is _extremely_ important**

## Quoting text
You can quote text with `>`.

```
In the words of Abraham Lincoln:
> Pardon my French
```
In the words of Abraham Lincoln:
>Pardon my French

## Quoting code
You can call out code or a command within a sentence with single backticks.The text within the backticks will not be formatted.
```
Use `git stauts` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:

\`\`\`

git status

git add

git commit

\`\`\`

Some basic Git commands are:
```
git status
git add
git commit
```

\`\`\`python

for i in range(5):

    print(i)
    
\`\`\`

```python
for i in range(5):
    print(i)
```

## Links
You can create an inline link with wrapping link text in brackets `[]`, 
and then wrapping the URL in parentheses `()`. 
You can also use the keyboard shortcut `command + K` to create a link.

`This site was built using [GitHub Pages](https://pages.github.com)`

This site was built using [GitHub Pages](https://pages.github.com)

## Section links
You can link directly to a section in a rendered file by hovering over the section heading to expose the link:

## Relative links
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file.
For example,if you have a README file in root of your repository, and you have another image in png/1.png,
the relative link to 1.png in you README might look like this:

`[png example](png/1.png)`

[png example](png/1.png)
