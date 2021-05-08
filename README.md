# Milestone Project One: Samurai
This is my 1st milestone project for my Code Institute Diploma in Software Development. 
The aim for this right now is to create a static site promoting a band called **Samurai**.
The band is from the game **Cyberpunk 2077** by the developers *CD Projekt Red*, and the site is largely designed around the band's theme which is black, red and white.
## UX
### User Stories:
* I am an avid listener of **Samurai**, I'm looking for tour dates so that I can go to one of their shows.
* I have heard about the band **Samurai** and have heard some of their music, but am looking to learn more about the band itself.
* I have never heard a **Samurai** song before, I am looking to listen to one of their songs to get a feel for their music.
* I am an employee of a record label, I am looking for a contact page so that we can talk about signing them to our label.
### Design
* I created a wireframe of my website made in Balsamiq Wireframes before starting it, providing a rough guideline to follow. I only created the desktop design as a wireframe because of time constraints but in hindsight, creating the other responsive designs in advance would have sped up the development process. This can be found as a pdf file in the directory "assets" and is named "Milestone Project 1 Wireframe (Samurai).pdf".
* The main colour theme for the band Samurai is red, black and white. I also added some yellow in there because of the game that the band is from, "Cyberpunk 2077".
## Features
### Existing Features:
The first feature is the header which includes the logo for my band and a navigation bar to navigate through my pages easily. 
![Website Header](https://github.com/Harbs1999/MS1-Samurai/blob/master/assets/README-images/navbar-screenshot.png "nav bar")

The next feature is the hero image, here I have chosen one of Samurai's album covers and some cover text with a button telling the user to buy the album.
![Website Hero Image](hero-image-screenshot.png "hero image")

This screenshot includes 2 features. The top feature is a music player, this plays a song by Samurai to give the user a sample of their music, perhaps gaining new fans this way.
![Website Song Player and About the Band](song-n-abtme-screenshot.png "Website Song Player and About the Band")

This is the footer feature, it includes 4 icons linking to band social media.
![Website Footer](footer-screenshot.png "footer")

This feature is shows. It shows tour dates and where they will be taking place. It also has a button at the bottom to buy tickets to the show.
![Website Tour Dates](shows-screenshot.png "Shows")

This feature gives fans information about the band members, this gives people a reason to become more invested in the band.
![Website Bio](meet-the-band-screenshot.png "Meet the Band")

This feature gives people a way to get in touch with the band. People give the reason they're contacting the band and they give an email so that the band can contact them back.
![Website Contact Us](contact-us-screenshot.png "Contact Page")
### Features Left to Implement:
* A feature that would be a nice implementation would be a forum for fans to interact and engage on specific topics such as different songs and genres.
* Another feature that will be added will be a gallery to show different photos and videos from tours and music videos. Some behind the scenes are a good way to engage fans.
* An extra feature that will be added will be a map to go along with the locations on the shows page, this would be helpful for fans to find how close the shows are.
## Technologies Used
* Bootstrap
* FontAwesome
## Testing
* Had an animation for both the logo and the hero image but found there was too much happening on the screen at once so changed to just the hero image. I also got a 2nd opinion on this to ensure it wasn't just bias.
* Bio page had a horizontal scroll bar so I added "overflow: hidden" to the section class.
* There were 2 instances of contrast issues that I changed because writing was hard to read. The first was the cover text on the hero image and the other was the contact us form. Both had dark grey, semi-transparent backgrounds with white text, so I changed them to white backgrounds with black text which still kept in line with the theme.
* There were 2 images in the "About The Band" section, all positioned diagonally but it was all to close and it did not translate to mobile. So instead I used bootstrap and had 1 image on the left and the about me writing on the right.
* I tested all links on the page and they all worked.
* I also tested the form, I tried to submit without typing anything in an input field to ensure all of the required attributes work.
## Credits
### Content
* The icons in the footer were taken from [Font Awesome](https://fontawesome.com/).
### Media
* Logo taken from [Logo](https://www.google.co.uk/url?sa=i&url=https%3A%2F%2Fwww.pngitem.com%2Fmiddle%2FiiJwiT_cyberpunk-2077-samurai-sticker-hd-png-download%2F&psig=AOvVaw0VuRyr9oDaxHLsE4ltRuH6&ust=1620535882151000&source=images&cd=vfe&ved=2ahUKEwjPqYrepLnwAhV5EGMBHdh0AnwQjhx6BAgAEBI)
* Image of Johnny Silverhand [Johnny](https://cyberpunk2077.wiki.fextralife.com/file/Cyberpunk-2077/johnny-silverhand-npc-cyberpunk-2077-wiki-guide.png)
* Image of Kerry Eurodyne [Kerry](https://cyberpunk2077.wiki.fextralife.com/file/Cyberpunk-2077/kerry-eurodyne-npc-cyberpunk-2077-wiki-guide.png)
* Image of Nancy [Nancy](https://cyberpunk.fandom.com/wiki/Bes_Isis?file=Char_Profile_besisis.png)
* Image of Henry [Henry](https://cyberpunk.fandom.com/wiki/Henry?file=Char_Profile_henry.png)
* Image of Denny [Denny](https://cyberpunk.fandom.com/wiki/Samurai?file=Char_Profile_denny.png)
* Music Player [Chippin In](https://open.spotify.com/track/0UHxkkgI5GfV0XBRA1rqfe)
### Acknowledgments
* I used the videos from the Love Running project from Code Institute
* I used the template for a README.md given by Code Institute.
* The band is fictional and is from the game Cyberpunk 2077/Cyberpunk 2020, and the music made from them are performed by the band "Refused".
