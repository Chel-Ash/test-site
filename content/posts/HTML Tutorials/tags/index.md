---
title: "Introduction to HTML Tags"
<!-- date: 2021-02-01T06:00:23+06:00 -->
description: Simply by writng html tags in the correct format, you can display almost anything you want over a webpage. The format to write tags is painfully simple, and now you are gonna learn more about this and how to familarise yourself in writing tags to solidify your practice with them.
hero: getting-started/hero.jpg
menu:
  sidebar:
    name: HTML Tags - Introduction to Tags
    identifier: c
    parent: HTML-Tutorials
    weight: 30
author:
  name: Chelsea Koby
  image: /images/chel.png
math: true
---

### What are HTML Tags
HTML are the building blocks of the web. It is the most basic way to write content that can be loaded by web browsers and served over the internet. For this to happen, HTML has a simple syntax of building the structure of webpages and this is called **Tags**.


Simply by writng tags in the correct format, you can display almost anything you want over a webpage. The format to write tags is painfully simple, at least it was for me 😌, and now you are gonna learn more about this and how to familarise yourself in writing tags to solidify your practice with them.

### Details about HTML Tags
There are rougly 30 - 50 HTMl tags, and while you don't need to know or **use** all of them, it is immensely helpful to know what they are and can doo at the very leaset. Another approach is to have a reference list of notes which you can consult on a regular basis. A website also works. The whole idea about HTML Tags is this : You only need about 20% to do 85% of the work. The reason is that HTML is a very flexible language, you can make things work without following the normal **standard**. As you become more advanced, you would be more naturally inclined to follow standards to obtain the most useful and clean codes. Now onto Tags themself;


### Common HTML Tags
In this section, you are going to learn some common html tags, how they are wriiten, how they are used, and finally, steps on how to start practising.



#### Body Tag - 
* Denotatation: 	<mark>`<body></body>`</mark>
* Location: Placed Inside Html tag `<html></html>`
* Usage: Let's you Display content on the web page and encloses other tags like paragraph tag.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			An Empty Body Tag will display Nothing
			<p>I would show because I'm inside body 🙄</p>
		</body>
		</html>
		{{< /highlight >}}

#### Paragraph Tag - 
* Denotatation: 	<mark>`<p></p>`</mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you create a new paragraph
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<p>Paragraph Tag for Creating new paragraphs!</p>
		</body>
		</html>
		{{< /highlight >}}

#### Heading Tag(s) -
* Denotatation: 	<mark>`<h1></h1>`,`<h2></h2>`,`<h3></h3>`,`<h4></h4>`,`<h5></h5>`,`<h6></h6>`, </mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you create a Heading (Large Bold Text than paragraph). there are **six** Heading tags ranging from the largest to smallest. `<h1>` being largest & `<h6>` being smallest.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<h1>I am soo Huge</h1>
			<h2>I am considerably big</h2>
			<h3>I am also fairly big</h3>
			<h4>I am somewhat medium</h4>
			<h5>I am on the road to small</h5>
			<h6>I am really tiny</h6>
		</body>
		</html>
		{{< /highlight >}}


#### Bold Tag -
* Denotatation: 	<mark>`<b></b>` or `<strong></strong>`</mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you make a text bold to showcase importance. You can use either the `<b>` or `<strong>` tag to make text bold. The `<strong>` tag is the newer standard way of doing so.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<b>I make stuffs bold</b>
			<strong>I also make stuffs bold!. Are we buddies?</strong>
		</body>
		</html>
		{{< /highlight >}}

#### Italics Tag -
* Denotatation: 	<mark>`<i></i>`</mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you mark a text in the italics font style. i.e slightly bent to the right side.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<i>I would bend you and teach you resilience 😎</i>
		</body>
		</html>
		{{< /highlight >}}

#### Underline Tag -
* Denotatation: 	<mark>`<u></u>`</mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you mark a text underlined.i.e with a stroke of line underneath it.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<u>Uhhh, sure I would give you a line under? 😴</u>
		</body>
		</html>
		{{< /highlight >}}

#### Div Tag -
* Denotatation: 	<mark>`<div></div>`</mark>
* Location: Placed Inside Body tag <body></body>
* Usage: Let's you add a surrounding box around an element with a defined width and height.
* E.g: {{< highlight html >}}
		<!DOCTYPE html>
		<html>
		<head>
		  <meta charset="UTF-8">
		  <title>Example HTML5 Document</title>
		</head>
		<body>
			<div>I am officially the most used html tag. 😌</div>
		</body>
		</html>
		{{< /highlight >}}




And that's it for common tags!. Wait, but I mentioned rougly 30 if you remember. Well, that's because I decided to break down the tags in different sections of where they belong best. In the next few pages, you are gonna learn about **Advanced HTML Tags** and **Self-Closing Tags** and **Semantic Tags**. But before that, you need to practise what you just learnt, and what better way to do so than by writing codes and visualising it yourself. 



### Exercise for this Chapter

The simple exercise for you is to:
* Create an html file with the following in it: A title tag, body tag, paragraph tag, italics tag, bold tag etc (common tags). I strongly advise you write them down urself and not to copy it from online sources, that way it sticks faster.


Now how do you go about this, very simple:
* Download any text - editor softwares where you can write your code. If you are on a PC, i recommend any of the following:
	1. Sublime Text: <a href="https://www.sublimetext.com/3">Here</a>
	2. Atom: <a href="https://atom.io/">Here</a>
	3. VS code: <a href="https://code.visualstudio.com/download">Here</a>

* And if you are on a mobile, you can get any of the foll:
	1. Spck Editor: <a href="https://play.google.com/store/apps/details?id=io.spck"></a>
	2. Sublime text Mobile: <a href="https://play.google.com/store/apps/details?id=com.csgroup.texteditor">Here</a>
	3. Decoder, Compiler IDE: <a href="https://play.google.com/store/apps/details?id=com.paprbit.dcoder">Here</a>


After you complete your code, create an account on <a href="https://codepen.io/">Codepen</a> and upload you code there, a simple copy and paste would do. Then, you can leave a comment below to tell me about your progress, and with the link if you decide. I wish you Luck!

<p style="font-size: 40; font-family: cursive;">By Chel Koby</p>,

<!-- <abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
 -->