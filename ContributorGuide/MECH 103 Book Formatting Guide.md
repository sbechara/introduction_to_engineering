# MECH 103 Book Formatting Guide

This guide will give you the conventions that we will use to make sure that we are being consistent with formatting.

In general. To create paragraphs, use a blank line to separate one or more lines of text. Always keep a blank line above and below headings.

# Chapter Number - Chapter Title

Use heading level one for chapter titles as above. Use level two and level three subheadings as I do in the book.

## Level two heading

Here is a link to a markdown cheat sheet. It also shows you how to create links in markdown. [This is the link text in square brackets](https://www.markdownguide.org/cheat-sheet)

### Level three heading

More words.

## Questions, Discussions, and End of Chapter Items

For the questions and discussions in the book, use blockquotes like this with a bolded title:
###Discussions
> **Discussion X.X: What is your story**?
>
>> This post is not anonymous. The professor and participants can see the responses and the author. 

>I am certain that a lot of you have a personal story of how a connection that you had helped you get a job, get some paperwork through, fast tracked you through customs, etc. Take a moment to talk to someone that you know is a professional and ask them if they have a story where "it's not what you know, it is who you know" has helped them in life (also make sure they are comfortable with you sharing this info). This can be a professor, a parent, a grandparent, a friend, or anyone who is in a career. Please share with your classmates the story that you heard. If you have a personal and compelling story, you can use that instead.
>
> Notice how you can have a multi-line block quote by just putting the little alligator thing to start each line. Also, notice how the disclaimer is indented with a second alligator thing. This same formatting for indenting can be used for multiple options on multiple choice problems. See below.

### Questions
>**Question X.X: Units of \\({k}\\)**

> Based on Hooke's Law and using dimensional analysis, what should the SI units of \\({k}\\) be? (Let \\({F}\\) have units of Newtons, and \\({x}\\) have units of meters). 
>>(A) \\( M \\) 
>>(B) \\( m/N \\) 
>>(C) \\( N*m \\) 
>>(D) \\( N \\) 
>>(E) \\( N/m \\)

### End of Chapter Items
>**Personal Reflection - Chapter X**
>>This is a completely anonymous submission. The professor will be able to see the responses but the responses will not be attributed to an author. Your participation is required.

>What do you think about the content of this chapter? This was the last chapter in which we will cover Excel. Did you learn anything new? Do you need to do some more practice? Do some personal reflection.

>**Request for Feedback - Chapter X**

>>This is a completely anonymous submission. The professor will be able to see the responses but the responses will not be attributed to an author. Your participation is required.

>What did you think of this chapter? Does anything stand out as exceptionally good? Anything that you would like to see differently? Any feedback is appreciated.

## Code Examples

For code examples, use the following syntax with three quotes then the word MATLAB in all caps. This is nice because it automatically formats it when coverted.

```MATLAB
x = linspace(1,8,8);
y = x.^2;
plot(x,y,'r^');
```

I think almost all the code examples are on their own lines (three apostrophes). However, if you run accross an in-line code example you can do it like this `test=20;`.

## Pictures

To add pictures, first, make sure that they are downloaded by right clicking on the image and saving. Save it to the "media" folder associated with the chapter you are working on. The most basic form of a picture in markdown looks like this:

![alt text](image.jpg)

But, we need a way to display a figure caption. The little hack I came up with is putting both the figure, and the caption, in a table. Here is an example of how you should format an actual picture.

|![fig1.1](media/knight.jpg)|
|:---:|
|*Figure 1.1: You are all my knights in shining armor!*|


There are a few important notes about pictures...

1. Please note that there have been reports of some mistakes on the figures in the book. Please update them to make them correct. E.G. if it says Figure X, change it to Figure 12.5 or whatever it should be.
2. Note that the figure is just a table. Make sure to put *emphasis* or stars around the caption to make it italics.

## Videos

For embedded videos, just include the youtube links. Example:

[Video 2.1: TJ Duane, It's Who you Know](https://www.youtube.com/watch?v=NzpYBTeZdWw&feature=emb_title&ab_channel=StanfordGraduateSchoolofBusiness)

## Bulleted Lists

This is how you create bulleted lists.

- You can just use this notation.
- For bulleted lists.
- Easy right?

## Equations

For equations, you are going to have to use a little bit of latex formatting which might take a little practice. There are two types of latex equations. Either they are in-line like this: \\( {velocity} = {{dx}\over{dt}} \\)

Or they are on their own line like this:

\\( {a^2} = {b^2} + {c^2} \\)

Notice that you use the double backslash notation to start each one. They only difference is you use double-back-slash+paranthesis for one and double-back-slash+bracket for the other.

The only little trick with equations is figuring out latex formatting. The curly brackets you can think of as how to isolate little bits of math. So if you look at the velocity example above, notice, how I used curly brackets to make sure that the "over" function worked correctly.

[Here is a link to an online latex editor](https://latexeditor.lagrida.com/)

Now open up that link and try the following three lines in the latex editor to see what I am talking about. *Note: if I wanted to format these for the book I would have had to include the double-back-slash+paranthesis in front and after the equations.*

- \\(velocity = distance \over time\\)
- \\({velocity} = {distance \over time}\\)
- \\({velocity} = \frac{distance}{time}\\)

Notice that the first one doesn't work the way we wanted it to but the second two BOTH work. If you are not confident in your latex equation skills you can always access that online latex editor to see what your latex equations will look like before you put them in the book.

[Finally, here is a latex math cheat sheet you can reference](http://joshua.smcvt.edu/undergradmath/undergradmath.pdf)
