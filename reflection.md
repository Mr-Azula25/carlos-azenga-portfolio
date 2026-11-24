# ICS 2216 Lab 2 — Reflection
**Student:** Carlos Azenga  
**Programme:** BSc Environmental Science  
**Institution:** JKUAT

1. **What happens when someone types my website address into their phone?**  
The phone's browser acts as the client and begins by asking DNS to find the IP address linked to the website's domain name. DNS returns the address of the server hosting the site. The browser then uses HTTPS to make an encrypted connection to that server and requests the website files. The server sends back the HTML, CSS and images, and the browser puts them together to display the pages.

2. **What is the difference between a static and a dynamic website?**  
A static website displays content stored in its files, so the same page is normally shown until someone edits the files. A dynamic website can retrieve information from a database and build a page using the latest stored records. In my portfolio, the Top 5 Movies page is static because the movie details are written directly in the HTML. In a dynamic version, the page could read the movie titles and rankings from the movie table.

3. **Why use a separate CSS file?**  
A separate CSS file keeps the design rules away from the main page content. I can use one stylesheet to control colours, fonts, spacing and layout across all five pages. This makes the website look consistent and saves time when I want to change the design. It also makes the HTML easier to read and maintain.

4. **Which accessibility or responsive design choices did I make?**  
I added descriptive alternative text to images so that visitors using screen readers can understand what the images show. I used clear headings, readable text and a consistent navigation menu to make the pages easier to follow. The viewport setting, flexible layout and responsive grid help the pages fit smaller phone screens. These choices make the website easier to use for people with different devices and needs.

5. **Which field is a primary key and which is a foreign key?**  
The profile table uses profile_id as its primary key because it uniquely identifies each profile record. In the skill, hobby, movie and enquiry tables, each table has its own primary key, such as skill_id or movie_id. Those tables also use profile_id as a foreign key to connect each record to the correct profile. The keys help prevent confusion and maintain relationships between the tables.

6. **Which personal information did I choose not to publish, and why?**  
I chose not to publish my home address, personal phone number or identification details. These details are private and are not necessary for someone viewing an academic portfolio. I also left social media profile links out until I can check which accounts I am comfortable sharing publicly. This helps protect my privacy and reduces the risk of misuse of personal information.
