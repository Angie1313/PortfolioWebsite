Creating your professional portfolio within a CSS Framework

We are going to start the process of creating your professional online portfolio. An online portfolio is a website you create to show off your skills, experience, projects, and even your personality to potential clients and/or employers. 

Some benefits to building your own portfolio website include:

Increased visibility, credibility and authority
When someone searches your name in Google, your tech portfolio website appears at the top
Hiring managers and clients can find you, instead of you trying to find them 
Gives you a chance to show off your creativity and personality
Shows that you’re a professional, which means employers and clients are more likely to trust you and your work

Here are some examples of portfolios.

You will be building your portfolio within Visual Studio Code and eventually going live with it.

 Define the page as an HTML5 document using doctype.
 Use the meta tag to define the character set to be UTF-8.
A viewport meta tag should make the website work on all devices and screen resolutions.  *Don’t worry about not knowing what this means yet.

Copy this code and put it right below the meta tag:
<meta name="viewport" content="width=device-width, initial-scale=1">


Make sure to include head tags
Create an external stylesheet link
Insert the <body> element in the appropriate spot.
Next create a navigation bar using the <nav> tag that includes a:
Home link
About me link
My Work Link
Contact link
Use ids to bookmark the links so the user can click on the link and navigate to it
Include an image of yourself in an appropriate space
Use alternative text 
Use <div> tags to separate the four sections(home, my work, about, contact)
Specifically create three class selectors and assign them each to the corresponding div(one for about me and one for contact).
Use “.about” for the about me content
Use “.work” for the my work content
Use “.contact” for the contact content
Create a paragraph tag within the about div, write a paragraph about yourself within the tag(look at some of the examples
Within the “my work” content you will create additional links to your
Github profile and
Linkedin profile
Create a paragraph tag within the contact div, put in your contact information within the tag(look at some of the examples
Use CSS Grids for displaying thumbnails for your highlighted projects(your best 3-4 projects), making it responsive
you can use placeholders for where your future projects will go
Within the same div tag create a form for someone to contact you by using just html
The form should look like this when you are done.  Review Codecademy’s html form lessons to create the form needed.


Style your form in any way you want with some CSS
Add a footer
Center the footer with CSS
Make sure to organize the code within the appropriate files
	
# PortfolioWebsite
