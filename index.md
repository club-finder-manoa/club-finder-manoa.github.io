# **Club Finder Manoa**

## **Table of contents**

* [Overview](#overview)
* [User Guide](#user-guide)
* [Development History](#development-history)
* [Deployment](#deployment)
* [Developer Contact](#developer-contact)

## **Overview**
<!-- Summarizes what the system does and what makes it special and different from other related applications -->

*The problem*: UH Manoa has over 200 Registered Independent Organizations, plus many more that do not have this “official” status but are nonetheless active organizations. Unfortunately, there is no easy way for students to learn what student clubs (both registered and unregistered) exist, what they do, and how to get further involved.

*The solution*: The Club Finder Manoa application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), contact information for officers, and a few select photos.

Club Finder Manoa has three user roles, all of whom login with their UH ID:
  - Regular users browse the directory
  - Club Admins have the ability to edit the data associated with their club
  - Super Admins make sure site content is appropriate and grant “club admin” privileges to selected users

The site will allow a user to browse the list of clubs in alphabetical order as well as filter by interest. For example, “athletic” clubs, “art” clubs, “music” clubs, etc. A club can belong to multiple interest areas, making it easier for users to find.

Users can specify interest areas, and be notified when a new club is created matching that interest area (or an existing club adds that interest area).

Admins can monitor the site for inappropriate content, and create new categories of interests, capabilities, and goals.

## **User Guide**
<!-- Provide at least one screen shot of every page. This section should provide enough detail for a user to get up and running with your system (you can provide further help within the application itself) -->

This section provides a walkthrough of the Club Finder Manoa user interface and its capabilities.

### **Landing Page**

The landing page is presented to users when they visit the top-level URL to the site.

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/landing.png">
</div>

### **Sign In / Sign Up**

Club Finder Manoa requires students to log in to access club information. Users are required to have a @hawaii.edu email to create an account. To log in, click "Login" in the upper right corner of the page. If you are a returning user, select "Sign In" and the sign in page will be displayed:

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/login.png">
</div>

Alternatively, if you are a new user, select "Sign up" and you will be directed to a page where you can create a new account:

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/signup.png">
</div>

<!--
### **My Clubs Page**

After logging in, you are taken to the "My Clubs" page (to be completed).
-->

### **All Clubs Page**

Selecting "All Clubs" in the navbar will direct you to a page displaying a list of all of the clubs stored in the application's database:

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/all-clubs.png">
</div>

### **Club Page**

You can select a club from the list to see a specific club's page. This page displays more information about the club, including contact information, meeting times, and upcoming events:

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/club-page.png">
</div>

### **Profile Page**

Users can view their profile and edit profile information by selecting "Profile" in the navbar:

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/profile.png">
</div>

<!--
### **Admin Page**

Site administrators have access to a special admin page where they can edit users and clubs.

<div class="col d-flex justify-content-center">
  <img width="90%" class="rounded" src="./assets/images/login.png">
</div>

-->

<!--
## **Community Feedback**
<!-- Provides information obtained from users about the system

## **Developer Guide**
<!-- How to download, install, and run the system locally, as well as how to deploy it -->

## **Development History**
<!-- Explains the trajectory of development of the system: what was accomplished during each milestone. See the BowFolios system for details -->
- **[M1](https://github.com/orgs/club-finder-manoa/projects/1/views/1?layout=board)** (Milestone 1)
  - Completed mockups for major pages
  - Defined database schemas
  - Deployed to Digital Ocean

- **[M2](https://github.com/orgs/club-finder-manoa/projects/2)** (Milestone 2)
  - Integrate all mockup pages to deployed website
  - Refine database schema
  - Link pages to database

## **Deployment**
<!-- Section called Deployment containing a link to the deployed application running on Digital Ocean -->

[View Live Website](http://142.93.232.214/)

## **Developer Contact**
<!-- Explains who the developers of the system are and how to get in touch with them if you have comments or questions -->

Club Finder Manoa is designed, implemented, and maintained by:
- [Destynee Fagaragan](https://djaf6.github.io/)
- [Galen Chang](https://galenchang.github.io/)
- [Gwyneth Raquepo](https://graquepo.github.io/)
- [Jayson Iwanaka](https://jiwanaka.github.io/)
- [Robert Godfrey](https://robertgodfrey.github.io/)

[Team Contract](./team-contract.pdf)

For comments or questions, please contact us via our project's [GitHub](https://github.com/club-finder-manoa/club-finder-manoa).
