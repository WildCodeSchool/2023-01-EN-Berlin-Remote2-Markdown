
# Introduction

This
is
a
paragraph
spread
along
many
lines.

The advantage of this design is that a very long paragraph can be spread over multiple lines
in the source of the Markdown file, and this paragraph will not be broken at these points in
the rendered output.

For this reason, Markdown creates a smart way to force *a new line **WITHIN** a paragraph.* In order
to do this, we need to add two empty spaces at the end of the line to tell Markdown that this
new line should be rendered. For example  
Here  
And here  
And here.

Hey John. You do not have a cat. (Orwa)
> Would you like to help me walk my cat (John)
> > Hey John, what do you want me to do (Orwa)

This is what I want to buy from the grocery store:  
1. Milk
1. Coffee
1. Whole grain wheat
1. Cabbage

This is the same list without numbers:
- Milk
- Coffee
- Whole grain wheat
- Cabbage

Sometimes in Markdown, because it is used by programmers, we need to mention code in the text.
For example, I might want to refer to something we type in the shell, for example the `nvm` command.

This has been really cool. Now let me try to link to something: [Click here to access the WCS organization on GitHub](https://github.com/WildCodeSchool)

## Important keys on the keyboard

- <kbd>/</kbd>: Slash or a forward slash
- <kbd>&bsol;</kbd>: Backward slash
- <kbd>{</kbd> <kbd>}</kbd>: Curly brackets
- <kbd>[</kbd> <kbd>]</kbd>: Square brackets
- <kbd>&lt;</kbd> <kbd>&gt;</kbd>: Angle brackets
- <kbd>&</kbd>: Ambersand
- <kbd>:</kbd>: Colon
- <kbd>;</kbd>: Semicolon
- <kbd>|</kbd>: Pipe character
- <kbd>'</kbd>: Single quote
- <kbd>"</kbd>: Double quote
- <kbd>`</kbd>: Back tick
- <kbd>-</kbd>: Minus
- <kbd>_</kbd>: Underscore

\# This is not a title anymore

## Embedding Diagrams

Diagrams are a great example of embedding one logical language inside of another.

A single code word or phrase can be specified using backticks like `this`, a single
backtick surrounds the word or the phrase. An example of a phrase is `this is a code
phrase`.

```javascript
function test() {
  console.log("notice the blank line before this function?");
}
```

GitHub allows you to use a codeblock of the type `mermaid` to actually embed real diagrams
in your GitHub Markdown file. This is done using an embedded, and a completely distinct 
logical language only for diagramming puposes. This language is called mermaid and has its
own documentation on the internet.

```mermaid
pie title Do people believe in science
    "Those who do" : 10
    "Those who do not" : 10
    "Those who do not care" : 10
```
