## Summary Document - New Booki Website

Here's an overview of the technical and functional specifications for the development of the new Booki website. These specifications have been approved by the Product team and should be followed closely during development.

![Screenshot of the website](screeshot%20of%20the%20webite.png)


### Functional Specifications

1. **Accommodation Search**: Users should be able to search for accommodation in their chosen town. The search field should be editable and part of a form for W3C validation. Note: The search functionality itself is not required to be functional at this stage.

2. **Clickable Maps**: All maps for accommodation and activities should be entirely clickable. Use the `href="#"` attribute to simulate the presence of a link for now.

3. **Filter Appearance**: Filters should change appearance on mouseover. The exact effect is not specified and can be determined during development. Functionality is not required.

4. **Header Links**: The words "Accommodation" and "Activities" in the header should be links leading to the respective sections ("Accommodation in Marseille" and "Activities in Marseille").

### Technical Specifications

1. **Responsive Design**: Two mockups are provided for desktop and mobile versions. The website should also be adapted for tablet formats, ensuring nothing is cut off and text is of sufficient size.

2. **Breakpoints**: Use breakpoints at 992px and 768px for desktop and tablet formats, respectively. Below 768px is for mobile phones.

3. **Embedding Order**: Develop for desktop first, then adapt for tablets and mobile using Media Queries.

4. **Image Optimization**: Choose the most appropriate image format depending on resolution and loading time.

5. **Icon Usage**: Utilize icons from the Font Awesome library, possibly using a CDN for loading optimization.

6. **Color Palette**: Use blue (#0065FC), a lighter version of blue (#DEEBFF), and gray (#F2F2F2) for background.

7. **Font**: Use Raleway font from Google Fonts. Import it into the code for easy access.

8. **Units and Layout**: Use pixels and percentages for units, and Flexbox for layout. Avoid using REMs and EMs.

9. **CSS Frameworks and Pre-processors**: Do not use CSS frameworks or pre-processors like BootStrap, TailwindCSS, Sass, or Less.

10. **Semantic Tags**: Use semantic HTML tags for better accessibility and SEO.

11. **Code Validation**: Ensure the code is valid according to W3C HTML and CSS validators.

12. **Browser Compatibility**: Test the prototype on the latest versions of Google Chrome and Mozilla Firefox.

13. **Version Control**: Git is not required for versioning the code.

Following these specifications will ensure the successful development of the new Booki website.