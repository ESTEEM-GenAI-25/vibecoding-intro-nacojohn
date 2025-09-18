# 📑 Product Requirements Document (PRD)

## 1. Project Overview
- **Summary:**  
  A professional portfolio website showcasing Nnanna John’s expertise in digital transformation, policy advisory, innovation ecosystems, and technology leadership.

- **Context/Background:**  
  The website is being created to establish an online professional presence, centralize career achievements, highlight global contributions to digital innovation and policy, and provide an accessible platform for networking, consulting, and collaboration opportunities.

## 2. Goals and Objectives
- **Primary Goal(s):**  
  - Present a credible and professional digital profile.  
  - Showcase experience, skills, and achievements across policy, technology, and innovation.  
  - Provide a central contact point for professional opportunities.  

- **Secondary Goal(s):**  
  - Share thought leadership (e.g., articles, speaking engagements).  
  - Highlight recognitions such as Mandela Washington Fellowship and AU engagements.  
  - Serve as a resource hub for collaborators and mentees.

## 3. Target Audience
- **Who are the users?**  
  - Policymakers and government agencies.  
  - Multilateral organizations (e.g., AU, World Bank).  
  - Startups, SMEs, and innovation hubs.  
  - Academic collaborators and researchers.  
  - General professional network.  

- **User Needs:**  
  - Learn about expertise in digital transformation and policy.  
  - View projects, achievements, and speaking engagements.  
  - Access CV/resume or request consulting engagements.  
  - Easily connect via email, LinkedIn, or other channels.  

## 4. Key Features / Requirements
- **Must-Have Features:**  
  - Homepage with professional summary.  
  - About page with detailed biography and education.  
  - Projects/Experience page showcasing AU, RAD5, ministry, and consultancy work.  
  - Recognition & Awards section.  
  - Contact form with email and LinkedIn integration.  
  - Downloadable CV.  

- **Nice-to-Have Features (Optional):**  
  - Blog/Insights section for articles and thought leadership.  
  - Testimonials from collaborators or mentees.  
  - Newsletter subscription.  
  - Interactive timeline of career milestones.  

## 5. Design & User Experience
- **Visual Style / Vibe:**  
  Professional, minimalist, clean, and authoritative.  

- **Branding / Colors / Fonts:**  
  - Colors: Blue, white, and gray tones (reflecting trust, professionalism, and clarity).  
  - Fonts: Sans-serif fonts (e.g., Open Sans, Lato, Roboto).  

- **Accessibility Considerations:**  
  - High contrast for text.  
  - Alt text for all images.  
  - Screen reader compatibility.  
  - Mobile-first responsive design.  

## 6. Content Requirements
- **Pages / Sections:**  
  - **Homepage**: Hero section with name, title, professional tagline.  
  - **About/Bio**: Detailed background, education, certifications.  
  - **Experience**: Work with African Union, RAD5 Tech Hub, government advisory roles.  
  - **Projects/Portfolio**: Key transformation projects, policy contributions, startup mentorships.  
  - **Awards & Recognition**: Mandela Washington Fellowship, service awards, thought leadership.  
  - **Skills & Certifications**: Digital transformation, policy, cybersecurity, AI for policy, enterprise design thinking.  
  - **Contact**: Email, LinkedIn, optional contact form.  
  - **Downloads**: PDF CV.  

- **Specific Content to Include:**  
  - Professional summary from CV.  
  - Logos of organizations (AU, Notre Dame, RAD5, etc.).  
  - Links to LinkedIn profile.  
  - Images from speaking engagements/events (optional).  

## 7. Technical Constraints
- **Technology Stack:**  
  - HTML5, CSS3, JavaScript for a static site.  
  - Optional React framework for interactivity and scalability.  

- **Hosting / Deployment:**  
  - Hosted on **GitHub Pages**.  
  - Repository structure:  
    ```
    / (root)
      index.html
      /assets
        /css
        /js
        /images
    ```  
  - GitHub Pages URL: `https://username.github.io/portfolio/`  
  - Custom domain support (optional, e.g., nnannajohn.com).  

- **Performance / Security Requirements:**  
  - Mobile responsive design.  
  - SSL/HTTPS via GitHub Pages.  
  - Fast loading times (<2 seconds).  

## 8. Out of Scope
- E-commerce features.  
- Social media integrations beyond LinkedIn.  
- Large-scale blogging platform (initially).  
- Complex backend systems (focus on static/professional portfolio).  

## 9. Acceptance Criteria
- Homepage loads in under 2 seconds.  
- Fully responsive on mobile (iOS/Android) and desktop.  
- Contact form works and sends messages to provided email.  
- LinkedIn and CV download links functional.  
- All accessibility checks passed (WCAG compliance).  
- Key sections (About, Experience, Projects, Awards, Contact) are present and populated.  
