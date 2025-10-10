Project Title:sign-in-sign-up-with-product-store

Short Description: This responsive vanilla JS (HTML/CSS) app simulates a complete e-commerce platform. It features single-page authentication (Sign Up/Sign In via LocalStorage for credential management) and a dynamic product store. The catalog of 300 API-fetched products is displayed with prices localized in Pakistani Rupees (PKR), supporting advanced features like search, category/price filters, a Dark Mode toggle, and a secure logout procedure.

features list 
The provided code creates a fully functional, front-end authentication interface with a focus on modern design and client-side validation.
1. User Interface & Design Features
Modern, Responsive Layout: The form is centered, features a clean card design, and adapts well to all screen sizes (mobile, tablet, desktop) using Tailwind CSS utilities.
Aesthetics: Uses a soft background, rounded corners, and a subtle box shadow (`auth-card`) for a professional look. The Inter font is used for clear typography.
Toggle Switch: A button allows users to switch instantly between Sign Up and Sign In views without reloading the page.
Visual Feedback: The button colors are distinct for each form (Blue for Sign Up/Registration, Green for Sign In/Login).

2. Form & Interaction Features
Client-Side Validation: All necessary inputs are validated before attempting submission (e.g., checks run when the user blurs an input or clicks the submit button).
Required Field Check: Ensures no field is left blank.
Real-time Feedback on Blur: Errors are checked and displayed immediately when the user moves focus away from an input field.
Inline Error Messages: Validation errors appear directly below the corresponding input field, using a smooth transition (`error-message.show`) to avoid jarring layout shifts.
Input Error Highlighting: Invalid input fields are visually marked with a red border for immediate user correction.
Non-Blocking Notifications: Uses a custom `message-box` (green for success, red for failure) instead of the browser's intrusive `alert()` function.
Data Capture: Successfully validated form data is captured as a JavaScript object and logged to the browser console (simulating data ready for API submission).

3. Validation Logic Highlights
Email Validation: Checks for a valid email structure (e.g., `user@domain.com`).
Strong Password Enforcement (Sign Up): Requires the password to meet several criteria for security:
    * Minimum 8 characters.
    * Must include at least one uppercase letter.
    * Must include at least one lowercase letter.
    * Must include at least one number.
    * Must include at least one special character (`!@#$%^&*()_+`).
Password Confirmation: Ensures the "Confirm Password" field exactly matches the "Password" field during sign-up.
![4](https://github.com/user-attachments/assets/124c128a-1353-43fc-95b2-b2cf25209e85)
![3](https://github.com/user-attachments/assets/0939d2d4-b8b2-4cca-bc26-fc0b6ad3e2a7)
![2](https://github.com/user-attachments/assets/c2402040-b3a0-4bc8-aeec-42edf68c04b0)
![1](https://github.com/user-attachments/assets/db7ade68-0b8f-4e61-9dbc-705fa5882178)























a secure Logout.
