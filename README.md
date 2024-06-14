Title - Taj Mahal 

1. Purpose of the project. 

        "Taj Mahal - An Eternal calling" website is a "one stop" source of information that caters to users of all ages and varied interests across fields. It provides first hand information based on authors "TWO" visits to the Taj Mahal. It is supported by pictures clicked by the author and includes a "link" to a published artcile articulating the authors thoughts.
        As an example, a tourist may find useful information pertaining to "visit times" and "how to get there". Likewise anyone with interest in architecture can find useful information under "tickle your curosity" link on the landing page.Furthermore, details on the "information page" can be used to to arrive at decisons on the reasons to to visit the Taj. 
        Visitors to the website can leave their details to get in touch with the author or upload their own experiences via the "upload files and image" section under the "Contact us" page. 
 
2. Features.
        a.The website is designed using the "Mobile First" Responsive approach using a structured layout and "meta" tags.
        b.The website has four pages including the landing page.  "Home", "Information", "Gallery" and "Contact Us".
        c.The header includes the title of the website " Taj Mahal- An Eternal Calling and is common across all pages 
        d.The footer inlcudes the "copyright" and " author" details and icons for social media
        e.The chocie of foreground and background colors have the right contrast providing a rich user experience .
        d. All images, inclduing the hero image has a "alt " element to cater for the visually impaired.
        f. All images in the gallery have the right resolution when viewed across screens with different viewports.
        g. All External links open in a seperate tab -" tickle your curosity" on the home page and "best time to visit" section under the 
           information page  
        h. CSS media queires used where appropriate for different screen sizes.
        i. Masonry layout used to align images in the "Gallery" page.
        j. Relative paths are used for refering to folders and files.
        l. Favicon is  included to be displayed within the browser tabs and bookmarks bar is added for three different 
        j. "Keywords" and "Description" incldued for search engine optimization. 
        k. "Hover" property used to hightlight pages on navigation bar, social media icons and "tickle your curosity" link on landing page.

3. Font family and colors.

        a.Google fonts used for styling. Download link below
        ('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Oswald:wght@200..700&display=swap');
        b. Font-family used for styling : "Cursive", Courier New', Courier, monospace
        c. colors used for styling  :        aliceblue,bisque,brown,cyan,crimson,gold,lightyellow,aqua, magenta,lightcyan,
        
4. Technology used in development and testing-: 
        1.Google Chrome as the Browser.
        2.Cloud-based platform :gitpod.io and github for designing and hosting the website
        3.Devices with different viewports for testing the responsiveness - Galaxy A54, iPhone 14 Pro, Galaxy A25, Asus AMD Ryzen7 4800H with 
           Radeon Graphics    
    
5. Website Page and feature Description 
    a.Home page ( landing page) : - 
        1.This page is divided into three sections, Head, Body and Footer. 
        2. The Main element contains the header and hero image 
        2. The Navigation bar in the landing page includes links to three other pages- The Information, Gallery and Contact Us page.
    Head Section 
        1.Language chosen is US English 
        2.Meta tags "viewport" and "content" are included to make the page responsive. 
        3.Keywords and description are added in the head section for Search Engine Optimization 
        4.The CSS stylesheet which is an external file is linked here in the head section 
        5.The favicon to be displayed within the browser tabs and bookmarks bar is added for three different screen sizes.
        6. The title "Taj Mahal " is defined here.

    BODY SECTION  
        
        1.The body element contains <div> element, nested within it , two child elements "<a>" and <nav>.
        2. The <nav> included a <ul> with details of each page
        3. below the <div>, under the <main>, ther is a <section> which has the hero image 
        3. It also includes the <footer> element, which has two <h2> elements nested within it ad a<nav> which defines the <ul> for social media.
            Header:
                1.The Header section is common across all pages. It is nested under the Body element 
                2.The Header is created using an H1 element with the content" Taj Mahal- An Eternal Calling"
                3.The header is common across all pages 

             Navigation:
                1.Contains a unordered list to define the three pages-Home, Information, Gallery and Contact Us
                2.Hovering the mouse over these changes the colour to Cyan.
                3.Flex properties applied to UL element nested under the NAV element 
          
            HeroImage 
                1.The Heroimage has been clickeed by the author dueing his visit to TAJ 
                2.Inside the hero image just below the header, in the center is a link "Tickle your curosity" ".
                3.Hovering the mouse over it changes the color to gold 
                4.Link, when clicked  opens in a new tab. 
                5.The  image explains the architecture of the taj and has been sourced externally. 

            Footer 
                1.Displays the authorship of the website, copyright information and the social media icons
                2.Hovering mouse over the icons changes the color to "cyan"
                3.Clicking the social media icon opens in a new tab - home page or login page of that particular social media site 
                4.Each icon has a "alt" element to cater for the visually impaired.
                5.The footer is common across all pages 

    b.Information page: 
    ![Screenshot of Information Page ](image-2.png)
    
        1.The information page has header <h2> titled" !!! Explore the modern wonder of the world!!!, followed by a short paragraph. 
        2. The paragraph, contents created by the author explains the feelings one could experience. 
           These feeling were experienced by the author on his visit . 
           It also provides some information of past visitors and things to do..  
        3. Four sections on this page provide additonal information.
        4. These sections are  
            I. Reasons to visit the "Wow" factor 
            II. Historical facts 
            III.How to get there 
            IV. Best time to visit ( has an external clickable link ) 
        5. Flex properties were used 

    c. Gallery page : 
        1.Displays photgraphs takne by the author on his visit. 
        2. Masonry layout along with media queries was used in style sheet to ake this section responsive. 

    d. Contact Us page:
        1. This page is used to gather visitor information 
        2. A visitor can also drop images or files if they desire. 
        3.

6. Future Features: 
    True to responsive coding priciples the website also needs to be responsive to future requirements an enhancements.
    The author plans to add a 3D video section, glowinf featues and more changes to the sytling and logic using Javascript.
    
7. Testing 

   7.1 code validation
        a.W3school HTML validator was used to test the code at regular intervals https://validator.w3.org/

        b. CSS validation service at https://jigsaw.w3.org/css-validator/ was used to test the "style.css" sheet.
        


   

   7.2 test cases (user story based with screenshots)
   7.3 fixed bugs
   7.4 supported screens and browsers


8. Deployment 
  7.1 via gitpod

  Every change post additon/modification/alteration of the code in gitpod.io was added to the Github respository using the fllowing three ccommands 
  1) Git add .
  2) Git commit -m "meaninful comment" 
  3) Git push - to push changes to Github 

   7.2 via github pages
   ![Screenshot of GITHUB - to create an external link for the website](image.png)

9. Credits

    a.Referenced sites 

        1. Fontawesome.com website was used to download free fonts for the social media icons- Facebook, Twitter, Instagram and Youtube 
        2. An image "architecture of the Taj" was referenced from an external website  https://www.artefactindia.com/Taj-Mahal-and-its-marble-inlay-art.
        3. Favicon code was referenced from the Code Institute.
        4. Masonry code was referenced from the code institute.  

    b.Images

    1. The images used in this website were clicked by the author and hence copyright and ownership resides with the author.


    c.Understanding key concepts.

    1. Basic concepts of flexbox - An excellent guide from Mozilla.org  and can be accessed here: 
    https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox
    2. Controlling ratios of flex items along the main axis- This is the guide I suggest users to read next. 
    https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Controlling_ratios_of_flex_items_along_the_main_axis
    3. A Complete Guide to Flexbox : This is the a ready reference recokner to be kept handy while coding 
    https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    4. Flex Box from Code Institute https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    5. The Box Model Introduction part 2 - https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRR101+2/courseware/b4e5b2c91d0a4ee3bb24fac71811b23f/3ec01463d1ce4d82842b74a5706925d3/
    6. Httml Color Codes : https://html-color.codes/
    7. Looking for a specific device’s viewport size? https://viewportsizer.com/devices/
    8. ULTIMATE GUIDE: EM VS REM VS PX WHICH IS BETTER & WHY? https://www.fhoke.com/em-vs-rem-vs-px/

        






