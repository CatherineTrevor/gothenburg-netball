# Gothenburg Netball Club Project
## A simple website providing information about Gothenburg's Netball Club to existing and prospective players.

### [View the live site here.](https://catherinetrevor.github.io/gothenburg-netball/)

# Contents
1. Project Overview

2. UXD
- Strategy
    * Target audience
    * User stories

- Scope
    * Features 

- Structure
- Skeleton
- Surface

    * Typography
    * Imagery
    * Colour scheme
    * Favicon

3. Technologies used

4. Testing

5. Deployment

6. Credits

- Content
- Media
- Acknowledgements

# Project Overview

This project is my Milestone Project One as part of the Diploma in Software Development Course with the Code Institute.

I am on the committee for the Gothenburg Netball Club: a team of amateur netball players, set up for English-speaking adults in Gothenburg. 
Sadly due to the current Covid-19 situation having such a negative impact on sports, we have been unable to have routine sessions, and therefore 
do not have a group of regular players.

I am taking this opportunity to create a simple, clearly structured website to promote the club so that when we can start playing again in the 
spring, there is a larger awareness and interest in the club, encouraging site visitors to join a session and become paying members. It will also 
serve as a place that regular players can see upcoming training dates, times and locations. 

The club's current online presence is via [Facebook](https://www.facebook.com/gothenburgnetball/).
# User Experience Design (UXD)
## Strategy
The site has been designed using a mobile-first approach to ensure ease of obtaining information.

The look and feel must be friendly, local, and approachable: the objective is that people feel comfortable contacting 
the club and want to join us to play, even if just once. If the site feels too commercial, busy, or cold it will not provide this positive feeling to 
the user.

### Target audience
English-speaking adults (whether native or not), aged 18 or over, who wish to meet other people, whilst playing sport / improving their fitness. Site users are based 
in Gothenburg, Sweden, or can travel to the city regularly.

Users can have experience of netball, perhaps having played in school or college, or no experience at all. This is not a competitive environment: 
it is meant to be fun, therefore level of playing experience, or even knowledge of the game is immaterial. All are welcome and the site must reflect this.

Where users have knowledge of the game and/or are interested in volunteering, we invite them to join the committee and/or provide help in 
umpiring/coaching.

### User stories
#### I am an English-speaking adult in Gothenburg and want to:
- Meet other English-speaking adults regularly, and make new friends,
- Learn a new skill/sport,
- Improve my netball skills, a game I haven't played for years,
- Improve my fitness,
- Spend time with people that I have something in common with,
- Get out of the house,
- Have fun!

#### I am a new visitor to the site and want to:
- Easily understand what the club is and what it provides,
- Refresh my understanding of netball,
- Learn the basics of netball,
- Find out where and when practice is, 
- Understand the fees involved,
- Feel invited to join a session,
- Feel comfortable contacting someone for more information,
- Connect to the club's social media channels,
- Understand what I need to join,
- Understand what I will gain from coming to a session,
- Have an overview of the committee members.

#### I am a regular player / frequent site visitor and want to:
- Find out where and when practice is,
- Feel invited to join a session,
- Refresh my knowledge of netball,
- Find out the latest news about netball,
- Learn about future friendly matches and tours.

#### I am a club committee member and want to:
- Showcase how much fun we have as a club,
- Encourage regular playing members,
- Build a strong, regular team so that we can attend matches and tours as a group,
- Encourage people to try a new sport,
- Invite players to join the committee and help us run the club,
- Provide clear information about who we are and what we do for future sponsorship opportunities.

## Scope
### Features
Utilising the trade-off equation, below details the features I have selected to be included in the initial release, and ones to be considered 
in the future.

![Trade-off equation](assets/images/supporting-docs/trade-off-equation.jpg)

| --- | Importance | Feasibility |
| --- | :---: | :---: |
| 1. Increase number of paying members | 5 | 4 |
| 2. Increase attendees to trial sessions | 5 | 5 |
| 3. Offer digital sign-up and payment options to members | 2 | 2 |
| 4. Create sponsorship opportunities | 2 | 1 |
| 5. Build a basic online presence | 4 | 4 |

### Existing features

| Feature  | Details  |
|---|---|
| Nav bar | Simple, easy to understand navgation bar, always at the top of each page.  |
| Footer | Contact info, social media link (opening in new tab), membership form (opening in new tab) and organisation name and number.  |
| Images | Clean, real-life images of the players, venues and social occasions.  |
| About  | Basic, simple information about who we are and what we do.  |
| Guide to netball  | Basic principles of the sport, which are easy to comprehend, including visual representation.  |
| Contact page  | Easy to use contact form. Club contact information and committee member details.  |
| Practice dates | Clean presentation of the date, time and location of upcoming sessions.  |
| Current information  | Covid-19 safe guidelines, future tours, national netball information.  |
| Favicon  | A constant reminder to the site user of the site they are on.  |
| What is needed to play | Checklist and fee information. |

### Future features planned

Once play resumes, the website is live and more people start playing there will be many opportunities to build on the website and expand it to meet 
the growing and changing needs of the club.

**Feature 1:** An online membership form with e-signature capability.
This feature has not been implemented in the first release as I do not yet have the knowledge to do so.

**Features 2:** Online payment methods for membership and sessions fees.
This feature has not been implemented in the first release as the club doesn't have a bank account and I do not yet have the knowledge to build 
this option into the site.

**Feature 3:** Sponsorship opportunities.
This feature has not been implemented in the first release as the club doesn't have the necessary presence yet to create interest from potential sponsors.

**Feature 4:** Membership form.
This was intended to be included in the original release, however for now it will be emailed to potential members and will be deployed in a future release, as part
of the digital requirements in Feature 1.

## Structure

The website is structured into four pages: Home | What is netball? | Get in touch | Photo gallery

![Site structure](assets/images/supporting-docs/site-structure.jpg)

Each page is responsive on various device sizes, has the same clean, simple structure, and contains the navigation bar and footer. The navigation bar 
is static, and the favicon links back to the home page.

The layout is primarily based on [Bootstrap's grid system](https://getbootstrap.com/docs/5.0/layout/grid/), heavily modified to achieve the desired look and style.

Each page has the necessary internal links to direct the user in alignment with the relevant part of their online journey.

### Homepage
#### Content
- Welcome message
- About the club
- Next sessions dates, time and location
- Current information about Covid-19
#### Internal links
- What is netball?
- Get in touch

### What is netball?
#### Content
- Basic rules and principles of the sport
- Photos of professional play
- Diagrams (where appropriate)
#### Internal links
- Get in touch
- Photo gallery

### Get in touch
#### Content
- Contact form: Name (required), Email (required), Phone, Message
- Contact info: club email
- Committee member basic info: photo, name, small bio
#### Internal links
- Session dates on homepage

### Photo gallery
#### Content
- Player and sports-related photo gallery

### Error 404
- In case users are directed to a broken link

## Skeleton

### Homepage wireframe
![Homepage wireframe](assets/images/supporting-docs/homepage-wireframe.jpg)


### What is netball wireframe
![What is netball wireframe](assets/images/supporting-docs/netball-wireframe.jpg)

### Get in touch wireframe
![Get in touch wireframe](assets/images/supporting-docs/contact-wireframe.jpg)

### Photo gallery wireframe
![Photo gallery wireframe](assets/images/supporting-docs/photos-wireframe.jpg)

The wireframes were created using <a href="http://www.balsamiq.com" target="_blank">Balsamiq</a> and demonstrate the responsive behaviour of the site on each device size, 
as well as the clean, simple structure, which does not overload the user. The site presents the user with the information they are looking for, simply and logically, 
using as few clicks as possible.

## Surface
### Typography:
Using [Google Fonts](https://fonts.google.com/specimen/Permanent+Marker?preview.text=Gothenburg%20Netball%20Club%20Est.%202019%20Fun,%20fitness%20and%20friendship!&preview.text_type=custom)
I selected Permanent Marker for all navbar text, and headings, as I felt it gives a feeling of friendliness that I was looking for to match the tone of the site.
As per Google Font's recommendation, the accommodating font used is Lato. Sans-serif is used should either of these fonts fail to load.

### Imagery:

Where possible, the site uses real-life images. However, this has not been possible for all images. The What is netball image of the ball falling through a hoop is a basketball,
not a netball. It was not possible to source free images of netball that meet the needs of the site. This will be updated in the future when the club can
take its own photos for the site.

[Netball falling through a hoop |](assets/images/ball-in-net-resize.jpg) 
[Andres Siimon](https://unsplash.com/photos/jS2Cgv-Xppw)*

The following three images used on the photos.html page are published on Gothenburg Netball's Facebook page, for which I am an administrator.

[Image 1 ](assets/images/photo-gallery/group-1.jpg)

[Image 2 ](assets/images/photo-gallery/group-2.jpg)

[Image 3 ](assets/images/photo-gallery/group-5.jpg)

The other images on the page are stock images, sourced from Unsplash.com:

[Image 4 | ](assets/images/photo-gallery/group-3.jpg)
[Naassomz1](https://unsplash.com/@naassomz1?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Image 5 | ](assets/images/photo-gallery/group-4.jpg) 
[I am chang](https://unsplash.com/@iamchang?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Image 6 | ](assets/images/photo-gallery/group-6.jpg) 
[LinkedIn](https://unsplash.com/@linkedinsalesnavigator?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

The images used for the committee members were also sourced from Unsplash.com:

[Mark Darcy | ](assets/images/committee-members/mark-darcy.jpg)
[Christian Buehner](https://unsplash.com/@christianbuehner?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Bridget Jones | ](assets/images/committee-members/bridget-jones.jpg) 
[Eugabriel Silverio](https://unsplash.com/@eugabrielsilverio?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Daniel Cleaver | ](assets/images/committee-members/daniel-cleaver.jpg) 
[Sean Hall](https://unsplash.com/@_sean_hall_?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyTex)

[Helen Fielding | ](assets/images/committee-members/helen-fielding.jpg) 
[Clemono](https://unsplash.com/@clemono?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

The flag icons were sourced from [Flacticon](http://flaticon.com) and are also sourced on the site.

### Colour scheme:

The principle colours selected are variants of blue and yellow, the reason being two-fold: they are the colours of the Swedish flag, and other netball 
clubs in Sweden have red and green as their team colours, so we needed something different. All colour variants have been selected using 
[Coolors](https://coolors.co/) to compliment each other and provide a feeling of safety and calm, as required in the strategy.

![Color choices](assets/images/supporting-docs/color-codes.jpg)

### Favicon: 

I used the [basketball ball image from Font Awesome](https://fontawesome.com/icons/basketball-ball?style=solid) and used css styling to match the colours 
of the website as the favicon.

# Technologies used

This project uses the following languages:

 - HTML 5
 - CSS

This project was created on [GitHub](http://www.github.com).

This project uses the following libraries and frameworks:

 - [Balsamiq](https://balsamiq.cloud/) - used to create all wireframes
 - [Bootstrap](https://getbootstrap.com/) - Bootstrap was used as the main grid structure for the site, for the navbar, including navbar toggler,
 and contact form, and was heavily modified to meet the needs of the project
 - [Google Fonts](https://fonts.google.com/specimen/Permanent+Marker?preview.text=Gothenburg%20Netball%20Club%20Est.%202019%20Fun,%20fitness%20and%20friendship!&preview.text_type=custom) - Permanent Marker and Lato
 - [Font Awesome](https://fontawesome.com/) - used for the [basketball ball favicon](https://fontawesome.com/icons/basketball-ball?style=solid) and 
 [checklist icons](https://fontawesome.com/icons/check-circle?style=regular)
 - [Tiny PNG](https://tinypng.com/) - used to resize images to reduce site loading time  
 - [Free Formatter HTML](https://www.freeformatter.com/html-formatter.html) - for HTML code formatting
 - [Free Formatter CSS](https://www.freeformatter.com/css-beautifier.html) - to beautify CSS code
 - [Coolors](https://coolors.co/) - to select a color pallete to match the required tone of the site
 - [Stackoverflow](http://stackoverflow.com) - general help to undertand forms, image sizing and navbar toggler 
 - [W3 School](https://www.w3schools.com/html/html_tables.asp) - help understanding the table html code
 - [Grammarly](https://app.grammarly.com/) - the free service to double check grammar, spelling and tone
 - [Lighthouse](https://www.webpagetest.org/result/210126_DiYW_ef25f45f403133d4937b7ce39a1adc42/) - used to score accessibility and general site performance 
 - [Monday.com](http://www.monday.com) - I used this site for project management, to ensure tasks were completed on time 

# Testing:

See separate [Testing file](TESTING.md) for testing information.

# Deployment:

NB: During deployment, I had a few occasions where I duplicated commits, in particular at the beginning, and did not commit as often as I should. This I tried
to rectify as I continued to build the site.

This project was developed using Gitpod, committed to git and pushed to Github using the built-in functionality.

To deploy the pages to Github Pages, from the Github repository, the following steps were taken:

1. Log onto [Github](http://github.com).
2. From the list of repositories, select **CatherineTrevor/gothenburg-netball**.
3. From the menu bar, select **Settings**.
4. Stay on this page and scroll down to **Source**. 
5. Select **Master branch** and click **save**.
5. Wait a few minutes: the live link can be retrieved from the top of the page.

## How to run this project locally

1. Log onto [Github](http://github.com): create an account if required.
2. From the list of repositories, select **CatherineTrevor/gothenburg-netball**.
3. Click the **"Code"** dropdown within the menu above the commits.
4. Copy the URL address, or Download ZIP and save locally.
5. Using your chosen IDE, copy the URL within the CLI.
6. Alternatively, select **"Open with Github Desktop"**.

# Credits:

## Content:
- [Good reads](https://www.goodreads.com/author/quotes/6419544.Shanti) - the quote on
[photo gallery](https://catherinetrevor.github.io/gothenburg-netball/photos.html) page
- [Netball Sweden](https://www.netball.se/origin-of-netball) - source of basic netball info, and information about the origin of netball
- [Play Simple Netball](https://www.simplenetball.co.uk/rules/) - the list of players and their roles has been taken from this site. I also used it to verify my own knowledge of the rules, to ensure what I was writing was correct
- [Netball court illustration](assets/images/court-layout.jpg) - I drew this myself using Microsoft Powerpoint and saved as a jpg, based on my own knowledge
- [Committee member quotes](https://catherinetrevor.github.io/gothenburg-netball/contact.html) - all quotes are purely fictional, written by me

All other content has been written by me.

## Media:

- [Unsplash](http://www.unsplash.com) - committee members, and some photo gallery images sourced from Unsplash. Specific sources cited in the above 
imagery section 
- [Youtube](https://www.youtube.com/embed/WGaYDvaZ4No) - what is netball video
- [Gothenburg Netball Club Facebook](https://www.facebook.com/gothenburgnetball/)
- [Netball word graphic on the photo gallery](https://catherinetrevor.github.io/gothenburg-netball/photos.html) and [contact word graphic on the Get in touch page](https://catherinetrevor.github.io/gothenburg-netball/contact.html) were created using [Word Art](https://wordart.com)
- [Google maps](http://www.maps.google.se)

## Acknowledgements:

While designing and developing this site, I took inspiration from the following websites;

* [Skåne Netball Club](https://skane-netball-club.webnode.com/)
* [Stockholm Netball Club](https://www.stockholmnetballclub.com/)
* [Netball Sweden (Sweden's national netball federation)](https://www.netball.se/)
* [Kent County Club](https://www.kcnc.org.uk/)
* [Nicole Saidy](https://nicolesaidy.com/)
* [Leen Heyne Collection](https://leenheyne.nl/jewelry-all)

While the club is real, the names of the other committee members are fictional and have been taken from the book Bridget Jones' Diary by Helen Fielding.

Thanks also to my mentor at Code Institute Aaron Sinnott, the chair of Netball Sweden for her time and feedback, as well as Brendan, another member of slack for his time and 
feedback.
