# Welcome to Jenny's Portfolio

I created this portfolio using **HTML**, **CSS** and a little bit of **JS**. I started by creating the basic **HTML** structure for all pages, then proceeded to create all of the content before proceeding to **CSS**. I find the work flow more clean and consistent when I start with the "foundation". From there, I make sure my **HTML** is semantically correct, and I proceed to styling with **CSS**.

I used **CSS** to give the website the colours, layout, fonts, and responsive design that you see. The website is optimized for mobile, tablet and desktop screens, with responsive fonts and images as well. 

I used **JS** to create the hamburger menu for the tablet/mobile navigation. I started off with this code: 

            function myFunction() {
              var x = document.getElementById("myLinks");
              if (x.style.display === "block") {
                x.style.visibility = "hidden";
              } else {
                x.style.display = "block";
              }
            }

            which I found at: https://www.w3schools.com/howto/howto_js_mobile_navbar.asp 

The issues I faced with this were that I could not get the hamburger menu items to appear when in tablet/mobile. I had to remove the styles and replace them with adding/removing classes. This allowed for the items not to be hidden from display (which was my issue) and rather, add/remove the classes as needed depending on what we want to see in which state. This is the optimized code: 

                function myFunction() {
                    var x = document.getElementById("myLinks");
                    if(x.classList.contains('show')){
                    x.classList.remove('show');
                    }else{
                    x.classList.add('show');
                    }
                }

I then added this code to it's own **JS** file and folder, rather than having it in the **HTML** and linked it accordingly.

Creating code is *always* a learning process for me, which I was reminded of during this project. Whether that means slowing down or stepping away for a moment to see clearly, or spending an entire day trying to fix what I broke. It is **SO** important to be organized, consistent and focused with this work. Maintaining best practices such as correct folder/file names, using correct syntax, creating adaptive/responsive designs and layouts, meeting accessibility standards, and practicing often are key. I've learned that I am passionate about creating websites, and I can not wait to keep expanding my knowledge. 


## Resources
- JS Library
- Unsplash
- W3 Schools
- Stackoverflow
- IMDAC
- Markdown Guide
- Lottie
- W3 Docs
- CodePen