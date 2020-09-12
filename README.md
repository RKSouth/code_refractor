# code_refractor
<!--  2 hours ago
theres a section in the good read me example that says "At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out? If your project has a lot of features, consider adding a heading called "Features" and listing them here." -->
### The goal of this project was to make the code more concise, semmantically correct and usable for search engine optimization. I did this to better understand what good code looks and feels like, to work on developing strong habits of commenting, commiting, and continous improvement. Making code smaller, easier to read and more agile for the user is what turns smart men into rich men-and me into a better observer and practioner of creating well, written and optimized code. Knowing that it needs to happen is not enough, practicing is the only way. 
## Features 


 1. Converted all HTML elements into semantic terms
    Why?
        I did this to not only make my code more concise in general but to make it easier to read for search engine optimization and for anyone else that might want to read/edit it in the future. There were plenty of instances where it was not clear whether you were looking at a header or a footer or a section within a section. Adding labels to the outer sections (such as article, aside, header and footer) made it easier to see where you were in the code and when making changes, easier to avoid mistakes.
    What?/How?
        In order to understand what I was initially looking out, I started from the CSS first and combined all the duplicate classes. ".benefit-brand img", ".benefit-lead img" and ".benet-cost img" all contained the exact same thing and therefore could be put onto 1 block of code with the 3 lables. I did this for all duplicate blocks. 

        Then I went to the HTML code. I opened it up both in my IDE and in my browser and examined it. I also opened the w3 schools page on [Semantic HTML] https://www.w3schools.com/html/html5_semantic_elements.asp).
        I systamitically went from the outer edge in, removing <div class="benefits> and replacing it with "aside" then moving to the CSS and changing it there as well; saving and checking routinely as I went. 

        Finally I removed the inner sections, determining which <div>'s needed to stay and which to go, all inner divs were replaced with "sections" which, with only few exceptions no longer needed the "." to indicate a class.

2. Re-ordered the elements to follow a logical structure (HTML)
    Why?

    Because it is plain unnaceptable to have code floating around willy-nilly with no reasonable home. You wouldn't write a book with the words randomly scattered about the page and expect people to know where your story is going or that there is even a story, so you shouldn't do that with code either.

    What?/How?

    Most of the disorder in this code was in the CSS versus in the HTML. For instance, the paragraph tag, "p" was found floating amongst the header stuff- since there were no paragraphs actually in the heard I put it in place with the rest of the article section. For the most part, I wasn't 100% sure what constituted professional logical order but, I did follow my own idea which was to put everything in the order of their importance of the page and in which they appear. 
3. Added alt attributes to all image elements so that they meet accessibility standards
    Why?
    Two reasons: Just in case the image does not show up and to make the page usable and understandable even if the user cannot see the image. 

    To elaborate-sometimes images move, disapear or are just unnaccesable. Having an alt tag is a super easy way to make it clear what you are trying to convey even though the image isn't showing up. Moreoever, sometimes people cannot see the image whether they are blind or they are still working on a windows 95 computer on a dial up network. It's a fairly simple thing to make sure your website, the face you put to the world to sell your company, is easy and accessable to as many people as possible.

    What?/How?

    By finding this code:
    <img src="./assets/images/lead-generation.png" /> and turning it into this:
    <img src="./assets/images/lead-generation.png" alt="gears going down into money" />
     Notice what added: 
     alt="gears going down into money"
    
    A simply alt= with a good description in quoatation marks, it doesn't need to be long and detailed as long as the core of the image is described. 
    
4. Re-ordered heading attributes so they follow in sequential order

    Why?

    For the same reason we ordered everything else in a logical fashion, having code willy-nilly all over the place is unacceptable.

    What?/How?

    I mostly did this when I was thinking about logical order but to elaborate- I copied it using ctrl+c, hit backspace and then pasted it where it really belonged; in numeracil order 1-6.

5. Gave the website a concise, descriptive title
    Why?

    Because if you are like me, you enjoy a lot of tabs. The more tabs you have open the more thoughts you can have in your brain, the more quickly you can access all the wonderful information the world wide web has to offer. But unless that tab has a very good title, you will end up clicking on it without meaning to and if you are tired and in a hurry you will be more likely to get mad at the company who doesn't think to label and title their website appropriately. We don't want your company to be cursed before someone has even done business with you, having a good title is easy enough and assures that you put your best face forward to the world. 

    What?/How?

    Generally, the name of the company is a good enough descriptor for a website, especially if it is a home page and not some subsection. A short description can be usefull in specific instances but generally, I like to keep things as simple as I can.
## Table of Contents

* [TechnologiesUsed](TechnologiesUsed)
* [Usage](Usage)
* [Credits](Credits)
* [License](License)

## TechnologiesUsed
* HTML 
* CSS

## Usage
### How do you use this project? You may use it nearly anyway you see fit however, if you feel lost, scared and alone; I have some suggestions for you. 
 1. You may admire it, sit back and take in the beauty. Peruse through the code. Enjoy it as if it were an old coletrain record, Bach or Monet. So, I might not be quite there yet but not every note written by Bach was divined, Coletain didn't start out great and in the beginning Monet's art looked like everyone elses at the time.
 2. You can judge it. You can critisize and even give useful feedback. How can I improve? Do you know how to write code as beautiful as Monet paints- I want to know your secrets.
 3. You can x out. You came here by accident and only realized right now you weren't suppose to be here. So, it's cool. Have a good night. 

 ## Credits

I would like to thank Kerwin, Jerome and all my classmates for helping and anyone that contributed to make the base code.

## License

MIT License

Copyright (c) [2020] [Rachael Kelm-Southworth]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


