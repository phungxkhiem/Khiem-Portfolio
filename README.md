# Khiem-Portfolio
In this challenge, we were tasked with a list of acceptance criteria (featured below this section) that would allow/guide us to making the first version of our portfolio page.

* We would use HTML and Responsive CSS criteria
* Create a unique design showcasing blocks to put our biography and future class work
* Layout will shift depending on the size of the window it's being viewed from
* Navigation takes you to different pages or components within the same page

# Acceptance Criteria
```GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

# styles.css
```header {
    display: flex;
    justify-content: space-between;
    padding: 1%;
    background-color: rgb(47, 76, 142);
    border: 2px solid black;
}
body {
    background-image: linear-gradient(lightgray, lightgreen, lightblue, pink);
  }
nav ul {
    display: flex;
    justify-content: space-between;
}

nav a {
    font-size: 25px;
    font-weight: bold;
}

.image {
    padding: 1%;
    border: 2px solid black;
    width: 250px;
    text-align: center;
    margin: auto;
}

.profile-pic {
    width: 250px;
    align-items: center;
}


.intro-column {
    padding: 1%;
    border: 2px solid black;
}
.skills-column {
    padding: 1%;
    border: 2px solid black;
}
.main-text {
    padding: 1%;
    border: 2px solid black;
}
.contact-edit {
    padding: 1%;
    border: 2px solid black;
}
```