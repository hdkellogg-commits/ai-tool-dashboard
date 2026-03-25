# ai-tool-dashboard
An interactive, single-page HTML dashboard for organizing and managing personal AI development tools and technical documentation

## How to Add New Tools
To maintain a consistent layout and ensure the dashboard remains easy to navigate, please follow these formatting guidelines when adding new entries to the `index.html` file.

### 1. Update the Summary Table
Add a new row `<tr>` to the top-level tool table. Use the following structure:
* **Tool Name:** Linked to the official site or implementation detail anchor.
* **Primary Purpose:** A 2–4 word high-level category (e.g., "Data Acquisition").
* **Key Features:** A concise bulleted list of 2–3 core capabilities.

### 2. Add Implementation Details
Create a new `<div>` or `<section>` below the table with a corresponding `id` for internal linking.
* **Heading:** Use `<h3>` for the tool name and include any internal project references in parentheses.
* **Description:** A brief paragraph (3–5 sentences) explaining the tool's specific value proposition and how it integrates into the workflow.

### 3. Styling Guidelines
* **Links:** Use the primary accent color defined in the CSS (e.g., `#1a73e8`).
* **Consistency:** Ensure all descriptions use "Active Voice" (e.g., "Manipulates video manifests" instead of "The video manifests are manipulated by...").

---
*Created for personal AI workflow management.*
