# Hotbeans-Web-Development-Website
## Unit 15 Assignment 2 - Develop a website for a company

### Contents
- [Introduction](#introduction)
- [Design Documentation](#design-documentation)
- [Development Justifications](#development-justification)
- [Testing Documentation](#testing-documentation)
- [Evaluation and improvements](#evaluation-and-improvements)


# Introduction

This readme will contain the documentation for my website HotBeansWeb. I will show my webpage designs, justify them, test my website and make optimisations based on feedback given to me.

# Design Documentation

### Client requirements analysis

HotBeansWeb wants to create a new section on their website aimed at recruiting more web developers. This section will cater to individuals who have completed web development training or qualifications and are looking for an industry job. The specific requirements for this website are as follows:

1. Profile of the company
 - This will require a detailed description of the company, including its mission, vision and work culture. This section should highlight what makes Hot Beans Web a good employer to work for.
2. Testimonials from current trainee developers
 - Showcasing profiles of current trainee web developers, their skills, experiences and how they have grown within the company will help prospective applicants relate to existing employees and understand the growth opportunities at HotbBeansWeb.
3. Job specifications and required qualifications
 - Provide a clear list of job roles and responsibilities, including specific qualifications and skills required to join the company. This will help potential applicants assess their eligibility and understand what the comoany expects from their developers.
4. Online application form
 - Have a simple and user-friendly form where applicants can submit their resumes, portfolios and any additional information relevant to their application.
5. Links to web development courses
 - Provide external resources and links to online courses or certifications that can help potential applicants enhance their skills and increase their chances of getting hired.

### Plan to meet the requirements

1. Company Profile
- **Content Gathering:** Gather relevant information about HotBeansWeb (history, values, culture and current focus etc.)

- **Design:** This section of the website would have a clean layout, with an image of the office or the team and concise text about the company's history, mission statement and company vision.
  
2. Profiles of trainee web developers
- **Content Gathering:** Reach out to trainee web developers to gather details and stories about them - could include short bio, educational background, skills and their growth journey within the company.
  
- **Design:** A simple grid or card-style layout to display each profile, with images and descriptions.

3. Job Specifications and Required Qualifications
- **Content:** Based on the roles available at HotBeansWeb, I will create a detailed list of job specifications, including skills (technical and soft skills), experience, and educational qualifications required.

- **Design:** A clear, easy to read list format will be used, with tags to categorise each job role so they can be filtered.

4. Online application form
- **Content:** I will create a clean, user-friendly online application form. It should include fields for:
   - Personal Information (Name, contact details etc.)
   - Education/Qualifications
   - Portfolio link
   - Resume upload field
   - Cover letter section

- **Validation:** I'll implement form validation to ensure that users submit complete and accurate information.

5. Links to web development courses
- **Content Gathering:** I'll research reputable platforms that offer web development courses (such as Coursera, CodeAcademy etc.) and gather information on specific courses that align with the skills that HotBeansWeb is looking for.
   
- **Design:** Each course would have it's own card with a brief overview of what the course teaches, and a redirect link that takes you to the course to learn about in more detail.

Before coding the website, I needed to know what my webpages will look like. Here are the wireframes and mockups I have designed:

### Wireframe

The wireframe acts as a framework of the website, where I can focus on webapge structure and functionality as opposed to colours and the overall style of the website.

![Hot-beans-wireframes-drawio.png](https://i.postimg.cc/Yqyhh7sh/Hot-beans-wireframes-drawio.png)

### Mockups

The mockups are built to look like the website in it's final form - in a static, high quality image. The mockups help to visualise the final design before coding begins.

[![web-design-mockups.png](https://i.postimg.cc/Bbf7sRx6/web-design-mockups.png)](https://postimg.cc/gX4HHStF)

### Flow Diagram

I have also designed a flow diagram that dictates how users will traverse the webpage.

[![sitemap.png](https://i.postimg.cc/TP1tJD8q/sitemap-v2.png)](https://postimg.cc/zLmwJ3GV)

### Colour schemes and Typography

I opted to use the colours from the logo to come up with an appropriate colour scheme, this was done to maintain brand identity. The same colour palette is used throughout the website for a unified look.
I also decided to use gradients like the one in the logo to add some flair to the website and on the interactive elements so that they stand out to the users and have a direct call to action. 

| Logo   | Colour Palette |
|--------|--------|
| [![logo.png](https://i.postimg.cc/HkVbBJ9T/logo.png)](https://postimg.cc/TKvyP3ss) | [![Hot-Beans-Colour-Palette.png](https://i.postimg.cc/9FPkCn6D/Hot-Beans-Colour-Palette.png)](https://postimg.cc/crHhcX4W) |

### Design Feeback

After contacting colleagues to look over my design, they informed one big improvement I could make:

**"The only issue I have is that the select colour scheme is conflicting. The use of blue does not blend with the colour of the logo. I recommended revising the colour palette you are planning to use to keep your website looking fresh and professional."**

[![hotbeans-web-feedback-screenshot.png](https://i.postimg.cc/s2VX4zBD/hotbeans-web-feedback-screenshot.png)](https://postimg.cc/ZWM4J1F1)

# Development Justification

### Justification of design decisions

I decided to do my layout such that the homepage has a taste of everything in one page, and if users want more information, they are then prompted to travel onto that specific page that has more information. This meets the users needs as the website's layouts and contents will have exactly what they (clients and users alike) are looking for.

I opted to use flexboxes throughout the website, this is because flexboxes adapt well to different screen sizes, so the website is more accessible on mobile devices. It also makes it easier to arrange elements in a container, even when the content size is dynamic. This is fit for purpose as users of the website may use all kinds of devices to access the website, so accommodating this allows for all users to be able to use the website effectively.

For website navigation, I used a navbar due to its familiarity and ease of scanning across primary pages like Home, About, Careers etc.
I also implemented a hamburger menu for mobile views to conserve space and maintain a clean layout. Navigation placement is consistent across all webpages to minimise confusion and improve familiarity.

Call to actions like "Apply for this position" and "Learn more..." are visually distinguished utilising the colour scheme to make it stand out, the buttons also have gradient transitions to highlight that they are clickable objects that can be interacted with. This is done to draw attention and have users engage with the website.

### Optimisation of Website

After completing my website to a satisfactory level, I reached out to my colleague (Cory Callicott) to see if he can inform any optimisations to my website:

[![Hotbeans_optimisations.png](https://i.postimg.cc/9031tXkg/Screenshot-2025-05-08-185214.png)](https://postimg.cc/620dBKtC)

This optimisation was fairly simple to implement, I changed the button colours from orange to a teal/green gradient that follows the webiste's colour scheme, making the website feel more professional as a whole.

| Before   | After |
|--------|--------|
| [![Button_Before.png](https://i.postimg.cc/13Pm7p6s/Screenshot-2025-05-08-190155.png)](https://postimg.cc/nCRfC90P) | [![Button_After.png](https://i.postimg.cc/tRZ4sRpQ/Screenshot-2025-05-08-190146.png)](https://postimg.cc/PNHjcjC2) |


### Review of client requirements

The client (HotBeansWeb) wanted a website that contained:
- A profile of the company itself
- profiles of existing trainee web developers
- job specifications and required qualifications
- an online application form
- links to web development courses

The target audience is people who have completed training courses or have gained related qualifications and are looking for an industry job.

I have fully met all the basic requirements that the client had requested, I have small pieces of each requriement on the homepage, and seperate webpages that go into further detail on each requirement.

# Testing Documentation

### Test Plan - Test Cases & Results
| Test Number | Feature Tested        | Test Steps                            | Expected Result                        | Actual Result     | Pass/Fail | Notes                 |
| ------------ | --------------------- | ------------------------------------- | -------------------------------------- | ----------------- | --------- | --------------------- |
| T-1        | Homepage loads        | Open homepage in browser              | Homepage displays correctly            | As expected       | Pass      |                       |
| T-2        | Navigation bar        | Click each menu item                  | User is taken to correct page          | About page broken | Fail      | Link not working      |
| T-2a       | Navigation bar        | Click each menu item                  | User is taken to correct page          | As expected | Pass      | Fixed broken links      |
| T-3        | Application form      | Fill and submit form with valid input | Form submits and shows success message | Form submits      | Pass      |                       |
| T-4        | Form submit           | Pressing submit button redirects to thank you page   | redirect to thank you page            | As expected | Passed      | Could add form validation to ensure fields filled out correctly |
| T-5        | Mobile responsiveness | Open site on mobile device            | Layout adjusts to mobile screen        | Layout good       | Pass      |                       |
| T-6        | Mobile navigation | click hamburger menu on mobile view           | hamburger menu opens       | As expected      | Pass      |                       |
| T-7        | Image loading | Open webpages to see if images load           | Images load properly       | Images show alt text (didn't load properly)      | Fail      |   Image links not working                    |
| T-7a        | Image loading | Open webpages to see if images load           | Images load properly       | Images load sucessfully      | Pass      |   fixed incorrect image links                    |

### Usability testing feedback


I distributed 2 Google forms in order to gather feedack regarding the website's usability features. The first form gathered information about the website's design as a whole and asked responders to comment on parts they like/dislike about the website. The second form was my testing form, where I asked responders to do actions and find specific webpages/elements, all of which were completed successfully. 
Overall, the feedback I have recieved from usability testing has been postitive. The overall response to the website's design and navigation was that it's clean and intutive - each button does what you expect it to do. 

# Evaluation and improvements

### Evaluation of Design & Optimised website against client requirements

This evaluation assesses the final website against the client's requirements, which included: a profile of the company, profiles of existing trainee developers, job specifications and required qualifications, an online applciation form and external links to web development courses. The purpose of this evaluation is to determine whether the website effectively meets these goals in terms of design, functionality, usablilty and performance.

The evaluation process involved a detailed review of each section of the website, functionality testting across multiple devices and browsers, user experience analysis and performance testing using tools such as webpagetest.org (which has various testing tools including Google Lighthouse and a comprehensive site performance test). A basic test plan was used to ensure each feature was tested methodically, and any bugs or issues were recorded and fixed. This evaluation will cover the website's strengths, weaknesses and any potential future improvements that can be made to the website.

#### Requirements Checklist Summary

| Requirement                         | Present? | Comments                                                                    |
| ----------------------------------- | -------- | --------------------------------------------------------------------------- |
| Company profile                     | Yes        | Homepage includes a professional summary of the company's goals and ethos.  |
| Trainee web developer profiles      | Yes        | Profiles feature names, skills, and contact details with consistent layout. |
| Job specifications & qualifications | Yes        | Job page lists positions with downloadable role descriptions.               |
| Online application form             | Yes        | Form includes validation, dropdowns, and successful submission feedback.    |
| Links to web development courses    | YEs        | Links to relevant courses included in sidebar and footer.                   |

#### Design and User Experience Feedback Summary (UX)

| Element                 | Rating (1–5) | Notes                                                                      |
| ----------------------- | ------------ | -------------------------------------------------------------------------- |
| Overall Layout          | 4            | Clean and structured layout; slight improvements in mobile spacing needed. |
| Color Scheme & Branding | 5            | Cohesive branding with consistent colors and logo placement.               |
| Font & Readability      | 4            | Easy to read on desktop; could use slightly larger font on mobile.         |
| Navigation & Menus      | 5            | Clear, intuitive navigation bar with dropdown support.                     |
| Accessibility           | 4            | Alt text used; contrast acceptable (could be improved)    |

#### Performance and Optimisation Summary

#### Potential future improvements

- **Fix Form Validation:** Add validation checks for all required fields to ensure data is filled out correctly
- **Improve Accessibility:** Add ARIA labels for better screen reader support


#### Conclusion

Overall, the website meets the client's core requirements and presents content in a clear, professional format. It performs well across various browsers and devices, offers a user friendly application form and integrates essential job and training information. Addressing the minor bugs, enhancing form validation and accessibility will further improve the website's quality and user experience. The project can be considered a successful implementation of the client's vision.

### Demonstration of individual responsibility and creativity

[![hotbeans_gantt_chart](readmeassets/Unit%2015-%20Assignment%202%20-%20D3%20Gantt%20Chart%20-%20Gantt%20Chart.pdf)]


