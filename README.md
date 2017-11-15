<!--Actually 10:06 to 10:17-->

<!--WDI4 11:30 to 11:40 -->

# Legacy Code Intro

## Objectives
*By the end of this lesson, developers will be able to:*

- **Understand** the various definitions of "legacy code" in the developer world
- **Describe** some ways to make working with "legacy code" easier

## What is legacy code?

Excellent question!  There are more opinions on the definition than there are letters in "legacy code".  Here are some of the major ones, with sources.  After you've been devloping for a year or two, you will probably develop your own opinion as well.

- Code is **legacy code** as soon as it's written.
  -[Unknown, possibly Pragmatic Programmer](http://stackoverflow.com/questions/4174867/what-is-the-definition-of-legacy-code) 
- **Legacy code** is code that gets inherited by a team or a programmer from somewhere else.
  -[Top Answer on Stackoverflow (Shaggy Frog)](http://stackoverflow.com/questions/4174867/what-is-the-definition-of-legacy-code)
- **Legacy code** is source code that relates to a no-longer supported or manufactured operating system or other computer technology. 
  -[Wikipedia](https://en.wikipedia.org/wiki/Legacy_code)
- **Legacy code** is code without tests.
  -[Michael Feathers](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)
- [Even More Opinions](http://softwareengineering.stackexchange.com/questions/94007/when-is-code-legacy)

## How do we tackle legacy code?

In a few minutes, we'll look at someone else's code.  Namely, you will look at code written by the instructor currently talking and his collaborator.  Try to keep the following pointers in mind as you work through this code:

1. Start Small
  - Target what you think you can accomplish, small bugs or errors in the console. Then graduate to bigger things as you understand more of the codebase.
2. Don't Judge
  - A real human wrote this code.  A human with good intentions.  Just as you are not your code, they are not their code either.  Focus on making the customer happy, and don't worry too much about "the mess you walked into".  It's hard, but it will really help.
3. Rely on Your Peers
  - Is that issue you're looking at actually an issue?  Or is it just different from what you're used to?  Second opinions are incredibly valuable when you walk into code you've never seen before.
4. Stick to Convention
  - Don't try to overhaul the directory structure, but as you proceed, stick to best practices whenever possible in terms of organization, OOP practices, and scalability.  That means you may want to check out our recommended style guides for [Angular](https://github.com/johnpapa/angular-styleguide), [JS](https://github.com/airbnb/javascript), and [HTML/CSS](https://google.github.io/styleguide/htmlcssguide.xml).
5. When in Doubt, Test Everything
  -Open Dev Tools **immediately**, and devise a way to verify every new line of code you write.  Ideally, this would mean a couple software tests, but at the least, show something in Dev Tools that proves your style or functionality has changed in the way you wanted it to.

## Resources

- [8 Strategies for Tackling Legacy Code](https://www.fastcompany.com/3029446/eight-strategies-for-tackling-legacy-code-you-didnt-write)
- [Book - *Working Effectively with Legacy Code*](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)
- [Adding Tests to Guide Legacy Code Work](http://softwareengineering.stackexchange.com/questions/122014/what-are-the-key-points-of-working-effectively-with-legacy-code)
- [7 Tips For Approaching Code You Didn't Write](https://www.vokal.io/labs/legacy-code-7-tips-for-approaching-code-you-didnt-write)
