to change the colors of the background you need to go to the static folder > css > then main.css

you'll see
body {
  font-family: "Roboto Condensed", Arial, sans-serif;
  background: #3cb371; 
  line-height: 1.5em;
  font-weight: 300;
  font-size: 16px;
  color: #666;   
}
	background: #3cb371;  I can add an image to the background by linking a .png file url here or changing the CSS hex color to a single solid color


/* Layout */
.main-layout {
  background: #e43975;
}
	under layout I was able to change the "background" color of the "foregorund" color of each page which typically contained the headers and additional content\

![[./Pasted image 20240522205324.png|Pasted image 20240522205324]]
FONT COLORS and EFFECTS

**(1), (10), (8), (7) located in main.css** 
	a, a:link, a:active {
	  text-decoration: none;
	  ==color: #000000;==
		changes the color for 
		 - CHRIS P
		 - Navigation links
		 - and the project tags  which is (7)
		 - 
**(2) main.css** 
under /* Left column */
	/* Left column */
	div.col-sm-3 {
	  margin-top: 100px;
	  font-size: 11px;
	  color: #8e9505;
	}
	div.col-sm-3 strong {
	  font-size: 16px;
	  color: #006eff;
	  font-weight: normal;
	}
	div.col-sm-3 div.profile-about {
	  margin-top: 10px;
	  ==color: #ffa8a8;==
	}
		changes the color for
		- The text right below the CHRIS P
		- 
**(3) & (6) & (13)**
	**==h1, h2, h3 {==**
  color: #0015ff;
  font-weight: normal;
}
		changes the color for 
			all values representing h1,h2,h3

**(4), (5), (9)**
	body {
  font-family: "Roboto Condensed", Arial, sans-serif;
  background: #e7c38c;
  line-height: 1.5em;
  font-weight: 300;
  font-size: 16px;
  color: #1a581c;
	  colors represent the
		  - Main font of foreground text
		  - "Tag" categories in "My Projects" page
		  - All dates
			  - Date under each project under my projects
			  - Date beside each listed blog post on the home page


**(11)**
	in main.css under /* Social Icons*/
	.social li a {
	  font-size: 16px;
	  ==**color: #00ff90;**==
	}
	.social li a:hover {
	  ==**color: #fb95f8;**==
	}
	represents the color of
		- the social media icons
		- also when hovered changes color 
- 

In procjets.css
**(12)**
	.tag-cloud.active {
  **==background: #ff0000;==**
	  creates a background of the currently selected tag category under myprojects page
	
(6)
	a.project-detail:hover h3 {
  **==color: #ffffff;==**
	  creates a hover effect when hovering over a h3 project header



