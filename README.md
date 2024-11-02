# the-paragraph
A blog website. Implemented using: HTML, CSS, JS, EJS, Mongo DB, Express and NodeJS

## How I maneouvered
### 1. Make a blog website using html and css.
(Ensure it has a create page)\
I had made a blog website using html and css a few years back. But I didn't connect it to a database. To put my CRUD skills to the test, I decided to add a database to the said website I made in 2022. In short, I already had the html and css. All I added was a create page to enable me or a user to create a post. 


### 2. Create an EJS folder
Earlier this year, I had tried to integrate EJS into the project, but I seemingly didn't have enough knowledge. Initially, I had installed ejs but I was implementing it in an app.js folder. This didn't work because "main" in the package.json is normally set to "index.js". I also didn't have a "views" folder, "pages" and "partials" subfolder. In addition, I had not set up my express server! So this is how I got it to work:

a. npm i ejs\
b. in index.js, set up an express server\
here you will eventually:

- require ejs\
- set the view engine to ejs\
app.set('view engine', 'ejs');\
-res.render one of your ejs pages\

c. create a views folder\
under it create a pages sub-folder and a partials-subfolder\
d. create your ejs files\
your ejs files are based on your html.\
e.cut and paste the header of your website into patials/header.ejs; footer into partials/footer.ejs and so on.\
f. you can test whether ejs is working by following one of the many ejs tutorials on the internet\
just try to ensure a const in index.ejs is being displayed on your browser\
g. further testing will be done once you implement mongodb in your project\
h. create a public folder\
It is important to note that at this point -when you're testing- your css won't be reflected.\
This is where the public folder comes in.\
Cut your css file from wherever it is and paste it into the public folder.\
in your header.ejs, adjust the link to be *relative by adding a foward slash at its beginning\
At this point when you test your html and css should display just fine. \

(To be continued)





