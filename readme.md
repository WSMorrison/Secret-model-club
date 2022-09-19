# SKRT modl klub

SKRT modl klub is a landing page for a club for model and miniature builders. The model club brings new messaging technology like Discord to target users who enjoyed the community in defunct and obsolete forums, but find social media like Facebook, Instagram, and Twitter too broad to maintain meaningful discussion and friendships. 

Users of the SKRT modl klub website will be able to find links to the appropriate Discord server, plus information about in-person club meetings. The site will also capture user email and basic preferences so users can receive a periodic targeted email. There will be links on the site to take users to the Discord server and a Google Maps location for in person meetings. Social media links other than Discord will take users to a second page that indicates that the club is secret, and therefore does not have a social media presence.

[SKRT modl klub](https://wsmorrison.github.io/Secret-model-club/)

[SKRT modl klub ain't got no socials](https://wsmorrison.github.io/Secret-model-club/socialswarning.html)

## Features

    -Navigation bar
        -A navigation bar stays fixed to the to of the page as the user scrolls through the page.
        -The links in the bar link to different sections of the site, allowing the user to quickly and easily find the information they need.
        -The links stay centered responsively to keep a consistent look.
        -The navigation bar is translucent and blurs the backdrop to maintain clarity about where user is on the page.
        -The nevigation bar clears the linked sections to maintain clarity, and the scroll animates smoothly to keep the user oriented.
    -Splash image
        -The splash image shows a miniature car build by a member, and sets the tone for the skill level and interests of target users.
        -The website name is in a color and font that is reminiscent of rubber stamps on manila folders indicating that things are secret.
        -The website name is in a translucent box over the image.
        -The splash image and the translucent box are responsive to different screen sizes.
        -The slash image grows to a maximum size to maintain resolution and is set over a responsive, blurred background of the same image on very large screens.
    -Online section
        -The online section includes images to indicate what the user can expect by participating online.
        -The images have text to add context.
            -Users can expect to find and discuss industry news.
            -Users can share and discuss what they are working on, and what other members are working on.
            -Users can discuss new, rare, and interesting kits, parts, tools, items, and objects they have acquired, want to git rid of, or just want to show off.
        -The online section includes a link to the Discord server for user navigation.
        -The text is in translucent boxes that blur the backdrop so they can maintain the interest of the images but can keep the text legible.
        -The images, text, and text boxes are responsive to different screen size.
    -One:One section
        -1:1 is scale notation for full size (as opposed to 1:24, a common model car scale) and in this case indicates in person club activities.
        -The One:One section includes images to indicate what the user can expect by particiating in person.
        -The images are paired with text to add context.
            -Users can expect to casually discuss topics similar to what is available online.
            -The Beer of the Month indicates that users can expect casual, often off topic meetings, and affords the club opportunity to use different meeting places as part of cross promotion with relevent and interested breweries.
            -Users can participate in an annual swap meet and sale.
        -The One:One section includes a link to a Google Maps page showing where the in person meetings are held.
        -The text is in translucent boxes that blur the backdrop so they can maintain the interest of the images but can keep the text legible.
        -The images, text, and text boxes are responsive to different screen size.
    -Transmissions section
        -The Transmissions section is where the site can capture user information for an email newsletter.
        -There are checkboxes so users can indicate as many related interests as they like, including none.
        -There is an email input field so user can submit their information.
        -There is a submit button that the user can click to make their submition.
    -Footer
        -The footer includes font based logos to link to Discord and potentially other social media.
        -The Discord logo links to the SKRT modl klub Discord server.
        -The Facebook, Instagram, and Twitter links link to another internal page that indicates that there is no social media presence.
    -"SKRT modl klub ain't got no socials."
        -This second page indicates that there is no social media presence for the club.
        -The page includes the same header nav bar that can take the user back to the main page, or the appropriate section of the main page.
        -It also has a similar footer that takes user back to the top section of the same page, without refreshing it.

## Testing

-I confirmed that the wesbite works, looks good, and maintains clarity and functionality on different sized devices and at different sizes by using Chrome developer tools, as well as using the site on multiple devices.
-I confirmed that the links in the navigation bar, the "social media" footer, and in the content sections are clear, legible, and take users to the appropriate address.
-I confirmed that the site is intuitive and works properly by having a hanful of testers interact with the site on different divices, in different places, and with different use cases.
-I confirmed that the form works properly, and requires an email for submission.

## Bugs

    -Solved bugs:
        -Responsiveness was poor in first draft. I restructured the site to build for mobile and small screens first, using min-widths to change layout at page gets larger instead of max-width to change layout as the page gets smaller.
        -Images in the Online and One:One sections did not work. I found that the images were using relative address instead of absolute. Changed the src= code.
        -Links to sections in the navigation bar did not all work. While troubleshooting I found that I had changed the section id= naming convention but did not update the links in the navigation bar. Updated all the links to correct section id attributes.
        -Found the socials-warning page had a responsiveness error. Troubleshooting found that I had set the width for #socials-warning-container to 100rem instead of 100%. Changed the width code to a responsive dimension.
    -Unsolved bugs:
        -There are no known unsolved bugs.
    -Validator testing:
        -No html errors were found using W3 schools html validator.
        -No CSS errors were found using W3 schools CSS Jigsaw validator.
        -Accessibility scored well in Chrome developer tools Lighthouse tool, and I confirmed that colors and contrast maintain good visibility.

## Deployment:

    -The page is deployed on Github pages using the following procedure:
        -In the associated Github repository, I navigated to settings tab.
        -In the settings tab, I navigated to the pages link in the lefthand navigation bar.
        -I deployed the Master Branch as the source.
        -Github provided the link to the completed website.
    -The deployed site can be found at this link: [SKRT modl klub](https://wsmorrison.github.io/Secret-model-club/)

## Credits

    -The Gitpod template provided by Code Institute.
    -Many pieces of code are inspired by Code Institute training, W3 schools resources, Stack Overflow forums, and other searchable online resources.
    -Adam Boczek in the UCD July 2022 cohort helped with code to animate scrolling and clear sections when using the navigation bar.
    -The fonts used on this website are:
        -Rubik Dirt [Google Fonts.](https://fonts.google.com/)
        -Palanquin Dark from [Google Fonts.](https://fonts.google.com/)
    -Font-based logos for Discord, map, and social media links are from [Font Awesome.](fontawesome.com)

## Media

    -Photos are by the developer, unless otherwise noted.
    -The following photos from other sources were used for educational and training purposes only:
        -The photo associated with Modeling News is taken from The Modeling News. The source can be found [here.](https://www.themodellingnews.com/2019/05/tmn-on-tour-japans-58th-shizuoka-hobby.html)
        -The photo associated with Station Meetings is taken from the Alexander City Outlook. The source can be found [here.](https://www.alexcityoutlook.com/news/fight-breaks-out-at-city-hall-after-council-meeting/article_9bc75cd2-77a7-5865-bd32-e8c34bbc94a5.html)
        -The photo associated with Beer of the Month is taken from Twitter, user @Beerdo_El. The source can be found [here.](https://mobile.twitter.com/hashtag/workbenchipa?src=hash)
        -The photo associated with Stash Adjustment is taken from Intscalemodeller.com user DRUMS01. The source can be found [here.](https://intscalemodeller.com/viewtopic.php?t=28144)

