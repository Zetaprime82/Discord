# Markdown Text 101

Want to inject some flavor into your everyday text chat? You're in luck! Discord uses Markdown, a simple plain text formatting system that'll help you **make your sentences stand out**. Here's how to do it! Just add a few characters before & after your desired text to change your text! I'll show you some examples...

**What this guide covers:**

- [Text Formatting](#text-formatting)
- [Organizational Text Formatting](#organizational-text-formatting)
  - [Headers](#headers)
  - [Subtext](#subtext)
  - [Masked Links](#masked-links)
  - [Unordered Lists](#unordered-lists)
  - [Ordered Lists](#ordered-lists)
- [Code Blocks](#code-blocks)
- [Block Quotes](#block-quotes)
- [Spoiler Tags](#spoiler-tags)
- [Syntax Highlighting](#syntax-highlighting)

## Text Formatting
<table style="height: 120px;">
<tbody>
<tr>
<td class="wysiwyg-text-align-left" style="width: 151px;"><em>Italics</em></td>
<td class="wysiwyg-text-align-left" style="width: 178px;">*italics* <strong>or</strong> _italics_</td>
<td class="wysiwyg-text-align-left" style="width: 153px;"><em><span class="wysiwyg-underline">Underline italics</span></em></td>
<td class="wysiwyg-text-align-left" style="width: 191px;">__*underline italics*__</td>
</tr>
<tr>
<td class="wysiwyg-text-align-left" style="width: 151px;"><strong>Bold</strong></td>
<td class="wysiwyg-text-align-left" style="width: 178px;">**bold**</td>
<td class="wysiwyg-text-align-left" style="width: 153px;"><span class="wysiwyg-underline"><strong>Underline bold</strong></span></td>
<td class="wysiwyg-text-align-left" style="width: 191px;">__**underline bold**__</td>
</tr>
<tr>
<td class="wysiwyg-text-align-left" style="width: 151px;"><em><strong>Bold Italics</strong></em></td>
<td class="wysiwyg-text-align-left" style="width: 178px;">***bold italics***</td>
<td class="wysiwyg-text-align-left" style="width: 153px;"><span class="wysiwyg-underline"><em><strong>underline bold italics</strong></em></span></td>
<td class="wysiwyg-text-align-left" style="width: 191px;">__***underline bold italics***__</td>
</tr>
<tr>
<td class="wysiwyg-text-align-left" style="width: 151px;"><span class="wysiwyg-underline">Underline</span></td>
<td class="wysiwyg-text-align-left" style="width: 178px;">__underline__</td>
<td class="wysiwyg-text-align-left" style="width: 153px;"><s>Strikethrough</s></td>
<td class="wysiwyg-text-align-left" style="width: 191px;">&nbsp;~~Strikethrough~~</td>
</tr>
</tbody>
</table>

Don't want to use markdown? You can slap a backslash in front of your statement, or put your message in a code block, and it'll escape the markdown formatting. You'll see those asterisks as you'd like!

## Organizational Text Formatting

### Headers

<div class="tip-box">
<strong>Note:</strong> Don’t forget to add a space between the leading heading character (<code>#</code>, <code>##</code>, <code>###</code>) and your text!</div>

To create a header, you need to include a specific number of the hash/pound sign character (#). Use (#) for a big header, (##) for a smaller header, or (###) for an even smaller header as the first character(s) in a new line.
<p class="wysiwyg-text-align-center"><img alt="link_example_two.png" class="optanon-category-C0002 " data-src="[https://i.imgur.com/9dhQ4SE"></p>
![headers](https://i.imgur.com/9dhQ4SE.png)

### Subtext

<p>Like <strong>Headers</strong>, you can add subtext to any chat message. To do so, add a (<code>-# </code>) before the text you want to appear in the subtext. Don’t forget the space after # before your message. For example:&nbsp;</p>
<span style="color: #434343;" data-darkreader-inline-color="">Subtext works very similarly to Headers, so the (<code>-#</code>) must be at the very beginning of the line in order for it to work.</span>

![subtext](https://i.imgur.com/ADFapDa.png)

### Masked Links

You can use masked links to make text a clickable or pressable hyperlink. To do so, you need to include the text you want displayed in brackets and then the URL in parentheses. For example:

![masked links](https://i.imgur.com/313wSx8.png)

If you don't wish to embed a link, you can wrap the link with `<>` to remove the embed for that specific link.

### Unordered Lists

<div class="tip-box">
<strong>Note:</strong> Don’t forget to add a space between the list bullet (<code>-</code>, <code>*</code>, <code>1.</code>, etc) and your text!</div>
<p>You can create a bulleted list using either (<code>-</code>) or (<code>*)</code> in the beginning of each line. For example:</p>

![unordered lists](https://i.imgur.com/v6pTIhe.png)

### Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list will always start with the first number. You can indent your list by adding a space before the number at the beginning of each line.

![ordered lists](https://i.imgur.com/yZ0bgbl.png)

## Code Blocks

Discord also supports code blocks as well.  You can make your own code blocks by wrapping your text in backticks (\`)

![one line code blocks](https://i.imgur.com/UNxqhiy.png)

You can also use three backticks (\`\`\`) to create multiline code blocks, like this beautifully written haiku.

![multiline code blocks](https://i.imgur.com/XvNIZ2b.png)

## Block Quotes

The syntax to use Block Quotes is > or >>> followed by a space.

**\>** at the beginning of a line of text, creates a single-line block quote.

![one line block quote](https://i.imgur.com/JJGECw1.png)

**\>\>\>** at the beginning of a line of text, creates a multi-line block quote. All text from `>>>` until the end of the message will be included in the quote.

![multiline block quote](https://i.imgur.com/TL1Tfu8.png)

## Spoiler Tags

You can manually tag spoilers by using the syntax `||` around your text or by typing `/spoiler` before your message. This is also negated by a code block.

![spoiler tags](https://i.imgur.com/rWhCqMc.png)

## Syntax Highlighting

If you really want to spruce up your code blocks, you can denote a specific language for **syntax highlighting**, by typing the name of the language you want the code block to expect right after the first three backticks beginning your code block. An example...

![syntax highlighting](https://i.imgur.com/cT1lDcy.png)

There are many different languages in place of Markdown that Discord's syntax highlighting support. Each different language has its own approach to highlight-able syntax. Note that you won't be able to view syntax highlighting on the mobile app.

asciidoc

![asciidoc](https://i.imgur.com/jT1UHko.png)

autohotkey

![autohotkey](https://i.imgur.com/TKEKFok.png)

bash

![bash](https://i.imgur.com/sMlKwsf.png)

coffeescript

![coffeescript](https://i.imgur.com/nuqQSjY.png)

cpp (C++)

![cpp](https://i.imgur.com/wwrzgrQ.png)

cs (C#)

![cs](https://i.imgur.com/6skWo5z.png)

css

![css](https://i.imgur.com/Nr7DsZA.png)

diff

![diff](https://i.imgur.com/JfoaZ63.png)

fix

![fix](https://i.imgur.com/v3Qw5tC.png)

glsl

![glsl](https://i.imgur.com/AdUfLEM.png)

ini

![ini](https://i.imgur.com/Pd8sbyQ.png)

json

![json](https://i.imgur.com/Jkuipkp.png)

md (markdown)

![md](https://i.imgur.com/wLunJuH.png)

ml

![ml](https://i.imgur.com/BQFfCnj.png)

prolog

![prolog](https://i.imgur.com/K3UyAdH.png)

ps

![ps](https://i.imgur.com/XmKiby8.png)

py

![py](https://i.imgur.com/G81EjVL.png)

tex

![tex](https://i.imgur.com/rxL4JoI.png)

xl

![xl](https://i.imgur.com/fGSFsKN.png)

xml

![xml](https://i.imgur.com/UELn5Un.png)

yaml

![yaml](https://i.imgur.com/aT0Nmjy.png)

And you get the idea! Now you're a **Discord text markdown expert**. Get out there and highlight your statements!
