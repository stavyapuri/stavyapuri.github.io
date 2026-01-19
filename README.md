# Stavya Puri - Personal Website

A modern, research-oriented personal academic website built with HTML, CSS, and JavaScript.

## Features

- Modern, clean design with research-focused aesthetics
- Light/Dark mode toggle with persistent preference
- Fully responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Interactive quantum atom animation
- Sections: About, Research Interests, Publications, Experience, Education, Skills, Achievements, Contact

## Deployment on GitHub Pages

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select the **main** branch and **/ (root)** folder
   - Click **Save**

3. **Access your site:**
   - Your website will be live at `https://stavyapuri.github.io`

## File Structure

```
├── index.html      # Main HTML file
├── styles.css      # All CSS styles including themes
├── script.js       # JavaScript for interactions
├── Stavya_Puri_CV.pdf  # Resume/CV file
└── README.md       # This file
```

## Customization

### Colors
The color scheme uses orange accents. To change the accent color, modify the CSS variables in `styles.css`:

```css
:root {
    --accent-primary: #f97316;    /* Main accent */
    --accent-secondary: #fb923c;  /* Secondary accent */
    --accent-tertiary: #fdba74;   /* Tertiary accent */
}
```

### Content
Update the content directly in `index.html`:
- Personal information in the hero section
- Research interests in the research cards
- Publications in the publications section
- Experience in the timeline
- Skills and achievements in their respective sections

## License

This website template is free to use and modify for personal use.
