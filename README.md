# mailify.rfc
Submissions repository for `ASOC14` - [https://github.com/acm-avv/mailify.rfc](https://github.com/acm-avv/mailify.rfc)

> [!NOTE]
All discussions regarding `ASOC14: Drag-n-Drop HTML Email Template Builder` shall take place in https://github.com/orgs/acm-avv/discussions/4.

## Overview
In-order to be eligible to work on this project as **Request for Code** under the banner of **Amrita Summer of Code, 2025**, you are required to form a team of size 1-4 and have all the members register at [amsoc.vercel.app](https://amsoc.vercel.app)

## Project Manager Details
```json
"Name": "Kiran Rajeev, Revanth Singothu",
"Year": "3rd and 4th",
"Roll": "CB.SC.U4CSE23624, CB.EN.U4CSE22149",
"GitHub": "@Kiran-Rajeev-KV, @rev-sin",
```

## How to Apply
Type out a message in https://github.com/orgs/acm-avv/discussions/4 with the following details:
1. Team Name
2. Team Members' Names, Roll-Numbers and respective GitHub usernames
3. Tag the project manager as **@username**

## Guidelines
1. Keep all discussions limited to this discussion channel by tagging the project manager via **@username**
2. Do not try to contact the project manager personally unless they are open to it.
4. Maintain decorum and avoid any misbehavior with the project manager. This can be subjected to disqualification.
5. Send us an update every week with regards to your progress for your respective project. If we do not receive an update for more than 10 days then your team will be disqualified automatically.

## Project Description
This project aims to develop a user-friendly, browser-based email template editor, inspired by platforms like Stripo.email. The core goal is to provide a seamless, no-signup experience for creating and exporting beautiful email templates directly within the browser, leveraging client-side storage and APIs.

### Core Goals:
**No-Nonsense Experience**: Allow users to start creating templates immediately without any registration or login.
**Browser-Only Functionality**: Ensure the entire application, including editing, saving, and conversion, operates solely within the user's web browser.
**Beautiful Templates**: Enable the creation of visually appealing and responsive email templates.

### Key Features:
- Intuitive Drag-and-Drop Editor:
    - Provide a highly interactive interface for assembling email layouts.
    - Allow users to drag and drop various content blocks (e.g., text, images, buttons, social media links, dividers) onto the canvas.
    - Enable easy rearrangement and customization of these blocks.
- Client-Side Data Persistence:
    - Utilize localStorage or other browser-based storage mechanisms (e.g., IndexedDB) to save user drafts automatically.
    - Ensure that templates persist across browser sessions without requiring a server-side database.
- Browser API-Driven Conversion Engine:
    - Implement the entire email template conversion and export logic using only Browser APIs. This means no server-side processing for generating the final HTML.
    - Support export formats suitable for email clients (e.g., clean HTML with inline CSS).
- Pre-built Templates:
    - Include a selection of ready-to-use templates for common use cases, such as:
        - Simple Event Invitations
        - Newsletter Layouts
        - Promotional Emails
