Lappeenrannan teknillinen yliopisto

Software Development Skills Front-End, Online course

Teemu Hakoniemi, 001481880

# Learning diary

Here is my learning diary for this course. Diary consist of 7 modules:

1. Introduction and Base HTML
2. Links and Core CSS
3. Buttons & Utility Classes
4. CSS Grid & Cards
5. FAQ elements
6. Mobile Menu & Responsiveness
7. Website Deployment

and also diary about the project task.

# Introduction and Base HTML

**28/08/2026**

Started already with the course as I got some time before other courses start next week. Read through the course information and the target of the course is quite clear to me. Even though I've coded quite a lot through my studies, I haven't used GitHub before so making my first repository was the task number one. Video in Moodle 'Environment Setup' was quite old and didn't introduce VSCode (which I think is used more than Atom, might want to change the video to a newer Traversy Media one). Found a great video from Coder Coder and got my Git to work!

**01/10/2026**

Been a while. Other courses took a quite lot of time and kind of forgot about this one. Now caught up with the other ones so I have time to focus on this one.

First part of the saas-website done (00:00 -> 19:20). Video went by quite fast but by pausing it time by time I managed to do everything. Learnt about the shortcut where you can write for example div.menu and it comes as <div class="menu">

# Links and Core CSS

**02/10/2026**

In this task I learned several CSS techniques that were new to me, even though I already knew the basic idea behind the CSS from earlier courses. One useful thing was the CSS reset, where margin and padding were set to zero for all elements and `box-sizing: border-box` was used.

I also learned more about using container classes. A container can have a maximum width and be centered with `margin: 0 auto`, which prevents the content from stretching across the whole screen on large displays. It was also interesting to see that different container sizes can be created and reused in different parts of the website.

The biggest new topic for me was Flexbox. I kind of understood the basic idea before, but this example made it clearer. The navbar container was given `display: flex`, and `justify-content: space-between` was used to move the logo and navigation menu to opposite sides. `align-items: center` was then used to align them vertically. The menu itself was also made into a flex container so that the links appeared next to each other instead of vertically.

Another useful thing I learned was how CSS variables work. Instead of writing the same color value many times, a color can be saved as a custom property inside `:root` and then reused with `var()`. This seems especially useful on larger websites because changing one variable can update the same color everywhere it is used.

All in all this section helped me understand how CSS can be organized in a more reusable and structured way instead of only styling individual elements separately.
