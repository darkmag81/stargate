 # Stargate World Website

https://darkmag81.github.io/stargate/

## Milestone Project for User Centric Front End Development Module
 *****************************************************************************
 
 ### 1. Project Scope
 
    Stargate is a science fiction media franchise based on the film written by Dean Devlin and Roland Emmerich in 1994.
    The scope the project for is to develop the static front-end website of Stargate World information.   
    The goal of the current website is to familiarise potential user with vasteness of Stargate World. 
    I hope the front-end provides an intuitive and visually appealing overview and encourages users to find out more about
    enormous world of Stargate. It's my intention to continue to buildout this project as the course progresses.


### 2.  Structure

     a. index.html - is the home / landing page.  It contains general information about Stargate franchise.
        Carousel appearing on the main view is showing posters from Movies and TV series. Each graphics is connected to 
        specific Movie/TV Series at movies.html. Note the logo is also a home-button so user's can always go home by clicking
        the Stargate logo. Same layout is continued on every page of this website. Each sub-page has different background picture. 
        The logo and main font used in website is using custom stargate font as well as glyphs used in header and footer.  
   
     b. movies.html - provides a general information about Movies and TV Series as well as main plot for each.
	Every item of this sub-page has its graphics poster and description. Also there is a Back to top button on every item to
	to make it easier for users with small devices to go back to top of the page instead of manually scrolling.
	Each item (Movie/TV series) has its specific ID so the carousel from hompe page re-directs user to proper content of the page.
    
     c. races.html -  provides a quick description of species present in Stargate Universum.
	Similiar to movies.html "back to top" button is present and proper graphics is displayed with every species.  
        It is assumed, that some point later in the course, this page will be modified and extra js functions will be implemented
	to make browsing even more fun for the user.
        
     d. characters.html - provides a short description of main characters and actors. Its divided into three sections to cover 
	main characters from Movies and TV series. Each character description is collapsed to create better user-experience 
	during browsing.
        
    e.  weapons.html - provides a short description of weapons existing in Stargate universum. Similiar to previous sub-page its 
	content is also collapsed for better user-experience. This sub-page will be modified with extra js function in order to
	present more data in even more entertaining level.
       
    f.  scraft.html - provides a short description of Starships existing in Stargate world. Similiar to previous sub-page its 
	content is also collapsed for better user-experience. This sub-page will be modified with extra js function in order to
	present more data in even more entertaining level.    
 
###  3. Design Approach and Code Sources
  	
	I've used several external sources in order to achive current view of the project.
	As first project is based on HTLM and CSS only I tried to achieve as much as possible using only these technologies.
	It's my intention to continue to buildout this project as the course progresses.

    a. Design Phase
    
        I used bootstrap v 3.3.7 for faster and better creating responsive website. Also carousel is acquired from bootstrap
	page. I used fontawesome for small icons in navbar, and also I used Hover.css to make nav buttons transitions.
	Freeware stargate fonts and glyphs have been downloaded from http://www.thescifiworld.net.

    b. Programming 

        As first step, I  created a template which included header with menu bar, logo and footer.
        
        My first task was to modify the top of page to reflect my color preferences and menu content.  
        
        I was following the rule to create header and footer first and then section for each page so to keep all pages look
	similiar.
        
        I used opacity on every page so the background was visible. I've changed font colors and size for the text to be visible.
        
        I've used bootstrap carousele as I thought it was visually pleasing and functional, and it din't require any js script.
        
        The contact page, used code from the resume mini-project.  Care was taken to add the necessary
        CSS elements while not creating referencing conflicts.
        
        At the begining of my project I was hoping to present different way of showing content on each page, however during my
	learning and research I've noticed that most of the visually attractive ways need to use js script. Therefore I had to 
	not use all features I planned such as Tooltips and modals. These and more will be implemented on my future projects.
	
	In the CSS a media query was used to fix small issues with positioning on smaller devices.

	Also during my learining and research I've found that there are better ways to present data such as characters, weapons
	or starcrafts by using database instead of creating each item indvidually. I'm hoping to get back to this project and 
	utilise this knowledge after I progress in the course.
        
        In the CSS a media query was used to fix small issues with positions on smaller devices.

	My first project is created using HTML5 and CSS3 (with bootstrap) only. My general idea was to show absolute
	control of any element on my page and to create website which is visually pleasing, attractive, aesthetic and
	responsive.
        
   ### 4.  Deployment
    
        The deployment of the project relies soley on the Cloud9 platform.  At this point, it is not
        deployed to any live webserver.  
        
        Note that project from time-to-time was backed up locally using git. 
	In order to faciliate an initial review, the project was added to github at 
        https://darkmag81.github.io/stargate/index.html and will continue to be udpated on the site.
        
   ### 5.  Testing
    
        My current test enviroment consists of:
        
            MSI GE62VR Apache Pro laptop with OS Windows 10, Chrome 66.0.3359.139 (Official Build) (64-bit),
            Firefox Quantum v 59.0.1 (64-bit), Microsoft Edge 41.16299.371.0
            
            Samsung Galaxy s6 Edge with OS 7.0, Chrome v 66.0.3359, Samsung Internet v 6.4.10.5

        To test the site I used the following procedure:
        
            a.  I developed the site on my Laptop using Chrome browser.
                First, I examined the site in desktop mode, to view the look and feel and verify
                all links.
  
            b.  I tested the smaller screen on my Samsung smartphone.
		To diagnose issue on the small screen, I used Chrome developers tool.
            
            c.  I used Chrome Developer tools to check website responsivness on different devices.
        
    
    
  
 ********************************************************
 
 # Major Change Log
   
 ## May 3, 2018 Update

    uploaded the README.md
 
 # Test Log
 
     The test log is being added for the benefit of my Code Institute indstructors
     so that they can verify my testing methodology / process
 
 
   ##   Initial Review
   
        Tested on Windows 10 computer Google Chrome
        for look and feel   Examined margins and flow
        
	tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested section on each page - passed
        
        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            movies page     - horizontal  Passed   , Veritical  Passed
            races page      - horizontal  Passed   , Veritical  Passed
            characters page - horizontal  Passed   , Veritical  Passed
            weapons page    - horizontal  Passed   , Veritical  Passed
            scraft page     - horizontal  Passed   , Veritical  Passed
            
        Tested on Windows 10 computer MS Edge
             for look and feel   Examined margins and flow
        
	tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested section on each page - passed
        
        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            movies page     - horizontal  Passed   , Veritical  Passed
            races page      - horizontal  Passed   , Veritical  Passed
            characters page - horizontal  Passed   , Veritical  Passed
            weapons page    - horizontal  Passed   , Veritical  Passed
            scraft page     - horizontal  Passed   , Veritical  Passed
   
       Tested on Windows 10 computer Firefox
            for look and feel   Examined margins and flow
        
	tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested section on each page - passed
        
        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            movies page     - horizontal  Passed   , Veritical  Passed
            races page      - horizontal  Passed   , Veritical  Passed
            characters page - horizontal  Passed   , Veritical  Passed
            weapons page    - horizontal  Passed   , Veritical  Passed
            scraft page     - horizontal  Passed   , Veritical  Passed
   
        Tested on Samsung Galaxy Chrome
        for look and feel   Examined margins and flow
        
	tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested section on each page - passed
        
        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            movies page     - horizontal  Passed   , Veritical  Passed
            races page      - horizontal  Passed   , Veritical  Passed
            characters page - horizontal  Passed   , Veritical  Passed
            weapons page    - horizontal  Passed   , Veritical  Passed
            scraft page     - horizontal  Passed   , Veritical  Passed
   
        Tested on Samsung Galaxy Samsung Internet
        for look and feel   Examined margins and flow
        
	tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested section on each page - passed
        
        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            movies page     - horizontal  Passed   , Veritical  Passed
            races page      - horizontal  Passed   , Veritical  Passed
            characters page - horizontal  Passed   , Veritical  Passed
            weapons page    - horizontal  Passed   , Veritical  Passed
            scraft page     - horizontal  Passed   , Veritical  Passed
