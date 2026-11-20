# Activity 5 – AI Tools: Hot Wheels Marketplace Website

## Overview
This activity explores how the quality and specificity of a prompt affect an AI-generated website. Two prompts were tested using an AI tool: an initial general request and an improved request with clear project details and functional requirements.

## Objective
To use an AI tool to generate a website and evaluate how improving a prompt can produce an output that is more relevant to the intended project.

## Project Description
The improved prompt requested a Hot Wheels marketplace website using the Hot Wheels-inspired flame-red, orange, yellow, and dark-charcoal color palette. The requested website was organized into four pages:

- **Home** – an introductory page about Hot Wheels.
- **Marketplace** – a product area where users can browse items and add them to a cart.
- **2025 Cases** – a page showing Hot Wheels cases released during the year.
- **Cart** – a page for reviewing selected items and proceeding to checkout.

The documented functionality includes adding items to the cart, removing items, displaying a live cart count, retaining cart contents across pages and refreshes using browser local storage, and showing a checkout confirmation.

## Prompts and AI Outputs

### 1. Original Prompt
> make me a website code

The first prompt produced a simple, generic landing page with a heading, text, and a button. Although the code was readable and functional as a basic page, it did not address the specific Hot Wheels marketplace concept.

### 2. Improved Prompt
> make me a website code for a marketplace for hotwheels, use the colors of the hotwheels branding, make one page about hotwheels and one for the marketplace where customers can add to cart and check out. Also put a page where customers can see which hotwheels case is released this year.

The improved prompt gave the AI clearer requirements about the website's subject, branding, pages, and shopping-cart features. The resulting output was more closely aligned with the intended project.

## Comparison and Evaluation
The improved prompt produced the stronger result.

- **Relevance:** Output 1 was a generic landing page, while Output 2 directly addressed the Hot Wheels marketplace.
- **Organization:** Output 2 separated the website into multiple files/pages and described the role of each page.
- **Functionality:** Output 2 documented product listings, cart management, a live cart count, local-storage persistence, checkout confirmation, and a released/upcoming case list.
- **Usefulness:** Output 2 provided a more substantial starting point that could be extended, while Output 1 would require major redevelopment to meet the project requirements.

## Key Learning
A prompt should clearly communicate the purpose of a project, its intended users, design direction, required pages, and expected functionality. A broad prompt may produce a technically valid result that does not solve the intended problem. Adding specific requirements helps guide the AI toward a more useful output. AI-generated code should still be reviewed and tested before being used.

## Reflection
This activity helped me understand the importance of writing clear and detailed prompts when using AI tools to generate a website. The first prompt produced only a basic landing page because it lacked specific instructions. After improving the prompt by describing the Hot Wheels marketplace, its branding, pages, and shopping-cart features, the output became more relevant and useful. I learned that the quality of an AI-generated result depends greatly on how well the task is explained. Overall, this activity improved my ability to communicate project requirements and evaluate AI-generated website outputs.

## Evidence
The accompanying activity documentation PDF contains screenshots of the original prompt, improved prompt, generated code/output, and the comparison of both results.

## Note on Source Files
The submitted documentation contains screenshots of code rather than a complete set of downloadable website source files. Add the actual website source files (for example, `index.html`, `marketplace.html`, `cases.html`, `cart.html`, `style.css`, and `app.js`) to this folder if you have them. Do not treat screenshots of code as a substitute for the complete, tested source files.
