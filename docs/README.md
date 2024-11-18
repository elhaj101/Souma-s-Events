# Souma's Events

## Project Name
**Souma's Events**

## Table of Contents
1. [Introduction](#introduction)
2. [Pages Overview](#pages-overview)
   - [1. Index](#1-index)
   - [2. Locations](#2-locations)
   - [3. Photography](#3-photography)
   - [4. Catering](#4-catering)
   - [5. Contact](#5-contact)
   - [6. About Us](#6-about-us)
   - [7. Thank You](#7-thank-you)
3. [Features](#features)
4. [Credits](#credits)
5. [Manual Testing](#manual-testing)
6. [Deployment](#deployment)

## Introduction

**Description**:  
Souma's Events is a comprehensive website designed for an events planning business. It serves as a platform to showcase services, provide information, and engage with potential clients. The goal is for users to be encouraged to fill out a contact form and make a business inquiry, which can be found on the contact.html page.

**User Demographics**:  
The target audience includes individuals and organizations looking to plan events such as weddings, corporate gatherings, parties, and other special occasions.

## Pages Overview

### 1. Index
- **Description**: The homepage provides an overview of Souma's Events, highlighting key services and offerings through an engaging carousel and detailed sections.
- **User Interaction**: Visitors can navigate to other sections of the website from the homepage using a responsive navbar.
- **Main Content**:
  - A carousel featuring images and descriptions of services.
- **Placeholder Image**: ![Index Page ](/assets/images/indexread.png)

### 2. Locations
- **Description**: This page features a selection of event venues available for rent, providing an inviting overview with images.
- **User Interaction**: Users can view different venues and are encouraged to contact the company for more information.
- **Main Content**:
  - An introductory section with a heading and description.
- **Placeholder Image**: ![Locations Page ](/assets/images/locationsread.png)

### 3. Photography
- **Description**: This page showcases the photography services offered by Souma's Events, highlighting a collection of stunning images from various events like weddings, parties, and corporate gatherings.
- **User Interaction**: Visitors can browse through a gallery of images, view details about the photography services, and inquire for bookings.
- **Main Content**:
  - **Introduction Section**: 
    - Title: "Capturing Moments That Matter"
    - Description: A brief welcome message highlighting the purpose of the gallery.
    - Call to Action: A button linking to the contact page.
- **Placeholder Image**: ![Photography Page ](/assets/images/photographyread.png)

### 4. Catering
- **Description**: This page provides information about catering options available for events. It includes an overview of services but does not display specific pricing.
- **User Interaction**: Users can learn about catering services and make inquiries through the contact form on the website.
- **Placeholder Image**: ![Catering Page ](/assets/images/cateringread.png)

### 5. Contact
- **Description**: A contact page that allows potential clients to reach out to Souma's Events for inquiries or bookings.
- **User Interaction**: Features a contact form where clients can fill out their details, specify their event type, and request an offer. Users will receive a response within three business days.
- **Main Content**:
  - **Contact Form**: Users can provide their name, email, city, and select a subject related to their inquiry.
  - **Submission Confirmation**: Upon submission, users are directed to a thank you page.
- **Placeholder Image**: ![Contact Page ](/assets/images/contactreadd.png)

### 6. About Us
- **Description**: This page details the mission, vision, and background of Souma's Events, introducing the team and their expertise.
- **User Interaction**: Users can learn more about the company’s values and team members.
- **Main Content**:
  - **Meet Our Team**: 
    - **Anna Schmidt**, Event Planning Manager: With over 8 years of experience, Anna ensures every detail is perfect.
    - **Markus Müller**, Culinary Expert: With over 10 years in the catering industry, Markus specializes in curating menus that delight every palate.
    - **Julia Fischer**, Photographer: With a keen eye for detail, Julia captures the essence of every event, ensuring that memories are preserved beautifully.
- **Placeholder Image**: ![About Us Page ](/assets/images/aboutusread.png)

### 7. Thank You
- **Description**: The Thank You page serves as a confirmation that a user's inquiry or booking request has been successfully submitted.
- **Purpose**: 
  - It reassures users that their request is being processed and that they can expect a response from the Souma's Events team within three business days.
  - This page enhances user experience by providing clear communication about the next steps, helping to build trust and engagement with potential clients.
- **Main Content**:
  - A welcoming message thanking the user for their inquiry.
  - Information indicating that the team will review the request and follow up shortly.
- **Placeholder Image**: ![Thank You Page ](/assets/images/thankread.png)

## Features

- **Navbar**: A responsive navigation bar present on all pages, providing links to:
  - Home
  - PhotographyPage
  - Catering
  - Locations
  - Contact Us
  - Buffet

  The navbar is designed to be responsive and takes the form of a burger menu on smaller screens, ensuring easy access to navigation links on mobile devices.

![Responsive Navbar](/assets/images/respnavbar.png)

- **Footer**: A consistent footer across all pages, containing:
  - Contact information, including address and multiple email contacts for inquiries.
  - Social media links (Facebook, Twitter, Instagram, LinkedIn).
  - Legal notices and copyright information.
  - Validation certificates from "W3C".

![Footer](/assets/images/footerread.png)

- **Carousel**: Automated using JavaScript, this carousel showcases different services with images and descriptions, along with buttons that take the user directly to the relevant page.

![Carousel Smaller Screen](/assets/images/rescarousel.png)  

![Carousel Larger Screen](/assets/images/carousel.png)

- **call to action button**:

![index Page call to action ](/assets/images/what-are-youwaiting-for-button.png)


- **Marketing Grid**: Takes the user to relevant pages within the website when clicking on the interactive button links.

![Marketing Grid](/assets/images/marketing.png)

- **Event Categories**: Lists various event types such as:
  - Weddings
  - Baby Showers
  - Birthdays
  - Graduation Parties
  - Engagements
  - Corporate Events

![Event Categories](/assets/images/coloms.png)

- **Video Embed**: Displays a video showcasing events organized by Souma's Events.

![Video Embed](/assets/images/video.png)

- **Contact Form**: The Contact page includes a form where clients can fill out their details to apply for an offer, fulfilling the website's goal. The form contains inputs like name, email, subject, and description.

![Contact Page](/assets/images/contact-page.png)  
![Responsive Contact Page](/assets/images/res-contact.png)  
![Contact Form](/assets/images/contact-form.png)  
![Responsive Contact Form](/assets/images/res-contact-form.png)

## Credits
- All media files were taken from [pexels.com].
- The carousel and album templates were taken from [Bootstrap].

### 1. Steps Taken to Manually Test
- Open the website in various browsers (Chrome, Firefox, Safari) and devices (desktop, tablet, mobile).
- Navigate through all pages using the navbar and ensure all links work.
- Test the carousel functionality for smooth transitions and responsiveness.
- Fill out the contact form with valid and invalid data to test validation.

### 2. Functionality Testing Results

| Functionality                                      | Page          | Does it work as intended? |
|---------------------------------------------------|---------------|---------------------------|
| Carousel transitions and links                     | Index         | ✓ Yes                     |
| Links to other pages (Photography, Catering, etc.)| Index         | ✓ Yes                     |
| Display of event venues and details                | Locations     | ✓ Yes                     |
| Contact information and inquiry button             | Locations     | ✓ Yes                     |
| Image gallery showcasing photography services      | Photography   | ✓ Yes                     |
| Call to action button linking to contact page      | Photography   | ✓ Yes                     |
| Overview of catering services                       | Catering      | ✓ Yes                     |
| Links for inquiries and details                     | Catering      | ✓ Yes                     |
| Functional contact form with validation            | Contact       | ✓ Yes                     |
| Submission confirmation and redirection            | Contact       | ✓ Yes                     |
| Team information and expertise                      | About Us      | ✓ Yes                     |
| Clear mission and vision statement                  | About Us      | ✓ Yes                     |
| Thank you message upon form submission             | Thank You     | ✓ Yes                     |
| Confirmation of request processing                  | Thank You     | ✓ Yes                     |
| Responsive design across all devices                | All pages     | ✓ Yes                     |

### 3. Lighthouse Performance Audit
- Run a Lighthouse audit in Chrome DevTools to assess performance, accessibility, best practices, and SEO.
- Review scores and recommendations for improvements.

### 4. W3C HTML and CSS Validation
- Use the [W3C Markup Validation Service] to check HTML.

![aboutus validation](/assets/images/aboutus.png)  
![catering validation](/assets/images/catering.png)
![index validation](/assets/images/index.png)
![locations](/assets/images/locations.png)
![photography validation](/assets/images/photog.png)
![thankyou validation](/assets/images/thankyou.png)
![contact validation](/assets/images/contact.png)


- Validate CSS using the [W3C CSS Validation Service].

![w3c](/assets/images/w3c-css-validation.png)  


## Deployment

### Deployment on GitHub
1. Create a GitHub repository named `soumas-events`.
2. Push your local files to the repository:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main