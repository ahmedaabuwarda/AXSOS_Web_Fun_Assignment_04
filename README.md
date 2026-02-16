# Registration Form Assignment 04

A simple HTML registration form created as part of the AXSOS Web Fundamentals course (Week 03, Lecture 04).

## Overview

This project demonstrates the creation of an interactive user registration form using HTML5. The form includes various input types and collects essential user information for account creation.

## Features

- **Required Fields** (marked with *):
  - First Name
  - Last Name
  - Email Address
  - Password
  - Confirm Password

- **Optional Fields**:
  - Birthday (date picker)
  - Gender Identity (radio buttons)
  - Personal Description (textarea)
  - Favorite Programming Language (dropdown selection)
  - Email Updates Subscription (checkbox)

## Form Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| First Name | Text | ✓ | User's first name |
| Last Name | Text | ✓ | User's last name |
| Email Address | Email | ✓ | User's email address |
| Password | Password | ✓ | User's account password |
| Confirm Password | Password | ✓ | Password confirmation |
| Birthday | Date | ✗ | User's date of birth |
| Gender Identity | Radio | ✗ | Options: Male, Female, Non-binary, Prefer not to answer |
| Description | Textarea | ✗ | Short bio/description about the user |
| Favorite Language | Dropdown | ✗ | Options: JavaScript, Python, Java |
| Email Updates | Checkbox | ✗ | Opt-in for periodic email updates |

## How to Use

1. Open `index.html` in a web browser
2. Fill in the required fields (marked with *)
3. Optionally fill in additional information
4. Click the "Create Account" button to submit the form

## Files

- `index.html` - Main HTML file containing the registration form

## Technologies Used

- HTML5
- Form inputs (text, email, password, date, radio, checkbox, select, textarea)

## Notes

- All required fields use HTML5 validation attributes
- The form currently uses `method="GET"` and `action="#"` - these can be updated to point to a backend service for actual form processing
- No CSS styling is included - styling can be added as needed
- No client-side JavaScript validation is implemented - server-side validation is recommended

## Assignment Details

- **Course**: AXSOS Web Fundamentals
- **Week**: 03
- **Lecture**: 04
- **Topic**: HTML Forms and Input Elements
