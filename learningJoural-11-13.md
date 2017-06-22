Ref. http://htmlandcssbook.com/

Here's what I learned, thus far...

  **Ref. Course Books:

    "HTML & CSS: Designing and Building Web Sites," by Jon Ducket
    "JavaScript & jQuery: Interactive Front-End Development," by Jon Ducket

                      - ISBN-13: 978-1118907443
                      - ISBN-10: 1118907442

            - ~/supercodingninja/HTML and CSS design and build websites.pdf
            - ~/supercodingninja/javascript.pdf

  The more simple you can keep your CSS, the better it is; and remember to Control Flow.**

***Week 3***
Code 201: Day 1 (DAY 11)
  **Think about project**
- Learn to manage your stress; especially in projects with team members.
- it's vey easy to look at someone else code, and see what is broke; but it's very difficult to see what's wrong with your code: because we, as developers, see what we want to get out of our code vs. what the user sees and experience: WE WANT TO PUT OURSELVES, AS MUCH AS POSSIBLE, IN THE USERS'S SHOES.
**You can now do video in HTML5**
  *Where we get the parameters (pixels) for css:
  - screens sizes use to be 640 x 480 (4:# aspect ratio)
  - as we got into the era of bigger monitors (15"+), the screen sizes just got bigger (1024 x 768: still 4:3 ratio)
  - now, more screens are built wider (16:9 ratio)
  **A very, common width approach is 960px (smaller on big screens)
  - 12 colummn grid  https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=0ahUKEwjxkc_0rsrUAhVP9mMKHVa9D7gQjRwIBw&url=https%3A%2F%2Fincrediblogger.net%2F960-grid-system-explained-depth%2F&psig=AFQjCNGd3WEcfUku7vAfzFxokOOXyQABxg&ust=1497977329986542

  -When you're building out a  css, you want to start out with all of the global, first.

**Practice Wire Frame**
- build from the ground up
- plan ahead
- it takes discipline not to try make everything pretty.
  **Absteaction (UI/UX)**
  0101100101---> when voltage transpires---->3a f2 96 bc (processor language)---->Low-level languages (C, Java, C++)----->High Level Languages (JS, Python, etc.)____>Interface (HTML, CSS, JS)---->Interface for the Users (DON'T BUIL WANT YOU WANT: BUILD WHAT THEY WANT).

  **Events**

  ***Ch. 19 in the JS book, is practical information you want to know, when it comes to freelancing; and making money.***
  - SEO pg. 479
  - Analytics pg. 483
  - Domain names and hosting pg. 487
  - FTP + tools pg. 489

***HTML CH. 9 AND 16***
- video
- css material

***PLAN YOUR WORK; AND WORK YOUR PLAN***
  **BUS MALL LAB**
  - Backstory:
    1. Employed by BusMall (startup)
    2. Product is similar to
    SkyMall Catalog
    3. Tracking popularity of items

  - Problem Domain:
    1. Build app that displays potential products to individuals in focus groups:
      a. Three products at a time, side-by-side-by-side
      b. Need to manage the size and the aspect ratio of the images (maybe edit them):
        i. Need to manage the size and the aspect ratio of the images
        ii. Lots of online tools
    2. Purpose is to have the group members choose which product, of the three displayed images, that they would be most likely to purchase, and then store, calculate, and visually display the resulting data:
      a. Keep the product selection process as untainted as possible
      b. Do not allow any results to be shown to users until there have been a total of 25 selections made
    3. Marketing team is not only interested in:
      a. Total number of clicks for each item, when it was shown
      b. The percentage of times that an item was clicked, when it was shown:
        i. Keep track of how many times each image is displayed
        ii. Do the calculations
    4. Responsible for the look and feel of the app:
      a. Custom font
      b. Color palette
      c. Layout with semantic HTML

  - User Stories:
    *1. Write your own user stories:
      a. Try to write 4-5 user stories for each role (DO THIS STEP FIRST)
        i. In a file called user_stories.md
        ii. The commit logs in your repo will have a first couple of commits for the scaffolding process
        iii. Next you should have a 'user stories' commit that is in place before any code is written.
      b. Consider the multiple roles involved:
        i. The marketing research team
        ii. The developer
        iii. The focus group participant (who will be using the application)
    2. Take about 30-45 minutes to work on the user stories (A wise student would)
    3. Draft a technical plan for the project:
      a. A detailed to-do list of things to make, step by step and tested at each stage, before getting into the code
      b. That time spent in thought and planning will make the code flow a lot faster
      c. Give yourself a series of little problems to solve (rather an a ginormous thing that you just wade through and poke at):*
        i. Set 'em up, and knock 'em down
      **ii. Plan your work, and work your plan**

  - Goals to complete by the start of class Tuesday morning:
    **Note: There's a lot of moving pieces in this assignment, and more details to attend to than it might seem at first. Build methodically, in small pieces, that you test and check regularly. ACP regularly on at least one non-master branch. Try sketching out a plan on paper and breaking down the problem conceptually before getting into the code.**
    1. Create a new repo for this weekly project called bus-mall at the root level of your ~/CF/201 directory.
    2. Scaffold your repo with:
      a. The usual README
      b. CSS
      c. JS
      d. HTML files
      e. Plus a img/ directory.
    3. Retrieve the assets from the assets/ directory in the week-03 directory of our class repo and place them in your image directory.
   *4. Write your user stories as described above and place them in a file called user-stories.md in your repo. Utilize good Markdown style to make this document look nice.*
    5. The thing you want to build today will select three random photos from the image directory and display them side-by-side-by-side in the browser window.
    6. In addition, you'll want to be able to receive clicks on those displayed images, and track those clicks for each image. You'll also want to track how many times each image is displayed, for statistical purposes.
    7. Upon receiving a click, three new non-duplicating random images need to be automatically displayed. In other words, the three images that are displayed should contain no duplicates, nor should they duplicate with any images that we displayed immediately before.
    8. To do this, you'll want a constructor function that creates an object associated with each image, and has (at a minimum) properties for the name of the image (to be used for display purposes), its file path, the number of times it has been shown, and the number of times it has been clicked. You'll probably find it useful to create a property that contains a text string you can use as an ID in HTML.
    9. After 25 selections have been made, turn off the event listeners on the images (to prevent additional voting) and also display a list of the products with votes received with each list item looking like "3 votes for the Banana Slicer".
  **10. Remember to submit a link to your most recent PR following the instructions in Canvas.**

  *Code 201: Day 1 (DAY 12)*
  Based on peer code review, I also needed:

  var totalClicks = 0
  var option = []
  var newOption

  I was right about my original thought: new Option('', '', '').  I was also correct with my original thought of utilizing a for loop.  I forgot to put a function for my totalCalculations.  When calculating conversions, make sure you do not allow it to divide by 0: Infinity.

  You can pass an array in a value; and check an array.  Austin did a great job by this: he had an checkQ(value, value); where he made it check for an value in array, by True of False.  You can also do this by a built in function in JS by numbers.indexOf(index value); ex. numbers.indexOf(7);

  I should have also use something like what Austin used prodLast = prodNew to reassign pictures.

  **The 2 hardest things about programming**
  1. Naming
  2. Cache


  Probably wouldn't do:

  <!-- for loop
    if
      while
        if
          while
            else -->

  I want to have the following variables (unsure if I want this many Global Variables: because there are already a lot of Global Variables built in; and when working with people, there may be a whole lot of teams with JS, and naming conflicts can emerge.):
  1. clickTotal
  2. option
  3. lastOption
  4. newOption
  5. Options
  6. getOption
  7. render
  8. clickEvent (for the event listener)

**Library: ChartJS**
- use this for Canvas.
    *Libraries*
    - a bunch of code someone wrote; and made available.
    - use them to enhance the functionality of an app.

    *Frameworks*
    - a bunch of code someone wrote; and made available.
    - we take our content; and out it in the frameworks structure.

    *EXAMPLES OF LIBRARIES*
    - ChartJS
    - JQuery

    I connected with Evert Timberg on LinkedIn (he is a second conection of mine, aleady)

    "Hello, Sir.

I attend Code Fellows (www.codefellows.org; Seattle location); and we learned about chart.js, today.  I would like to personally thank you for your contributions, Sir.  It is truly amazing, and motivating!  Please feel free to let me know if I can assist you in any way.
+1 253 279 7213

***Ultimately, you're going to get hired by what you do; and not what you say; or what certifications you had***

*Code 201: Day 1 (DAY 13)*
- Get Chart.js fomula "Data sett...Data set..."
- define depth, width, and structure {how we organize our data structure}
**Helpful Sites**
- https://erty.me/access/ ("Access Practice")
- https://pokeapi.co/ ("Pokéapi
The RESTful Pokémon API

Over 186,167,800 API calls received!")

- GET SAM HAMM, PHD BLOG ON WEB BROWSER.
- DEINE JSON {local storage}
**Local Storage**
- First, you have some data that you want to store.
- So first, you'll do: JSON.stringify(data)
- the, localStorage.setItem('key', stringifiedData)
- then localStorage.key = stringifiedData
- Stored
- Retrieved
- do Reverse for...save...and save for...
- Before you store data, you must stringify it; and before you Parse it...

**Local Storage and Caching Data**
- Cache = stored(duplicate) of data
- When do we actually need/use local storage in our code:
  1. Store (when do you want to store data: event listeners, etc.)
    *note* every time you store data, you overwrite the pre-existing data: store data every time...
  2. Retrieve (on page load)

**Local Storage and BusMall**
-Why use local storage with BusMall: keep up with voting results of multiple focus group subjects, so that when we render the chart, it shows totals for All users.
- on page load, what you're going to need is some kind of if statement; i.e.

    if(local storage exists) {
      retrieve and Parse
      assign to allProducts = []
      } else{
        make instances from constructor *Be careful not to overwrite*
        display...
      }
    }

  **Cool Links**
  - projects.seattle.com [entire project in GitHub]
  - Butterwick's Typography
