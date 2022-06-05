# [NextJS Material Kit PRO]


## Table of Contents


* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)



## File Structure
Within the download you'll find the following directories and files:

```
nextjs-material-kit-pro
.
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── README.md
├── next.config.js
├── package.json
├── Documentation
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   │   └── faces
│   │   └── js
│   └── tutorial-components.html
├── pages
│   ├── _app.js
│   ├── _document.js
│   ├── _error.js
│   ├── about-us.js
│   ├── blog-post.js
│   ├── blog-posts.js
│   ├── components.js
│   ├── contact-us.js
│   ├── ecommerce.js
│   ├── error-page.js
│   ├── index.js
│   ├── landing-page.js
│   ├── login.js
│   ├── presentation.js
│   ├── pricing.js
│   ├── product.js
│   ├── profile.js
│   ├── sections.js
│   ├── shopping-cart.js
│   └── signup.js
├── assets
│   ├── css
│   │   ├── nextjs-material-kit-pro.css
│   │   ├── nextjs-material-kit-pro.css.map
│   │   └── nextjs-material-kit-pro.min.css
│   ├── img
│   │   ├── assets-for-demo
│   │   │   ├── example-pages
│   │   │   ├── ourClients
│   │   │   ├── presentationViewSectionComponent
│   │   │   └── sections
│   │   │       └── imgs.js
│   │   ├── examples
│   │   ├── faces
│   │   ├── flags
│   │   └── sections
│   ├── jss
│   │   ├── nextjs-material-kit-pro
│   │   │   ├── components
│   │   │   └── views
│   │   │       ├── aboutUsSections
│   │   │       ├── blogPostSections
│   │   │       ├── blogPostsSections
│   │   │       ├── componentsSections
│   │   │       ├── ecommerceSections
│   │   │       ├── landingPageSections
│   │   │       ├── presentationSections
│   │   │       ├── pricingSections
│   │   │       ├── sectionsSections
│   │   └── nextjs-material-kit-pro.js
│   └── scss
│       ├── core
│       │   ├── mixins
│       │   └── variables
│       ├── plugins
│       └── nextjs-material-kit-pro.scss
├── components
│   ├── Accordion
│   │   └── Accordion.js
│   ├── Badge
│   │   └── Badge.js
│   ├── Card
│   │   ├── Card.js
│   │   ├── CardAvatar.js
│   │   ├── CardBody.js
│   │   ├── CardFooter.js
│   │   └── CardHeader.js
│   ├── Clearfix
│   │   └── Clearfix.js
│   ├── CustomButtons
│   │   └── Button.js
│   ├── CustomDropdown
│   │   └── CustomDropdown.js
│   ├── CustomFileInput
│   │   └── CustomFileInput.js
│   ├── CustomInput
│   │   └── CustomInput.js
│   ├── CustomLinearProgress
│   │   └── CustomLinearProgress.js
│   ├── CustomTabs
│   │   └── CustomTabs.js
│   ├── CustomUpload
│   │   └── ImageUpload.js
│   ├── Footer
│   │   └── Footer.js
│   ├── Grid
│   │   ├── GridContainer.js
│   │   └── GridItem.js
│   ├── Header
│   │   ├── Header.js
│   │   └── HeaderLinks.js
│   ├── InfoArea
│   │   └── InfoArea.js
│   ├── Instruction
│   │   └── Instruction.js
│   ├── Media
│   │   └── Media.js
│   ├── NavPills
│   │   └── NavPills.js
│   ├── PageChange
│   │   └── PageChange.js
│   ├── Pagination
│   │   └── Pagination.js
│   ├── Parallax
│   │   └── Parallax.js
│   ├── Snackbar
│   │   └── SnackbarContent.js
│   ├── Table
│   │   └── Table.js
│   └── Typography
│       ├── Danger.js
│       ├── Info.js
│       ├── Muted.js
│       ├── Primary.js
│       ├── Quote.js
│       ├── Rose.js
│       ├── Small.js
│       ├── Success.js
│       └── Warning.js
└── pages-sections
    ├── about-us
    │   ├── SectionContact.js
    │   ├── SectionDescription.js
    │   ├── SectionOffice.js
    │   ├── SectionServices.js
    │   └── SectionTeam.js
    ├── blog-post
    │   ├── SectionBlogInfo.js
    │   ├── SectionComments.js
    │   ├── SectionSimilarStories.js
    │   └── SectionText.js
    ├── blog-posts
    │   ├── SectionImage.js
    │   ├── SectionInterested.js
    │   ├── SectionPills.js
    │   └── SubscribeLine.js
    ├── components
    │   ├── SectionBasics.js
    │   ├── SectionCards.js
    │   ├── SectionCarousel.js
    │   ├── SectionContentAreas.js
    │   ├── SectionFooter.js
    │   ├── SectionJavascript.js
    │   ├── SectionNavbars.js
    │   ├── SectionNotifications.js
    │   ├── SectionPills.js
    │   ├── SectionPreFooter.js
    │   ├── SectionTabs.js
    │   └── SectionTypography.js
    ├── ecommerce
    │   ├── SectionBlog.js
    │   ├── SectionLatestOffers.js
    │   └── SectionProducts.js
    ├── landing-page
    │   ├── SectionProduct.js
    │   ├── SectionTeam.js
    │   └── SectionWork.js
    ├── presentation-page
    │   ├── SectionCards.js
    │   ├── SectionComponents.js
    │   ├── SectionContent.js
    │   ├── SectionDescription.js
    │   ├── SectionExamples.js
    │   ├── SectionFreeDemo.js
    │   ├── SectionOverview.js
    │   ├── SectionPricing.js
    │   └── SectionSections.js
    ├── pricing-page
    │   ├── SectionFeatures.js
    │   └── SectionPricing.js
    └── sections-page
        ├── SectionBlogs.js
        ├── SectionContacts.js
        ├── SectionFeatures.js
        ├── SectionHeaders.js
        ├── SectionPricing.js
        ├── SectionProjects.js
        ├── SectionTeams.js
        └── SectionTestimonials.js
```


