# What everything in the source folder does. 
 - doc folder: contains all the proper documentation
 - img folder: contains all the image elements
 - js folder: contains all the javascript code
 - .editorconfig: will be able to change the styling of how the website will utilize spacing
-	.gitattributes: attributes that will be used for web projects
-	.gitignore: a file that will be ignored by github
-	404.html: a general 404 error splash page to displace unknown landing pages
-	broswerconfig.xml: will configure the size of the title.png size based on the browser
-	favicon.ico: the favicon image of the website
-	humans.txt: a document highlighting an ordered style of who the contributor are.
-	icon.png: an icon sized image that is used on the website
-	index.html: the general splash page of the website
-	robots.txt: is a resource the website uses to make sure robots are not spamming login entries 
-	site.webmanifest: makes sure the the image loaded is coming from icon and sets the background and theme color
-	title-wide.png: contains a wider same image of title.png
-	title.png: contains an image of the title

#	Line by line Analysis of index.html | Documentation displayed via C++ inline comment style (//)
```html
<!doctype html> // Will notify the browser that this is an html file.
 <html class="no-js" lang=""> // Creates a class called no-javascript.
 <head> // creates a head tag.
  <meta charset="utf-8">  // will be explained in it's own section.
  <meta http-equiv="x-ua-compatible" content="ie=edge"> // will adjust the content compatibility to microsoft edge
  <title></title> // creates a title tag
  <meta name="description" content="">
  <meta name="viewport" content="width=device-width, initial-scale=1"> // will adjust the viewpoint based on the device's display

  <link rel="manifest" href="site.webmanifest"> // a site link to the webmanifest in source
  <link rel="apple-touch-icon" href="icon.png"> // A link to the apple's touch icon for a mobile ios device
  <!-- Place favicon.ico in the root directory -->

  <link rel="stylesheet" href="css/normalize.css"> // a css style reference to normal
  <link rel="stylesheet" href="css/main.css"> // a css style reference to main
</head> // the end of the head tag

<body> // the beginning of the body tag
  <!--[if lte IE 9]> // a version checking error to that will display if a browser is outdated
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
  <![endif]-->

  <!-- Add your site or application content here -->
  <p>Hello world! This is HTML5 Boilerplate.</p> // a paragraph with a HTML5 boilerplate text
  <script src="js/vendor/modernizr-{{MODERNIZR_VERSION}}.min.js"></script> // a script that will be able to use modernized periphials tied to certain devices
  <script src="https://code.jquery.com/jquery-{{JQUERY_VERSION}}.min.js" integrity="{{JQUERY_SRI_HASH}}" crossorigin="anonymous"></script> // will check a jquery hash
  <script>window.jQuery || document.write('<script src="js/vendor/jquery-{{JQUERY_VERSION}}.min.js"><\/script>')</script> // will write to the jquery 
  <script src="js/plugins.js"></script> // a script that will load plugins
  <script src="js/main.js"></script> // a script that will load main

  <!-- Google Analytics: change UA-XXXXX-Y to be your site's ID. -->
  <script>
    window.ga = function () { ga.q.push(arguments) }; ga.q = []; ga.l = +new Date;
    ga('create', 'UA-XXXXX-Y', 'auto'); ga('send', 'pageview') // a script that will set a function to google analytics to process data
  </script>
  <script src="https://www.google-analytics.com/analytics.js" async defer></script> // a page that will periodically sync and send the source to where the data will be collected
</body> // the end of the body tag
 
</html> // the end of the html tag
```
# UTF-8
- UTF-8 is a character code standard that was the successor to ASCII. UTF or otherwise known as Unicode, is a character format that can assess how certain characters can be transformed into an 8bit notation. For example, in Unicode the English letter 'A' is associated with 65 in binary. This type of format can be used in translating letters into bits from any language with an alphabet. 
# Timeline of the Internet
- 1957 - ARPA: Created by the US with a purpose of researching new sciences and technologies.
- 1962 - J.C.R Licklider: Proposes for a global network of computers.
- 1965 - MIT: Two computers at MIT Lincoln Lab communicate with one another using packet-switching technology.
- 1969 - ARPANET: The US Depeartment of Defense funds the Advanced Research Projects Agency Network or ARPANET.
- 1972 - Network Control Program: The Transmission Control Protocol is introduced as a way for ARPANET computers to communicate with one another.
- 1974 - ISP: The first Internet Service Provider (ISP) is born with the introduction of a commercial version of ARPANET, known as Telenet.
- 1982 - TCP: Transmission Control Protocol (TCP) and Internet Protocol (IP), as the protocol suite, commonly known as TCP/IP, emerge as the protocol for ARPANET.
- 1983 - DNS: The Domain Name System (DNS) establishes the familiar .edu, .gov, .com, .mil, .org, .net, and .int system for naming websites. 
- 1986 - Craig Partridge: designs how email is routed using domain names.
- 1987 - The Hitchhiker’s Guide to the Internet is Published
- 1989 - The World wide web: invented by Sir Timothy John "Tim" Berners-Lee, an engineer and computer scientist from Great Britin, working as a professor at MIT and CERN Laboratory.
- 1991 - CERN: introduces the World Wide Web to the public.
- 1994 - Netscape: Netscape Communications is born. Microsoft creates a Web browser for Windows 95.
- 1998 - ICANN: Internet Corporation for Assigned Names and Numbers (ICANN) was formed.
- 1999 - AOL buys Netscape.
- 2000 - Websites like Yahoo and eBay are hit by service attacks. Shows that internet is very vulnerable and easy to attack. AOL merges with Time Warner.
- 2001 - Judge shuts down Napster. Must find a way for users to stop sharing copyrighted information. 
- 2003 - Platform WordPress is launched. 
- 2004 - Facebook launches, social networking begins. Mozilla launches new web browzer, Mozilla Firefox. 

[Read.me file](https://github.com/lilberrones/boilerproject/blob/master/README.md)

![alt_text](images/remotes.PNG)

# (Tutorial) How to make a collaborative project on Git

1) Have your team set up their own individual github accounts.
![alt_text](images/step1.PNG)
2) Designate someone as the team leader of the project.

3) Instruct the team leader to create a repository on github, once created the leader will invite the other members to have collaborative access to the repo.
![alt_text](images/step2.PNG)
![alt_text](images/step3.PNG)
4) Have the other team members clone this newly created repository to WebStorm.
![alt_text](images/step4.PNG)
5) Once WebStorm is opened for each member, they will create their own individual member branch to conduct work from.
![alt_text](images/step5.PNG)
6) This process will ensure each member will be properly able post and share each other's work.

7) In order for someone to save their work, they will need to do a process called a commit, which is a report to the vcs that there will be an incoming change to the repository.
![alt_text](images/step6.PNG)
8) To do this you will need to go into the vcs menu and click commit, once the menu opens you will
  report what the change is in the form of task: added something , fixed: spelling errors, or feature: made something easier to read.  
9) Once your changes are committed, you will push the changes the final changes via the vcs menu.
![alt_text](images/step9.PNG)
10) Your partners will then pull the changes from the branch that were previously worked on.
![alt_text](images/step10.PNG)
11) After it was determined that the changes are sufficient, you will need to combine the changes into the master branch, aka merge.

12) In order to complete a Merge, you would need to go to the branch you would want merge, from there you must move your mouse cursor to the bottom right and click on the branch and select the option called "merge into current".
![alt_text](images/step11.png)

# Term Definitions

Git: a version-control system for tracking changes in source code during the stages of software/web development.

GitHub: a web hosting service that operates under the version control system called Git.

Repository: a location where central data is stored and managed.

Clone: a command in Git used to copy an existing repository into another.

Commit: a call to a repository stating that there will be an incoming change being reported to the repository.

Push: a command used to upload changes to a repository.

Pull: a command used to download changes from a repository.

Branch: a movable/editable copy of a master.

Merge: the process of combining and integrating changes into master source code.

Merge Conflict: the idea that certain elements of a merge can not be executed due to there being already existing unaccounted change.

Fetch: a command used to download commits, files, and references from a remote repository into a local repo.

Remote: the idea of splitting an already existing repository to different locations to be accessed by different people at the same time.

