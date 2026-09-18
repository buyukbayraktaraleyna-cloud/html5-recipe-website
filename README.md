# Delicious Recipes Kitchen

## Theme
The website represents an online culinary platform named "Delicious Recipes Kitchen". It offers simple, homemade recipe guides, baking tips, and nutritional insights. It also includes an interactive submission form where users can send their own recipes or reach out with culinary questions.

## File Organization
The project is built purely with semantic HTML5 elements without any CSS or JavaScript. The directory structure is organized as follows:

- `index.html`: The home page containing the site header, navigation menu, two featured recipe articles with images, and the footer.
- `about.html`: The background story and philosophy of the kitchen, featuring semantic tags (`<time>`, `<mark>`, `<blockquote>`, `<aside>`, `<details>`) and a captioned kitchen figure (`<figure>`, `<figcaption>`).
- `services.html`: A nutritional and recipe overview presented in a structured HTML table with headers (`<thead>`), data rows (`<tbody>`), and summary rows (`<tfoot>`).
- `contact.html`: A functional contact and recipe submission form utilizing `<fieldset>`, `<legend>`, labeled inputs (text, email, date), a select dropdown menu, a textarea, and a submit button.
- `assets/`: Folder holding all media files (`lasagna.jpg`, `brownie.jpg`, `kitchen.jpg`).
- `README.md`: Project summary, structural breakdown, and technical reflection.

## Challenges Faced
- **Designing Without CSS:** Creating an organized, readable layout exclusively using raw HTML5 tags required careful structuring with headings, horizontal rules (`<hr>`), and semantic tags to keep sections visually intuitive without stylesheets.
- **Form & Table Semantics:** Ensuring all structural requirements were met strictly according to standards, such as associating every `<input>` properly with its `<label>` via `for` attributes, and structuring the data table with `<thead>`, `<tbody>`, and `<tfoot>`.
- **Consistent Relative Linking:** Setting up identical, functional relative navigation links across all four files so that users can seamlessly navigate back and forth without broken paths.