# Warhammer 40,000

The objective of this webpage is to provide an introduction to the Warhammer 40,000 universe along with an introduction to some of the original factions.
As the warhammer 40,000 universe has a huge rich background of lore and factions it can be quite daunting for new players, collectors and readers to pick 
up.
The idea behind this website is to create an introduction for people interested in Warhammer 40,000 without overloading them with information and still 
providing the means to gain access to any further information that they might want, this will help to drive traffic towards games workshop's other websites 
as well as social media pages and in turn drive up sales.

### UX

The website is aimed at people who have an interest in the Warhammer 40,000 universe weather it is collecting, painting and/or playing the various games set 
in the universe or the novels and background itself which interests them, the universe is a huge and daunting thing to get in to and it may be difficult for
new players to find where to start.
This website would be used as an introduction to the Warhammer 40,000 universe as well as an introduction to some of the classic factions providing a portal
to the various Games workshop websites so users can easily find their way to the content that they are looking for.
Without going too deeply in to the sub factions that belong to the many factions of the Warhammer 40,000 universe this project provides introductory
information to give users an idea of the background without overloading them with infromation but also provides them with the means to find the information
that they are most interested in.

### User Stories

#### collector/player user type
As a collector, I want to find information on the different factions, so that I can make a decision on which models to buy.

#### fiction reader user type
As a reader of science fiction, I want to discover more about the setting, so that I can decide if I am interested in the fictional stories and characters.

#### Wireframes

Below are my first drafted ideas of how the page would look and work, these were originally made using WireframeSketcher.

- [Home Page on Desktop] (assets/wireframes/desktophome.png)
- [Home Page on Mobile] (assets/wireframes/mobilehome.png)
- [Open Modal] (assets/wireframes/modals.png)
- [Open Collapse on Mobile] (assets/wireframes/opencollapse.png)

### Features

#### Navbar

The Navbar used in this project was taken from Bootstraps library and then styled with CSS, some of the list items were reordered and an additional one 
was added to match the layout of the page. The navbar is fixed so that a user can move to any part of the page from anywhere on the page and is styled to 
be opaque so that it doesn't get in the way.

#### Introduction Video

Using a Bootstrap embed this video was taken from Warhammer TV, Games Workshop's youtube channel, it is placed at the top of the page as a way to catch the
users attention and build some interest and insight in to the setting. As the video is quite large, on smaller screens it is replaced by an image instead.

#### Introduction Text

As this is a large block of text it includes an image to break up the information, one block is to set the scene while the other speaks about the hobby 
itself.
On smaller screens this information is placed within a collapse, which was taken from bootstrap and the button to open and close it was taken from
font Awesome, so there isn't too much information on the screen for a user and the text can be collapsed away once finished with.

#### Factions

To provide an introduction to some of the factions in the Warhammer 40,000 universe there are four images, one of a Space Marine, Chaos Space Marine, Ork
and Asuryani, which have been included as they are some of the original factions for the game and it also gives users an idea of how these factions look.
The images have been made responsive so that on mobile they stack one on top of the other to keep the characters standing apart, allowing them to be larger
and draw attention to themselves seperate from the others.
On larger screens these images are accompanied by text that gives some background information on each faction, their themes and where they stand in the 
universe.

##### Modals
On smaller screens the faction information has been made responsive and will no longer display on the page, instead selecting the image for each faction 
will open up a modal which has been taken from Bootstrap and styled with CSS, this allows the text to be hidden away and only displayed when the user
wishes to read it rather than taking up too much space on the screen.

#### Newsletter Sign Up

Appearing at the bottom on all screen sizes is a call to sign up to a Newsletter, selecting the letter image which was taken from Font Awesome will open up
a modal which was taken from Bootstrap and styled with CSS, Within this modal is a form that was also taken from Bootstrap prompting the user to enter their
email address. The email has been set to required so pressing the submit button without entering anything will display a error message, as will entering an
invalid email address.
For the purposes of this project the collected inforation is not saved anywhere.

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits---------------------------------------------------------------------------------------------------------------------------------------------

-----------------------------------------Content
The text used in the introductory collapse and faction modals were copied from www.warhammer40000.com

-----------------------------------------Media
The "40klogo.jpg" image was taken from www.themarysue.com
The background image for the page and modals was taken from www.hadi.palmex.co
The "spacemarine.jpg" image was taken from www.warhammer40000.com
The "chaosspacemarine.jpg" image was taken from www.eternalcrusade.com
The "eldar.jpg" image was taken from www.mikemyler.com
The "ork.jpg" image was taken from www.pinterest.com (originl art by albe75.deviantart.com on deviantART)
The "collapse-filler.jpg" image was taken from www.warhammer-community.com
The "gw-logo.jpg" image was taken from the games workshop wiki page (https://en.wikipedia.org/wiki/Games_Workshop)
The "bl-logo.jpg" image was taken from www.warhammer-community.com
The "wh-community.jpg" image was taken from www.40krpgtools.com
The "fw-logo.jpg" image was taken from www.spikeybits.com 
The "replacement.jpg" image was taken from www.warhammer-community.com

Acknowledgements
I received inspiration for this project from X