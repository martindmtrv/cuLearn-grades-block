# cuLearn-grades-block
Add a custom block to your cuLearn dashboard containing all your grades from all classes in one place. Written using JS and jQuery

# How does it work?
Essentially this customization adds js code into a block on your cuLearn dashboard to add more advanced functionality.
The code makes requests to each of the grades pages for your classes for the current/most recent semester available.

# How to use
1) Open your cuLearn dashboard and click the "Customize this Page" button in the top right corner
2) Open the hamburger menu in the top left of the screen, and click "add a new block"
3) Go to your new block and click the gear icon then click "configure this block"
4) You can title the block however you want, I reccomend "Grades Table"
5) In the content box click the button with a downwards facing arrow on the left side of the toolbar to show more buttons
6) Click the button that looks like < > html tags to edit your block as HTML
7) Paste the following 
        `<script id="GradeScript" src="https://cdn.jsdelivr.net/gh/martindmtrv/cuLearn-grades-block/block.min.js">`
8) Save the changes to your block and profit off saving a couple clicks to see if your class grades have been released yet!
