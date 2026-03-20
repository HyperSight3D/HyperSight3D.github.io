# HyperSight 3D Perception Lab - School of Software, Dalian University of Technology GitHub Page

## Project Introduction

This is the GitHub homepage for HyperSight 3D Perception Lab at the School of Software, Dalian University of Technology. It is used to showcase the team's research directions, member information, published papers, and other content.

## Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles file
├── script.js           # JavaScript file
├── images/             # Images directory
│   ├── dlut.jpg        # Dalian University of Technology image
│   ├── zhongwei.jpg    # Professor Wei Zhong's photo
│   ├── weihenglu.jpg   # Associate Professor Henglu Wei's photo
└── README.md           # Documentation file
```

## How to Use

1. **Clone the Repository**: Clone the project to your local machine or deploy it to GitHub Pages

2. **Local Preview**: Open the `index.html` file in a browser to view the website

3. **Deploy to GitHub Pages**:
   - Push the project to a GitHub repository
   - Enable GitHub Pages in the repository settings
   - Select the `main` branch as the source

## How to Modify Content

### 1. Modify Basic Information

Open the `index.html` file and modify the following content:

- Website title: `<title>HyperSight 3D Perception Lab - School of Software, Dalian University of Technology</title>`
- Navigation brand: `<a href="#">PHyperSight 3D Perception Lab</a>`
- Hero section title: `<h1>HyperSight 3D Perception Lab</h1>` and `<p>School of Software, Dalian University of Technology</p>`
- Footer information: `<h3>HyperSight 3D Perception Lab</h3>` and `<p>School of Software, Dalian University of Technology</p>`

### 2. Modify About Us

In the `index.html` file, find the `<section id="about">` section and modify the following content:

- Team introduction text
- Dalian University of Technology image: Replace `images/dlut.jpg` with an actual image

### 3. Modify Research Areas

In the `index.html` file, find the `<section id="research">` section and modify the following content:

- Research area cards: You can add, delete, or modify research directions
- Each card contains an icon, title, and description

### 4. Modify Team Members

In the `index.html` file, find the `<section id="members">` section and modify the following content:

- Team member cards: You can add, delete, or modify member information
- Each card contains an image, name, position, and contact links
- Replace the images in the `images/` directory with actual member photos

### 5. Modify Publications

In the `index.html` file, find the `<section id="publications">` section and modify the following content:

- Paper list: You can add, delete, or modify paper information
- Each paper item contains a title, authors, journal/conference information, and a view details link

### 6. Modify Contact Information

In the `index.html` file, find the `<section id="contact">` section and modify the following content:

- Contact information: Address, email, phone number
- Form submission function: By default, it's a simulated submission, which can be modified to actual backend processing if needed

### 7. Modify Styles

Open the `styles.css` file and you can modify the following content:

- Color scheme: Modify variables like `--primary-color`
- Fonts: Modify the `font-family` property
- Layout: Adjust responsive design parameters
- Animation effects: Modify transition and animation properties

### 8. Modify Interactive Functions

Open the `script.js` file and you can modify the following content:

- Smooth scrolling effect
- Navigation bar scrolling effect
- Form validation logic
- Animation trigger conditions

## Add New Content

### Add New Research Areas

In the `<section id="research">` section of the `index.html` file, add a new research card:

```html
<div class="research-card">
    <div class="card-icon">
        <i class="fa fa-icon"></i> <!-- Replace with appropriate icon -->
    </div>
    <h3>Research Area Name</h3>
    <p>Research area description</p>
</div>
```

### Add New Team Members

In the `<section id="members">` section of the `index.html` file, add a new member card:

```html
<div class="member-card">
    <div class="member-image">
        <img src="images/member4.jpg" alt="Member Name"> <!-- Add new image -->
    </div>
    <h3>Member Name</h3>
    <p>Position</p>
    <div class="member-links">
        <a href="#"><i class="fa fa-envelope"></i></a>
        <a href="#"><i class="fa fa-google"></i></a>
    </div>
</div>
```

### Add New Papers

In the `<section id="publications">` section of the `index.html` file, add a new paper item:

```html
<div class="publication-item">
    <h3>Paper Title</h3>
    <p>Author 1, Author 2, Wei Zhong</p>
    <p>Journal Name, Volume, Pages, Year</p>
    <a href="#" class="btn small">View Details</a>
</div>
```

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Font Awesome icon library

## Responsive Design

The website uses responsive design to adapt to different screen sizes:

- Desktop: Full layout
- Tablet: Adjusted to two-column layout
- Mobile: Adjusted to single-column layout, navigation bar becomes vertical

## Customization Suggestions

1. **Add Actual Images**: Replace the placeholder images in the `images/` directory with actual photos
2. **Update Contact Information**: Modify to real email and phone number
3. **Add More Content**: Add more research directions, members, and papers according to the team's actual situation
4. **Integrate GitHub Repository**: Add links to the team's GitHub repositories in the footer
5. **Add News Section**: Consider adding a news section to showcase the team's latest activities

## License

This project is licensed under the MIT License. See the LICENSE file for details.