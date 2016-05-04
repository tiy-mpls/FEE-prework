# Extra Curriculum

**Stop!** The following are advanced tasks that you can start on if you have time. I do not want you to start on these unless you've already completed all other pre-work.  If you do not have time to complete this, please do not worry. There will be plenty of time in class for us to work on these extra items. You are not expected to know this content now or ever. This is provided simply for students who wish to work on extra work now or during class.  Please approach the following with caution and expect to be overwhelmed. 

## Lunch'n'Learns

From time to time, we'll have students to pick a research topic to a greater depth, and share lessons-learned with the rest of the class on this subject, presentation style.

First, an interesting quote:

```
We Learn
10% of what we READ
20% of what we HEAR
30% of what we SEE
50% of what we SEE and HEAR
70% of what is DISCUSSED with OTHERS
80% of what is EXPERIENCED PERSONALLY
95% of what we TEACH TO SOMEONE ELSE

~ William Glasser
```

## Prepare the talk

- Use at least one, ideally all three, of the following techniques:
  - live coding
  - whiteboarding
  - interactive exercises

- Do research! Your instructor will be thrilled to hear you echo what they've taught in class, but you should be going beyond this for your presentation. Read blogs, tutorials, books, essays, and anything else you can get your hands on to get a broad and deep perspective on your topic. 
- **Learn more than you plan to present**, so that you can distill down your knowledge to its key points, and so that you can answer questions that your classmates might have for you after your talk. And don't just dump the information on us. Take us there. Tell us a story. 
- Make sure that the way you define your topic consists of accessible vocabulary. Don't use too many acronyms and difficult words without clearly explaining their importance and significance.

## Front-End Topics 

Some of these have been discussed in class, others have not. You're also more than welcome to come up with your own topic, as long as it's related to web development, and as long as you discuss it with your instructor beforehand. Hints and suggested are included with some topics, but by no means should your talk be limited to those subpoints. 

- IIFES
  - what they are and why we use them
  - how do they relate to functional scope. 
- .bind/.call/.apply
  - relation to “this”
- variadic behavior 
    - spread operator in es6
    - Array.prototype.slice.call(arguments)
- jQuery-fetch vs $.ajax vs $.getJSON
- jquery methods on DOM node objects
  - pros & cons vs vanilla js
- underscore methods 
  - _.bind() etc
  - relation to Array prototype methods
- .git explained
  - what is in the .git folder, what does it all mean, how does it relate to the git system at large?
  - HEAD?
  - config?
- http verbs 
  - PUT POST DELETE GET
- prototyping 
  - prototype chain lookup 
  - .__proto__ vs .prototype 
- a bonus library of your choice. some suggestions:
  - fartscroll
  - snapJS
  - moment.js
  - reveal.js
  - highcharts.js

# Blogging Topics

The following are topics you can prepare to blog about, during or after class. All great things to meditate on. The more you can share about your expertise on a blog, the greater your chacnes of being noticed and hired. The differences in hiring rate and frequency of those who blog and those who don't are **statistically significant and better for the bloggers**.

## CSS Blogging Topics

- read and reflect on Mary Rose Cook's "Intro to Practical Functional Programming" (http://maryrosecook.com/blog/post/a-practical-introduction-to-functional-programming)
- read, write examples of, make our own: ["Exploring Canvas Drawing Tachniques"](http://perfectionkills.com/exploring-canvas-drawing-techniques/)
- What is the difference between classes and ID's in CSS?
- Describe what a "reset" CSS file does and how it's useful.
- Describe Floats and how they work.
- Describe z-index and how stacking context is formed.
- What are the various clearing techniques and which is appropriate for what context?
- Explain CSS sprites, and how you would implement them on a page or site.
- What are your favourite image replacement techniques and which do you use when?
- CSS property hacks, conditionally included .css files, or... something else?
- How do you serve your pages for feature-constrained browsers?
- What techniques/processes do you use?
- What are the different ways to visually hide content (and make it available only for screen readers)?
- Have you ever used a grid system, and if so, what do you prefer?
- Have you used or implemented media queries or mobile specific layouts/CSS?
- Any familiarity with styling SVG?
- How do you optimize your webpages for print?
- What are some of the "gotchas" for writing efficient CSS?
- What are the advantages/disadvantages of using CSS preprocessors? (Sass, Compass, Stylus, LESS)
- If so, describe what you like and dislike about the CSS preprocessors you have used.
- How would you implement a web design comp that uses non-standard fonts?
- Explain how a browser determines what elements match a CSS selector.
- Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
- What does * { box-sizing: border-box; } do? What are its advantages?
- List as many values for the display property that you can remember.
- What's the difference between inline and inline-block?
- What's the difference between a relative, fixed, absolute and statically positioned element?
- The 'C' in CSS stands for Cascading. How is priority determined in assigning styles (a few examples)? How can you use this system to your advantage?
- What existing CSS frameworks have you used locally, or in production? (Bootstrap, PureCSS, Foundation etc.)
- If so, which ones? If you could, how would you change/improve them?
- Have you played around with the new CSS Flexbox or Grid specs?
- How is responsive design different from adaptive design?
- Have you ever worked with retina graphics? If so, when and what techniques did you use?

## JS Blogging Topics

- Explain event delegation
- Explain how this works in JavaScript
- Explain how prototypal inheritance works
- How do you go about testing your JavaScript?
- AMD vs. CommonJS?
- Explain why the following doesn't work as an IIFE: function foo(){ }();.
- What needs to be changed to properly make it an IIFE?
- What's the difference between a variable that is: null, undefined or undeclared?
- How would you go about checking for any of these states?
- What is a closure, and how/why would you use one?
- What's a typical use case for anonymous functions?
- How do you organize your code? (module pattern, classical inheritance?)
- What's the difference between host objects and native objects?
- Difference between: function Person(){}, var person = Person(), and var person = new Person()?
- What's the difference between .call and .apply?
- Explain Function.prototype.bind.
- When do you optimize your code?
- When would you use document.write()?
- What's the difference between feature detection, feature inference, and using the UA string
- Explain AJAX in as much detail as possible.
- Explain how JSONP works (and how it's not really AJAX).
- Have you ever used JavaScript templating?
- If so, what libraries have you used? (Mustache.js, Handlebars etc.)
- Explain "hoisting".
- Describe event bubbling.
- What's the difference between an "attribute" and a "property"?
- Why is extending built in JavaScript objects not a good idea?
- Difference between document load event and document ready event?
- What is the difference between == and ===?
- Explain the same-origin policy with regards to JavaScript.
- Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]`
- Why is it called a Ternary expression, what does the word "Ternary" indicate?
- What is "use strict";? what are the advantages and disadvantages to using it?
- Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
- Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
- Question: How would you make this work?

    ```js
    add(2, 5); // 7
    add(2)(5); // 7
    ```

- Question: Can you explain how `sum()` works?

    ```js
    function sum(head, rest){
        if(head instanceof Array){
            return sum(head[0], head.slice(1));
        }
        return (head || 0) + (rest.length ? sum(rest[0], rest.slice(1)) : 0);
    }

    sum(1) // 1
    sum([1, 2, 3, 4, 5]) // 15
    ```

- Question: Can you explain how `factorial()` works?

    ```js
    function factorial (n) {
        return n ? n * factorial(n - 1) : 1
    }
    ```
