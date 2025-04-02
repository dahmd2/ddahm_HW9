# ddahm_HW9– Web Forms Assignment

## A. Project Description

This is a multi-page student survey web form created using HTML, CSS, Bootstrap 5.3, and Font Awesome. It collects information about BAIS students and is deployed as a responsive static site on Azure.

## B. Best Practices for Web Forms

This form implementation follows several best practices to ensure it is both user-friendly and effective in gathering accurate data. First, each form field is properly labeled and uses semantic HTML5 input types, such as text fields and select menus. Required fields are clearly indicated and enforced using the `required` attribute, helping reduce incomplete submissions. The form also uses `autofocus` to direct the user’s attention immediately to the first input field on the first page, improving flow and usability.

To support user understanding, a Font Awesome icon with a tooltip is included next to the "My home town is" input. This provides contextual help without cluttering the interface. The form also uses a Likert scale for measuring impressions of the major, and checkboxes for selecting completed courses, which are both intuitive and easy for users to interact with. Each page includes clear titles and descriptions to guide users through the process. Additionally, Bootstrap 5.3 is used throughout for responsive layout and form styling, ensuring a clean and mobile-friendly user experience.

## C. User Accessibility

Accessibility was a major priority in the design of this form. Each input is paired with an accessible `<label>` element, and all color choices maintain sufficient contrast to meet WCAG 2.1 AA standards. Keyboard navigation is fully supported, including tabbing through form fields and triggering the tooltip on hover/focus. Font sizes and spacing follow guidelines for readability and usability, especially for users with visual impairments. The form validates successfully as HTML5 and CSS3, and passes WCAG accessibility checks to ensure that all users can access and complete the form.
