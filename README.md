# Web Studio - CSS Animation and Modal Window

Welcome to the continued development of the Web Studio project! In this part of the project, CSS animations and decorative effects have been added to enhance the visual appeal of the web pages. Also, modal window functionality has been incorporated to handle user interactions. Below are the details of what this portion of the project contains:

## Project Contents

### CSS Animation and Styling

- All styles for the project are consolidated in a single CSS file named `styles.css`, located in the `css` folder.
- The CSS code is formatted using Prettier, maintaining code consistency and readability.
- All images and textual content are carefully placed within the layout, ensuring they are correctly structured.
- The project utilizes the `modern-normalize` stylesheet to ensure consistent rendering across different browsers.
- The CSS code is written following the provided tutorial.

### Modal Window

- The script responsible for the modal window functionality is included in a separate file named `modal.js`, and it is linked to the HTML using a script tag.
- The modal window and backdrop (dark semi-transparent overlay) are properly marked up and decorated with CSS styles.
- The modal window is vertically and horizontally centered within the backdrop.
- A close button is added to the top-right corner of the modal window for easy dismissal.
- The modal window and backdrop are initially hidden using the class `is-hidden`, which utilizes the `visibility`, `opacity`, and `pointer-events` properties.
- Clicking on the "Order Service" button opens the modal window with a submission form.
- The appearance and disappearance of the modal window are animated using transitions with customizable effects, such as `scale` or `translate`, along with `opacity`.

### Custom Data Attributes

- Special data attributes are added to relevant HTML tags for the modal window script to locate the corresponding elements:
  - `data-modal-open` - for the button that opens the modal window.
  - `data-modal-close` - for the button that closes the modal window.
  - `data-modal` - for the backdrop of the modal window.

## Conclusion

This part of the Web Studio project introduces exciting animations and decorative effects to the web pages, enhancing the overall user experience. Additionally, the implementation of the modal window provides a seamless way to handle user interactions and display important content, such as a service ordering form.
