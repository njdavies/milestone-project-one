# User Centric Frontend Development

I was given the following brief to construct a static website for a band:

> The band is a 1960’s rock band and have around 50 years’ experience of performing live at numerous events around the world. You have
> been given the following requirements after interviews with the client’s representatives: 
>
> Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalogue, and any new material as it becomes available.
> Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings
> and Christmas parties. 
>
> The band has provided you, the developer, with the following assets that they would like to showcase on their website:
>
> * Photos of the band members
>
> * A video clip
>
> * Audio clips
>
> Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube 
pages.

The music and general image of the band is energetic and uplifting, therefore I decided to use a vibrant colour scheme and make
the site as aesthetically pleasing as possible. Also, because the site is to appeal to both existing fans and potential new fans, I
wanted to make the site easy to navigate through and the features self-intuitive.

---

## UX

### User Stories

Using the brief given to me, I created [User Stories](https://pinup.com/SJSXZxe57 "User Stories") in a tool called Pinup. This allowed
me to break down each feature required within the website.

### Mock Ups

I then used a tool called Pencil to create [wireframes](https://github.com/njdavies/milestone-project-1/tree/master/wireframes) for each
of the pages in the site. This allowed me to plan out the content and functionality on each page, taking into account the user stories I
had put together. 

---

## Features

### Existing Features

* News page - Allows users to view the most up to date news regarding the band. This page also serves as the Home page of the site.

* Discography page - This page allows users to view the extensive back catalogue of the band by providing details of the albums they have
released.

* Media page - Allows users to view pictures of the band, listen to a selection of audio clips or watch a video. 

* Tour page - Allows users to view the upcoming tour dates of the band which would then allow them to plan in advance if they would like
to go and see the band live in the future.

* Contact - Allows users to contact the band and arrange for a booking, by having them fill out a form providing their contact
information.

* Social Medial links - Allows users to navigate to the band's Facebook, Twitter or YouTube pages to see additional content and keep
tabs on what the band is up to from day to day.

### Features Left to Implement

* A feature that I would like to add is a forum so that users can come together to engage in conversations about the band. This would 
then help to create a closer community amongst the fans of the band, whilst also serving as a place for new fans to join in the 
discussion.

---

## Technologies Used

In designing and creating this website I have utilised the following tools, languages and frameworks:

* [Pinup](https://pinup.com/SJRjLxMhQ) - As user stories are usually written on sticky notes I decided to use this tool to replicate the 
same process digitally.
* [Pencil](https://pencil.evolus.vn/) - I wanted to put together mock-ups of the website before starting to code anything. This simple 
but effective tool let me create wireframes very quickly, and aided in visualising how the website would look from the beginning of 
development.
* [HTML5](https://en.wikipedia.org/wiki/HTML5) - I used this language to build the basic structure and elements of the website.
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - This language was used to apply styling to the HTML structure, and 
described how the elements should be displayed.
* [Bootstrap 4](https://getbootstrap.com/) - I utilised the Bootstrap framework which allowed me to quickly incorporate templates for 
navigation bars and forms. I also made extensive use of the framework's grid system, which allowed me to make the site fully responsive across different viewports
and web browsers.
* [Font Awesome 4.7](https://fontawesome.com/) - I incorporated social media icons within the website, using this toolkit.
* [Hover.CSS V2](http://ianlunn.github.io/Hover/) - This tool was used to apply a grow effect to the navbar tabs and social media icons
within the website. 
* [Google Fonts](https://fonts.google.com/) - I incorporate several fonts from this library that went together well with the colour
scheme, further enhancing the vibrant theme of the site.

---

## Testing

### Automated Testing

In order to rigorously test the functionality of the site I initially made use of the following automated tools:

[W3C Markup Validation Service](https://validator.w3.org/) - I used this tool to validate the HTML used within the website. To do this
I pasted the website URL (https://njdavies.github.io/milestone-project-1/) into the address field and hit Check. It will then advise you 
of any errors within your code and make suggestions regarding how to keep this as correct as possible against the W3C standards.

[W3C CSS Validation Service] (https://jigsaw.w3.org/css-validator/) - I used this tool to validate CSS used within the website. To do
this I first selected the 'By direct input' tab and then pasted the entire CSS code from the [style.css](https://github.com/njdavies/milestone-project-1/blob/master/assets/css/style.css) file into the box provided. I
then hit Check. As per the HTML checker above, if there are any errors in the code these will be highlighted.

### Manual Testing

I tested the User Stories I had put together by conducting the following scenarios:

1. **News Page**
    1. When in another page on the site, hover over News Page tab in navigation bar to check that grow effect works correctly.
    2. Select News Page.
    3. Check that Header displays correctly.
    4. Check that Footer displays correctly.
    5. Check that Social Media Links within Footer grow when hovered over and display tooltip.
    6. Check that text and images in main section of page display correctly.

2. **Discography Page**
    1. When in another page on the site, hover over Discography Page tab in navigation bar to check that grow effect works correctly.
    2. Select Discography Page
    3. Check that Header displays correctly.
    4. Check that Footer displays correctly.
    5. Check that Social Media Links within Footer grow when hovered over and display tooltip.
    6. Check that text and images in main section of page display correctly.
    
3. **Media Page**
    1. When in another page on the site, hover over Media Page tab in navigation bar to check that grow effect works correctly.
    2. Select Media Page.
    3. Check that Header displays correctly.
    4. Check that Footer displays correctly.
    5. Check that Social Media Links within Footer grow when hovered over and display tooltip.
    6. Play each audio file and check that they run correctly. Test that pause, mute and download (where browser permits) options all work
    correctly.
    7. Play video and check that this runs correctly. Test that pause, mute, full screen and download options all work correctly.
    8. Check that text and images display correctly.

4. **Tour Page**
    1. When in another page on the site, hover over Tour Page tab in navigation bar to check that grow effect works correctly.
    2. Select Tour Page.
    3. Check that Header displays correctly.
    4. Check that Footer displays correctly.
    5. Check that Social Media Links within Footer grow when hovered over and display tooltip.
    6. Check that text and images in main section of page display correctly.
    
5. **Contact Page**
    1. When in another page on the site, hover over Contact Page tab in navigation bar to check that grow effect works correctly.
    2. Select Contact Page.
    3. Check that Header displays correctly.
    4. Check that Footer displays correctly.
    5. Check that Social Media Links within Footer grow when hovered over and display tooltip.
    6. Hover over Send Request button and check that grow effect occurs.
    6. Try to submit form with no fields completed and verify that an error message appears that states input is required.
    7. Try to submit form with invalid email address and verify that an error message appears.
    8. Check that text displayed in main section of page displays correctly.

During the development of the site I made extensive use of Chrome Developer Tools to view the content in different viewports and assess 
how it was behaving. This then led to me using multiple media queries to make subtle changes to the code so that the content was always
displayed correctly.

In order to be completely satisfied that the site worked correctly across multiple browsers I completed the manual testing above after
loading the site in Chrome, Internet Explorer, Edge and Firefox. 

---

## Deployment

In order to deploy the site, I first created a remote Git repository on GitHub. I then went into the settings option of this remote
repository and changed the Source option under the GitHub Pages section to Master Branch. This then provided me with the following
URL for the site - https://njdavies.github.io/milestone-project-1/

I then committed and pushed content from my local repository to the remote repository each time I added a new piece of functionality to
the site. This allowed me to continually test the live version of the site in different browsers throughout development, to see how
it was responding.

---

## Credits 

### Content

The text used for each album in the discography page was copied from the following Wikipedia pages: 

1. The Monkees - (https://en.wikipedia.org/wiki/The_Monkees_(album))
2. More of the Monkees - (https://en.wikipedia.org/wiki/More_of_the_Monkees)
3. Headquarters - (https://en.wikipedia.org/wiki/Headquarters_(album))
4. Pisces, Aquarius, Capricorn & Jones Ltd. - (https://en.wikipedia.org/wiki/Pisces,_Aquarius,_Capricorn_%26_Jones_Ltd.)
5. The Birds, The Bees & The Monkees - (https://en.wikipedia.org/wiki/The_Birds,_The_Bees_%26_The_Monkees)
6. Head - (https://en.wikipedia.org/wiki/Head_(The_Monkees_album))

### Media

The photos used for the news items were obtained from the following websites:

Greatest Hits Album - (https://www.amazon.com/Monkees-Greatest-Hits/dp/B0000033O3)

Walk of Fame - (http://seiginonakama.blogspot.com/2013/03/happy-birthday-mickey-dolenz.html)

The photos used for each album in the discography page were obtained from the following Wikipedia pages:

1. The Monkees - (https://en.wikipedia.org/wiki/The_Monkees_(album)
2. More of the Monkees - (https://en.wikipedia.org/wiki/More_of_the_Monkees)
3. Headquarters - (https://en.wikipedia.org/wiki/Headquarters_(album)
4. Pisces, Aquarius, Capricorn & Jones Ltd. - (https://en.wikipedia.org/wiki/Pisces,_Aquarius,_Capricorn_%26_Jones_Ltd.)
5. The Birds, The Bees & The Monkees - (https://en.wikipedia.org/wiki/The_Birds,_The_Bees_%26_The_Monkees)
6. Head - (https://en.wikipedia.org/wiki/Head_(The_Monkees_album)

The photos used in the tour page were obtained from the following websites: 

1. Bryce Jordan Center - (http://cityportals-statecollegecom-assets.s3.amazonaws.com/assets/news/images/1473410_34504.png)
2.  Spectrum Center - (https://www.visitcabarrus.com/wp-content/uploads/2017/08/Time-Warner-Cable-Arena-lg0_f8f11871-5056-a36a-069452c7afa665bc-3.jpg
)
3.  Wells Fargo Center - (
https://www.bluestonecomm.com/wp-content/uploads/wellsfargocenter1web-495x400.jpg)

All remaining photos (including the header logo), audio clips and video from the Media page were obtained from the following GitHub
repository - (https://github.com/Code-Institute-Org/project-assets)

### Acknowledgements

I received inspiration in the design of this project from the following websites:

1. [Muse Official Website](https://muse.mu/home.htm?force=show)
2. [Coldplay Official Website](https://coldplay.com/)
3. [Metallica Official Website](https://www.metallica.com/)
