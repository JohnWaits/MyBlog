# Coding Etiquette

Today I'm going to write about methods to make other developers hate you less!  
Unless you write in machine code, the langages you use are high level, simplified to make it easier for humans to write and read them.

![machine code](http://i.imgur.com/X8Bojtu.png)

(This is machine code.)

So when you write code, you have to think about the target of it: the future you, and the other people who may have to read and edit it.
You can write in many different ways that would end up being and working the same for the computer, so make sure it is understandable for humans, always.

> “Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live.”
> ― John Woods

## Code Comments
  * Code without comments is suboptimal.
  * Too many comments (one per line, for example) is probably a sign of poorly written code.
  * Comments should explain why, not what. They can optionally explain how if that's particularly confusing.
  
You should try to be as expressive as possible using clever variable names, and clear synthax, before commenting.
> "Whenever you think, “This code needs a comment” follow that thought with, “How could I modify the code so its purpose is obvious?” 
>Talk with your code, not your comments."
> ― improvingsoftware.com

There are two different ways to comment on code:

```javascript
  // This is a single-line comment, used on top, or at the end of a line

  /* This is a multiline comment, 
       if you have to write several lines of explanation, 
	   that can also be used in the middle of a line. */
```


## Style Guidelines
Following some style guidelines makes your code easier to read, if you're in a team, follow the same rules together, define the bracket placement, how you use spaces, 
lines lenghts and so on, to avoid this kind of things:
```javascript
$.getJSON(someURL, function(data){$("button").on("click", function(){if(foo.html() == bar){foo.html(baz);}else{foo.html(bar);}}
```
To make it easier, people use what is called a linter, it parses your code, looking for errors and enforcing the predefined coding style.
Increasing the overall readability, quality and homogeneity of your work.
You really should add one to your editor now.
I've been recommended ESLint with the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).

I hope you enjoyed this article, and that I convinced you to think about writing beautiful readable code, and using a linter if you were not already!
Do you have any other recommendations to improve this post, or any advice?  
Feel free to contact me.


_*sources:_  
[https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md#code-comments](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md#code-comments)  
[https://improvingsoftware.com/2011/06/27/5-best-practices-for-commenting-your-code](https://improvingsoftware.com/2011/06/27/5-best-practices-for-commenting-your-code/)  
[https://medium.freecodecamp.org/grabs-front-end-guide-for-large-teams-484d4033cc41](https://medium.freecodecamp.org/grabs-front-end-guide-for-large-teams-484d4033cc41)  
