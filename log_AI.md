### AI Usage Log

- **Student Name:** Mai Long Thien
- **Course:** Web Application Development
- **Assignment:** Assignment 1 - Personal Portfolio
- **AI Tool Used:** ChatGPT (Model: GPT-4)

#### 1. Advanced Form Elements

- **Prompt to AI:**
  > "I need to add more input types to my HTML contact form. Can you give me examples for a `<select>` dropdown for a contact reason, a group of `radio` buttons for a preferred contact method, and a required `checkbox` for agreeing to a policy?"
- **How I Modified/Used the Output:**
  - I used the provided HTML structure as a reference.
  - I changed the `name`, `id`, and `for` attributes to match my form's naming convention.
  - I wrote my own `<option>` values for the select dropdown to match the context of my portfolio (e.g., "Job Opportunity", "Collaboration").
  - I added my own `<label>` text and linked the policy checkbox to my `policy.html` page.

#### 2. Accessibility Features

- **Prompt to AI:**
  > "What are the correct ARIA attributes to use for a mobile navigation toggle button? Explain `aria-expanded` and `aria-controls`."
- **How I Modified/Used the Output:**
  - The AI explained that `aria-controls` should link the button to the navigation menu's `id`, and `aria-expanded` should be toggled between `true` and `false` by JavaScript to indicate the menu's state.
  - This explanation helped me understand _why_ I was adding these attributes, not just how. I then correctly implemented them in my `header` and `main.js` file.

#### 3. Documentation (README file)

- **Prompt to AI:**
  > "Please create a template for a `README.md` file for my student portfolio project. Include sections for a live demo link, key features, a sitemap, instructions to run locally, and a section for credits and attributions."
- **How I Modified/Used the Output:**
  - The AI generated a well-structured Markdown template.
  - I used this template as a starting point. I wrote all the content myself to accurately describe my specific project's features, sitemap, and the actual sources for my images. The AI provided the structure, but the content is my own.

#### 4. General Code Refinement & Idea Generation

- **Prompts to AI:**
  - "Is there a more semantic HTML tag I can use here instead of a `div`?"
  - "What are some common color palettes for a developer portfolio?"
  - "Proofread this paragraph for my 'About Me' page for grammar and clarity."
- **How I Modified/Used the Output:**
  - For these general queries, I used the AI's suggestions as inspiration. I evaluated its advice (e.g., using `<article>` instead of `div`) and implemented it only when it made sense for my project's structure and goals. I used its grammar checks to improve the professionalism of my written content.
