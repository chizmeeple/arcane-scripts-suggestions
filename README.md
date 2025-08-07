# Blood on the Clocktower - Storyteller Phrases

A simple website providing helpful phrases and suggestions for Blood on the
Clocktower storytellers. Similar to [Savant](https://savant.thegrim.gg/) but
supporting multiple characters.

## Features

- **Dark Theme**: Easy on the eyes during night games
- **Character-Specific Pages**: Dedicated sections for different characters
- **Interactive Elements**: Click to copy phrases, random phrase generator
- **Mobile Responsive**: Works well on phones and tablets
- **GitHub Pages Ready**: Simple HTML/CSS/JS that can be hosted anywhere

## Characters

- **Yaggababble** ✅ Available
- **Savant** 🔄 Coming Soon
- **Amnesiac** 🔄 Coming Soon
- **Wizard** 🔄 Coming Soon

## Local Development

Simply open `index.html` in your browser to view the site locally. No build
process required!

## Deployment to GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose your main branch (usually `main` or `master`)
5. Select the root folder (`/`)
6. Click Save

Your site will be available at
`https://[username].github.io/[repository-name]`

## Custom Domain Setup

To use a custom domain like `suggestions.arcane-scripts.net`:

1. Add a `CNAME` file to the root with your domain:

   ```text
   suggestions.arcane-scripts.net
   ```

2. Configure your DNS provider to point to GitHub Pages:

   - Type: `CNAME`
   - Name: `suggestions` (or `@` for root domain)
   - Value: `[username].github.io`

3. In GitHub repository settings → Pages, add your custom domain

## Adding New Characters

1. Create a new HTML file (e.g., `savant.html`)
2. Copy the structure from `yaggababble.html`
3. Update the character name, description, and phrases
4. Add a link to the new page in `index.html`
5. Update the status from "Coming Soon" to "Available"

## File Structure

```text
├── index.html          # Main page with character links
├── yaggababble.html    # Yaggababble character page
├── README.md           # This file
└── [future character pages]
```

## Contributing

Feel free to add more phrases, characters, or improve the design. The site is
intentionally simple to maintain and deploy easily.

## License

This project is open source and available under the MIT License.
