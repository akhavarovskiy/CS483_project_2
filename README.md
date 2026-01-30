# Write Up
Name: Aleksandr Khavarovskiy
Email: a.khavarovskiy@wsu.edu

## Includes Files

proj2_assets - Assets Used by Webpage
index.html - Main Page
contact.html - Contact page for website
about.html - A page describing the website

## Github Pages Link
<a href="https://akhavarovskiy.github.io/CS483_project_2">Link</a>

## Dom Representation

```
BODY 
  HEADER 
    H1
      #text: "Contact Us"
  NAV 
    UL 
      LI 
        A 
          #text: "Home" 
      LI 
        A 
          #text: "About Us" 
      LI
        A
          #text: "Contact"
  MAIN
    H2
      #text: "Get in touch"
    P
      #text: "If you have any questions or would like to book our services, 
                feel free to reach out to us be using the contact form below."
    FORM#my_form
      LABEL
        #text: "Your Name:"
      INPUT#your_name
      BR 2
      LABEL
        #text: "Your Email:"
      INPUT#your_name
      BR 2
      LABEL
        #text: "Your Message:"
      BR
      TEXTAREA#your_message
      BR 2
      BUTTON
        #text: "Submit"
      BR
  FOOTER
    #text: "Contact us at:"
    A
      #text: "info@petsitting.com"
```

<p>
 The page meets SEO requirements since the page is broken out into specific sections. 
 The language of the page is set in the html element to allow the search engines to understand who to best serve the content to.
 The navigation section is clearly marked and will be used by the seach engine to find related pages.
 The main content of the page is clearly marked with a single header encompasing the purpose of the page. The form with name, email, and text section will allow search engines to better understand the purpose of the page.
 Each of the for elements has a corresponding label element allowing for screen readers to allow vision impared users to understand the form content.
 Each of the input types are also clearly labeled which will enforce validation by the browser for each type of field. 
</p>