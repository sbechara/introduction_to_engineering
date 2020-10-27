# MECH 103 Book Formatting Guide

This guide will give you the conventions that we will use to make sure that we are being consistent with formatting.

In general. To create paragraphs, use a blank line to separate one or more lines of text. Always keep a blank line above and below headings.

# Chapter Number - Chapter Title

Use heading level one for chapter titles as above. Use level two and level three subheadings as I do in the book.

## Level two heading

Words words words.

### Level three heading

More words.

## Questions

For the questions in the book, use blockquotes like this:

> Discussion 2.1: What is your story?
>
> This post is not anonymous. The professor and participants can see the responses and the author. I am certain that a lot of you have a personal story of how a connection that you had helped you get a job, get some paperwork through, fast tracked you through customs, etc. Take a moment to talk to someone that you know is a professional and ask them if they have a story where "it's not what you know, it is who you know" has helped them in life (also make sure they are comfortable with you sharing this info). This can be a professor, a parent, a grandparent, a friend, or anyone who is in a career. Please share with your classmates the story that you heard. If you have a personal and compelling story, you can use that instead.
> Notice how you can have a multi-line block quote by just putting the little alligator thing to start each line.

## Code Examples

For code examples, use the following syntax with three quotes then the word MATLAB in all caps. This is nice because it automatically formats it when coverted.

```MATLAB
x = linspace(1,8,8);
y = x.^2;
plot(x,y,'r^');
```

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
