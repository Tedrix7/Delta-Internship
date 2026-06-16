# Delta EMEA Employer Branding Website

## Project Overview

This project is a responsive employer branding website concept for Delta Electronics EMEA. The website is designed to help students, graduates, and professionals understand what Delta stands for, what it feels like to work at Delta, and how they can grow their careers within the company.

The recurring employer branding message across the website is:

**“Together, we power a smarter and greener tomorrow.”**

The website follows a hub-and-topic-page structure. The homepage introduces the main employer branding themes and guides visitors toward deeper pages such as Life at Delta, Sustainability in Action, Delta Voices, Find Your Spot, Internships, and Growth & Development.

## Project Goal

The goal of this project is to design and build a front-end employer branding website that communicates Delta’s culture, people, values, sustainability impact, and career opportunities in a clear and engaging way.

The website aims to:

- Present Delta EMEA as an attractive and people-focused employer.
- Help candidates and students quickly understand Delta’s values, impact, and opportunities.
- Create a more newcomer-friendly experience compared to a purely corporate website.
- Support future content updates such as employee stories, internship moments, CSR initiatives, and career-related pages.
- Provide a responsive and accessible front-end implementation that can be used inside Delta’s CMS.

## Website Pages

The uploaded website consists of the following HTML pages:

### 1. Home Page

**File:** `home-page.html`

The homepage acts as the central hub of the employer branding platform. It introduces the main message of the website and links visitors to the most important topic areas.

Main sections include:

- Hero section with the main employer branding message.
- Empowering People, Driving Progress.
- Life at Delta.
- Grow Your Career at Delta.
- Delta Voices.
- Find Your Spot.
- Sustainability in Action.
- Discover Internships at Delta.
- Join Delta Today call-to-action.

### 2. Life at Delta: Living Our Values

**File:** `values-page.html`

This page presents Delta’s core values and shows how they are reflected in the company culture.

Main sections include:

- Built on Values, Powered by People.
- Integrity.
- Quality and professional standards.
- Innovation.
- Collaboration.
- Inclusion.
- Empowerment.
- Delta Voices.
- Career growth highlights.
- Join Delta Today call-to-action.

### 3. Sustainability in Action / CSR

**File:** `csr-page.html`

This page focuses on Delta’s sustainability and CSR initiatives. It connects Delta’s environmental values with employee engagement and real-world impact.

Main sections include:

- Together We Make Meaningful Impact.
- Living Our Values.
- Connecting Impact Around the World.
- Designed for People and Planet.
- CSR commitments.
- Green Voice.
- Milestones of Impact.
- Join Delta Today call-to-action.

### 4. Delta Voices

**File:** `voices-page.html`

This page works as the employee article and blog overview. It highlights real employee experiences and presents article cards for different topics.

Main sections include:

- Hero section for Delta Voices.
- Highlight Articles carousel.
- All Articles overview.
- Article cards with topic tags, dates, images, summaries, and read-more links.
- Join Delta Today call-to-action.

### 5. Delta Voices Article Detail

**File:** `voices-2-page.html`

This page is an example of an individual article detail page.

Article included:

- Journey of Growth Ahead.

The page includes a category tag, article title, main image, and article body text.

### 6. Find Your Spot + Hiring Process

**File:** `find-your-spot-page.html`

This page helps visitors explore roles, locations, the hiring journey, and internship opportunities.

Main sections include:

- Join Delta for a Smarter and Greener Tomorrow.
- Find Your Spot carousel.
- Global Operations.
- Hiring Process.
- Internship stories.
- Embark Your Internship.
- Join Delta Today call-to-action.

### 7. Growth & Development

**File:** `growth-page.html`

This page communicates career growth, learning, empowerment, and development opportunities at Delta.

Main sections include:

- Grow Your Career at Delta.
- At Delta, Your Growth Is Our Priority.
- Empowerment in Action accordion.
- Motivated to Grow: Inside Delta Careers.
- Leadership quote.
- Join Delta Today call-to-action.

## Technologies Used

This project is built as a static front-end website using:

- HTML5
- CSS3
- JavaScript
- Google Fonts: Inter
- Responsive CSS with `clamp()`, media queries, flexible grids, and reusable layout patterns
- Delta-hosted visual assets from the Delta file center

## CMS Implementation

The website is prepared for Delta’s CMS environment. Each page is built as a self-contained HTML file with the CSS and JavaScript included in the same file.

This makes the pages easier to transfer into the CMS because the structure, styling, and interactions are kept together.

## Main Components

The project uses repeated and reusable interface patterns, including:

- Full-screen hero sections.
- Gradient text treatments.
- Responsive content containers.
- Primary and outline buttons.
- Image cards.
- Article cards.
- Carousels.
- Accordions.
- CTA banners.
- Section-based page layouts.
- Responsive image grids.

These repeated patterns help keep the website visually consistent and easier to maintain.

## Responsiveness

The website is designed with desktop as the priority, while still supporting tablet and mobile layouts.

Responsive techniques include:

- Flexible widths using `min()`, `clamp()`, and viewport units.
- Media queries for tablet and mobile breakpoints.
- Grid layouts that change from multi-column to single-column layouts.
- Carousel layouts that adapt from three visible cards to two or one depending on screen size.
- Scalable typography and spacing.

## Accessibility Considerations

The website includes several accessibility-focused choices:

- Semantic HTML structure using `main`, `section`, `article`, headings, buttons, and labels.
- `aria-label` attributes for important sections and carousel controls.
- Alternative text for meaningful images.
- Decorative images marked with empty `alt` text where appropriate.
- Buttons used for interactive elements such as carousels, tabs, and accordions.
- Readable typography and strong visual hierarchy.

Further accessibility improvements can include:

- Adding visible keyboard focus styles.
- Adding `aria-current` or `aria-selected` states to active carousel dots and tabs.
- Connecting tab buttons to panels with `aria-controls`.
- Testing the pages with keyboard-only navigation.
- Running a Lighthouse and accessibility checker test before final handover.

## Current Status

The current version includes the main employer branding pages and interactive front-end components. The pages are suitable for further CMS integration, stakeholder review, and user testing.

Some links currently use placeholder `#` values. These should be replaced with the correct CMS page links before publication.

## Testing Checklist

Before final delivery, the following checks should be completed:

- Test all pages on desktop, tablet, and mobile.
- Test in Chrome, Firefox, Safari, and Edge.
- Check all carousel, accordion, filter, and CTA interactions.
- Replace placeholder links with real CMS links.
- Check image loading and image quality.
- Review all alt text.
- Run Lighthouse performance and accessibility checks.
- Test keyboard navigation.
- Validate heading order and semantic structure.
- Confirm that all content matches Delta’s tone of voice and brand guidelines.
- Ask stakeholders to review the final pages before handover.


## Author

Teodor Stamenov  
ICT Student / UX & Front-end Intern  
Fontys University of Applied Sciences  
Delta Electronics EMEA Internship Project
