
##System Design
The most current version of FreeFood4Terp relies mainly on the home page and supports navigation to two additional HTML files. These include an expanded list of events as well as a page with more details regarding individual events. Across all pages of the website, the user will be able to find and make use of a search bar in the upper right hand corner. The frontmost component of our website features a list of today’s top three events accompanied by a short description of each. The user has the ability to select one of the these featured events, which will load a page providing more details, or they may navigate to a list of all events by selecting “see more” below the top three events. An individual event’s page contains specifics such as a title, description, food type, event time, promo code, and the location. Directly to the right of the top events, there is a calendar which allow users to see what events are occuring on different dates. Below today’s events, we have included a map of the University of Maryland. Finally, at the bottom of the home page, a form has been included in order to allow both students and organizations to share events to the website. Users have the ability to navigate between the different pages by making use of the “back to more events” option.

##File Structure
FreeFood4Terp is broken down into the following folders. The files are split in this format to make it easily accessible.

  Project Folder - All the html files such as the homepage, events list, and detailed event page, along with images, CSS, and scripts folders
  Images Folder - All the images used in the site
  CSS Folder - All the CSS code use to style the web pages
  Scripts Folder -  All the JavaScript, HTC files
  Docs Folder - Markdown (MD) files of documentation including the user manual, developer’s manual
  README - A short document explaining what is contained in the repository

##Software
FreeFood4Terp primarily relies on third-party software applications in order to be able to alter the appearance and implement functionality to the website. Editors such as Atom, Microsoft Visual Code, Notepad++ were all used to alter the HTML & CSS of the platform. Web browsers, Microsoft Visual and other IDEs were utilized for code execution and testing purposes.  

##Library
FreeFood4Terp relies on JavaScript libraries such as jQuery and tuiCalendar.  jQuery is a JavaScript library designed to simplify HTML DOM tree traversal and manipulation, as well as event handling, CSS animation, and Ajax. tuiCalendar is a JavaScript schedule calendar that enables customizable calendar. OpenLayers is an open-source JavaScript library that we tried to use to display map data in web browsers as slippy maps. For future developers, more libraries may be needed to finalize our system.

##System Environment
FreeFood4Terp is presently hosted on Netlify, a cloud computing company which hosts static websites.  

##Database
Presently, there are no implementations of the database. However, future developers who will take over our system will have the opportunity to collect user-submitted data regarding the events that will be displayed on the website. The three main databases that should be implemented include an event database, a location database, and a user database. The event database should include an event id, title, description, food type, promo code, event time, as well as the location. The location database should include a unique number as a location id for each event’s location, name of the location, and an address of the event to locate it on the map. Finally, the user database should contain a user id, user location to locate how far the user is from the event, and user information to allow users to share and/or save events they are interested in.
