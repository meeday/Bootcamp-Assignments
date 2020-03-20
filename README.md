# **Refactoring Horiseon Website**

Horiseon is a marketing agency providing social solution services. 
This application is a website that gives the reader information on solutions for optimizing your site for search engines. 
Navigating the website is easy as you use the navigation links at the top right of the web page,
which will re-direct you to the relevant information further down on the website:
[#search-engine-optimization]
[#online-reputation-management]
[#social-media-marketing]

This assignment required me to refactor the coding according to the criteria proposed. 
One of the criteria is that the source code uses semantic HTML tags. 
To meet these criteria:

* I changed the <div> tags into the tags:
  -<header>
  -<nav>
  -<img>
  -<main>
  -<section>
  -<aside>
  -<footer>
this is highlighted in **GREEN** in the HTML snapshots

* I added alt attributes to all the images: Shown in **RED** in the HTML snapshots

*	all the heading attributes fall in sequential order except for the heading found within the <footer> tags so I changed that to an <h4> tag
(shown in **GREEN** in the HTML snapshots).

*	I also added a concise and descriptive title based on what I understood from the contents of the website Shown in **YELLOW** in the HTML snapshot. 
I used the Optimal format provided on: https://moz.com/learn/seo/title-tag
      
**Primary Keyword - Secondary Keyword | Brand Name**

*	I found that the elements followed a logical structure independent of styling and positioning so I left the html as it was, 
However the CSS was longer than was necessary therefore I consolidated some styling in one line of code; 
there are comments on the CSS file that detail these changes. Also view the CSS snapshots

[Screenshot folder]:https://github.com/meeday/Bootcamp-Assignments/tree/master/Screenshots



