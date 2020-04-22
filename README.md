# HW 1- Code Refractor Solution Summary

1. The goal of this homework was to make this site more accessibility friendly.
First I went online and familiarized myself with semantic elements.

2. I started looking at my current code on my index.html and spotted all the divs listed in it.

3. I sectioned which parts I would tackle and in what order by going to the site and working on the site's flow, i.e. header first, main section with the company's services listed, next benefits on working with the company and lastly footer.

4. With the guidance of the semantics article I was able to change the divs on the header. At first I put the menus as articles but then I realized that those are the navs because after all they are on the nav bar. 

5. I was able to section my code and separate each article (company service).

6. Next I set the benefits of working with the company as aside because even though this part is not on the flow of the main content on the center of the page, it still relates to it. We want the company to be able to list its benefits but not overshadow its services.

7. On the footer I just madxe sure to replace the div with the footer, which is its true identity.

8. Next, I moved on to the CSS styles. Took me some time to familiarize myself with the classes and see which class belonged to which line on the html code.

9. At first when I loaded the site everything had moved (*panic mode*). Menu navs had become unordered lists and moved all way to the left, under the logo. The content had moved up and covered the cover photo of the webpage. 

10. I followed the original css and how it was written and I figured that I needed to add .header nav on the header css because I had substituted it on the html. Same with .header nav ul li.

11. I opened the html on the default browser and Voila! It worked.

12. I alos added notes along the html code and css styles to differentiate the sections.