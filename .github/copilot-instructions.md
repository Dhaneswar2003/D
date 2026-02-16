# Copilot Instructions for Login Form Project

## Project Overview
A minimal login page with HTML form and basic styling. This is a static frontend-only project with no backend integration or build process currently implemented.

## Current Structure
- **index.html** - Main login form with email/password fields, remember-me checkbox, and footer links (Forgot Password, Sign Up)
- **style.css** - Referenced but not yet created; should contain styles for `.login-container`, `.login-box`, `.form-group`, `.login-btn`, and `.footer-links`

## Key Patterns & Conventions

### Form Structure
- Uses semantic HTML with `<form id="loginForm">` to allow JavaScript event handling
- Email and password inputs have `required` attribute for basic client-side validation
- Form groups use consistent `.form-group` class structure

### JavaScript Integration
- Event listener pattern: `document.getElementById('loginForm').addEventListener('submit', function(e) { e.preventDefault(); ... })`
- Currently shows placeholder alert; production implementation should integrate with backend authentication

### Styling Approach
- CSS classes follow BEM-like naming: container, box, form-group, login-btn, footer-links
- External stylesheet reference in `<head>` tag

## Development Notes
- The project is incomplete: `style.css` is referenced but doesn't exist
- Form submission currently has no backend integration
- No form validation beyond HTML5 `required` attribute
- No error handling or success feedback UI

## Next Priority Tasks
1. Create `style.css` with responsive design for the login container
2. Implement actual form validation (email format, password strength)
3. Add UI feedback states (loading, error messages, success)
4. Connect to authentication backend when available
