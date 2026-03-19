# index.html - Student Information Form

## Overview
This is a static HTML page featuring a simple, responsive **Student Information Form**. It collects essential student details with client-side validation and basic styling. Ideal for educational/training projects demonstrating HTML forms.

## Features
- **Form Fields**:
  | Field | Type | Required | Description |
  |-------|------|----------|-------------|
  | Full Name | text | Yes | Student's full name |
  | Age | number | Yes | Student's age |
  | Email | email | Yes | Contact email |
  | Phone Number | tel | No | Phone contact |
  | Address | textarea | No | Home address (multi-line) |
  | Parent/Guardian Name | text | No | Guardian details |
  | Emergency Contact | tel | No | Backup phone |

- **Interactive Elements**:
  - **Submit Button**: Triggers form submission (action="#", no backend).
  - **Reset Button**: Clears all fields.
  - **Hover Effect**: Message paragraph turns red on mouseover.
  - **Click Effect**: Secondary paragraph turns blue on click.

- **Design**:
  - Centered layout with bisque background.
  - Aliceblue form container with border and rounded corners.
  - Custom CSS (inline `<style>`): Lucida Sans font-family, responsive container (750px max-width).
  - Header: "Student Information Form" with horizontal rule.

## Technologies Used
- **HTML5** with semantic form structure.
- **CSS3** (inline styles): Responsive design, hover/click interactions.
- **JavaScript**: Empty `<script>` block (room for validation/handling).
- Fully static – no external dependencies.

## How to Run/Preview
1. Open `index.html` in any web browser.
2. Fill form fields and test Submit/Reset.
3. Hover/click demo paragraphs for JS effects.
4. Mobile-friendly (viewport meta).

## Usage Notes
- Form submits to `#` (placeholder). Add backend (PHP/Node.js) for real submission.
- No JS validation implemented yet – add to `<script>` (e.g., age > 0).
- Inline styles for simplicity; extract to external CSS for production.

## Project Context
Part of training portfolio with: `blog.html` (ecommerce), `tailwind.html`, etc. Complements README.md (blog-focused).
