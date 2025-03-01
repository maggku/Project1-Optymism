# PROJECT1 - OPTYMISM

# Optimism Oveview

Optimism is a cryptocurrency project designed to scale blockchain technology. The first implementation of blockchain technology was introduced with Bitcoin, which brought a decentralized currency that is trustless, transparent, and resistant to manipulation. This groundbreaking idea quickly gained traction among programmers, inspiring the concept of a decentralized internet where data is stored across a network of nodes rather than relying on a centralized server. This decentralized approach promotes fairness and removes single points of control.
The vision of a decentralized internet was first realized by Vitalik Buterin, who created Ethereum—the first blockchain to support decentralized applications (dApps). Optimism aims to scale Ethereum by providing a solution that makes transactions cheaper and faster.
Currently, the Optimism website is complex and challenging to navigate. My goal is to simplify it for better user experience and accessibility.
    

## Who is this for?  
- **Developers**: Building dApps on Ethereum using Layer 2 solutions.  
- **Crypto Enthusiasts/Investors**: Learning about Optimism and exploring investment opportunities.  
- **Existing Projects & DAOs**: Teams evaluating scalable and affordable Ethereum-based solutions.  
- **Researchers/Analysts**: Studying Layer 2 technology and Ethereum scaling.  

## Main Goal  
To provide clear educational content and technical resources, catering to both beginners and developers as crypto concepts are still new to many.  


## Project Description
This project is a modern webpage built with HTML, CSS, and Bootstrap. Initially, the website featured a gradient-styled layout and a **Subscribe Section** where users could input their email addresses to subscribe for updates. To improve usability, I made the website **responsive**, using **Bootstrap components** to make it mobile-friendly and accessible on all screen sizes. The gradient background and subscribe button were removed to simplify the design, and the website was deployed to GitHub Pages.

## UX Development
- **Figma**: The user experience design for this project was created using [Figma](https://www.figma.com/). You can view the design stages, including the prototypes and development process, by following the link below:

[View UX Development on Figma](https://www.figma.com/design/IukzHed7QcjJxfFP36iGhH/OPTYMISM?node-id=3-8&t=jNUKA3Q6i1dhHlS5-1)

This design process helped shape the final implementation and layout of the website.

## Changes Made
- **Responsive Design**: The website was transformed to be fully responsive using Bootstrap components to ensure it works seamlessly across all devices (desktops, tablets, and mobile phones).
- **Removal of Gradient Backgrounds**: I removed the gradient-styled background from various sections of the site to create a cleaner, more modern look.
- **Removal of Subscribe Button**: The subscription form was removed to simplify the site and improve user experience.
- **GitHub Deployment**: The website was deployed to GitHub Pages, allowing users to access it live.

## Final Design Preview
This is the final design as conceptualized in Figma (after the changes were implemented):
![Final Design](assets/images/home-page.png)

## Final Project Screenshots

### New Website (After Updates)
These screenshots show how the website looks after the responsive design updates and simplifications:

#### Homepage-Hero-section (New Version)
![New Version 1](assets/images/hero-section.png)

#### Homepage-Products-section (New Version)
![New Version 2](assets/images/product-section.png)

#### Homepage-Build-section (New Version)
![New Version 3](assets/images/build-section.png)

#### Learn-page-image (New Version)
![New Version 1](assets/images/learn-image.png)

#### Learn-page-content (New Version)
![New Version 1](assets/images/learn-content.png)

#### Build-page-image (New Version)
![New Version 1](assets/images/build-image.png)

#### Products-page-content (New Version)
![New Version 1](assets/images/products-content.png)

## Features
- **Navigation Bar**: A header with a logo on the left and navigation buttons on the right linking to different sections of the Landing Page.
- **Hero Section**: An introduction to the topic with a styled heading and paragraph.
- **Responsive Layout**: The layout is now fully responsive, adjusting to various screen sizes using Bootstrap components.
- **Products Section**: Cards displaying key features or topics.
- **Footer**: A footer with basic information.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling for layout, colors, fonts, and responsiveness.
- **Bootstrap**: For responsiveness and mobile-friendly layout.
- **Google Fonts**: Inter font for clean typography.
- **Box Shadows**: To enhance the design's appeal.
- **GitHub Pages**: Deployment platform for hosting the website live.

## Tools and Methodology
- **Designed in Figma**: This project utilized Figma to design the user interface and generate initial CSS code snippets. Figma’s design-to-code feature was instrumental in creating the layout and visual styles. These generated styles were further customized to fit the specific needs of the project.
- **Bootstrap**: Bootstrap was used to make the design responsive, using its grid system, utility classes, and pre-built components.

## Credits 
- **Optymism Logo**:  Logo OPTYMISM.png
- **Google Fonts**: Inter font for clean typography.
- **Box Shadows and Gradients**: To enhance the design's appeal.
- **Mosh Hamedani**:  This project incorporates code snippets and ideas inspired by the tutorial The Ultimate HTML5 & CSS3 Series: Part 3 by Mosh Hamedani. Mosh's comprehensive explanations and coding best practices significantly helped in structuring and styling this project.
- **Figma**:  This project incorporates svg code snippets from Figma for Ellipse and Triangle images used in Cards.

# File Path Testing

Here are 5 different file paths 

| **Path Example**                                    | **Explanation**                                                       | **Test Result (Pass/Fail)** |
|-----------------------------------------------------|-----------------------------------------------------------------------|----------------------------|
| Clicking a 'learn' link in the navbar               | Directed to the Learn Page                                            | Pass                       |
| Clicking a 'products' link in the navbar            | Directed to the Products Page                                         | Pass                       |
| Clicking a 'build' link in the navbar               | Directed to the Build Page                                            | Pass                       |
| Clicking a 'learn' button in the hero section       | Directed to the learn.html page                                       | Pass                       |
| Clicking a 'products' btn in the products section   | Directed to the build.html page                                       | Pass                       |
| Clicking a 'build' button in the build section      | Directed to the hello.html page                                       | Pass                       |
| Changing the size of the screen on the Home page    | Checking for responsivness                                            | Pass                       |
| Changing the size of the screen on the Learn page   | Checking for responsivness                                            | Pass                       |     
| Changing the size of the screen on the Products page| Checking for responsivness                                            | Pass                       |
| Changing the size of the screen on the Build page   | Checking for responsivness                                            | Pass                       |                  |


---

## Summary of Errors and Fixes

### Errors pointed by a Validator

- **Error 1 Message:**
Error: Bad value assets/images/Logo OPTIMISM.png for attribute src on element img: Illegal character in path segment: space is not allowed.

From line 25, column 9; to line 25, column 71


 - **Error 2 Message:** 
Error: Bad value assets\pages\learn.html for attribute href on element a: Backslash ("\") used as path segment delimiter.

From line 46, column 13; to line 46, column 62
 

 - **Error 3 Message:** 
Error: The element button must not appear as a descendant of the a element.

From line 47, column 15; to line 47, column 45


 - **Error 4 Message:** 
Error: Bad value assets\pages\hello.html for attribute href on element a: Backslash ("\") used as path segment delimiter.

From line 136, column 3; to line 136, column 52



 - **Error 5 Message:** 
Error: The element button must not appear as a descendant of the a element.

From line 137, column 5; to line 137, column 35


- **Error 6 Message:** 
Error: Bad value assets\pages\hello.html for attribute href on element a: Backslash ("\") used as path segment delimiter.

From line 147, column 13; to line 147, column 62
  

- **Error 7 Message:** 
Error: The element button must not appear as a descendant of the a element.

From line 148, column 15; to line 148, column 45

#### Errors- HTML
![New Version 1](assets/images/html-errors.png)

#### HTML Validator (PASS)
![New Version 1](assets/images/html-validator-pass.png)

#### CSS VALIDATOR (PASS)
![New Version 1](assets/images/css-validator.png)




## How to Run
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/maggku/Project1-Optymism.git

## Deployed Version

   - **Deployment**:
   1. Log into GitHub
   2. From the list of repositories on the screen, select **Project1-Optymism**.
   3. From the menu items near the top of the page, select **Settings**.
   4. Scroll down to the **GitHub Pages** section.
   5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**.
   6. On selecting Master Branch the page is automatically refreshed, the website is now deployed.
   7. Scroll bak to the **GitHub Pages** section to retrieve the link to the deployed website.

 
   - **Live Version**: You can view the live website at [GitHub Pages Link](https://maggku.github.io/Project1-Optymism/).



### How to run this project locally

To clone this project from Gitpod you will need:

1. A github account.
2. Use the Chrome browser.

Then follow these steps:

1. Install the Gitpod Browset Extensions for Chrome.
2. After installation, restart the browser.
3. Log into Gitpod with your Gitpod account.
4. Navigate to the [Project GitHub repository](https://maggku.github.io/Project1-Optymism/).
5. Click the green **Gitpod** button in the top right corner of the repository.
6. This will trigger an new Gitpod workspace to be created from the code in GitHub where you can work locally.

To work on the project code within a local IDE such as VSCode:

1. Follow this link to the [Project GitHub repository](https://maggku.github.io/Project1-Optymism/).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTP's section, copy the URL for the repository.
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the clone directory to be made.
6. Type 'git clone', and then paste the URL you copied in step 3.

### Heroku Deployment

1. Create a requirements.txt file using the terminal command pip freeze > requirements.txt.
2. Create a Procfile with the terminal command echo web: python app.py > Procfile.
3. git add and git commit the new requirements and Procfile and then git push the project to GitHub.
4. Create a new app on the Heroku website by clicking the "New" button in your dashboard. Give it a name and set the region to Europe.
5. From the Heroku dashboard of your newly created application, click on Deploy > "Deployment method" and select GitHub.
6. Confirm the linking of the Heroku App to the correct GitHub repository.
7. In the Heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".



  


