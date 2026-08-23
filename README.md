# Dashing Boards

One dashboard. Many identities.

Dashing Boards is a CSS Zen Garden–inspired showcase of how dramatically CSS can transform the same HTML. Every submission styles the shared `dashboard.html` without changing its structure or content.

## Contributing a design

1. **Fork** this repository and clone your fork.
2. Make a copy of `empty.css`.
3. Add your design to the copied stylesheet. Do not change the dashboard’s HTML structure.
4. Rename the stylesheet to the title of your submission, using a `.css` extension—for example, `cosmic-candy.css`.
5. Add your design to the stylesheet selector in `index.html`. Inside the existing `<fieldset>`, add:

   ```html
   <label>
     <input type="checkbox" data-stylesheet="cosmic-candy.css">
     cosmic-candy.css
   </label>
   ```

   Replace `cosmic-candy.css` with your stylesheet’s exact filename in both places.

6. Open `index.html` locally, enable your stylesheet, and confirm that it loads and remains usable at different screen sizes.
7. Commit both your new CSS file and the updated `index.html`, push them to your fork, and submit a pull request.

Your pull request should include a short description of the design and, if possible, a screenshot.

## The rule

Transform the dashboard through CSS alone. The only permitted change to `index.html` is adding the `<label>` that makes your stylesheet available in the demo.

## License

MIT
