# Dog vs Cat Classifier - Web Interface

A simple web application to classify images as dogs or cats using machine learning.

## Deployment

This project is deployed on GitHub Pages at: `https://NarayanSMore7114.github.io/dwm-pbl/`

### To Deploy:

1. **Create a GitHub repository** named `dwm-pbl` under NarayanSMore7114
2. **Push this code** to GitHub:
   ```bash
   git remote add origin https://github.com/NarayanSMore7114/dwm-pbl.git
   git branch -M main
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose branch: `main`
   - Choose folder: `/ (root)`
   - Click Save

4. **Access your site**: After a few seconds, visit `https://NarayanSMore7114.github.io/dwm-pbl/`

## Note

The prediction API endpoint (`/predict`) won't work with static GitHub Pages hosting alone. To use the full functionality, you'll need to:
- Deploy the Flask backend separately (Heroku, AWS, etc.)
- Update the API endpoint in `index.html`

For testing locally, run:
```bash
python main.py
```

Then visit `http://localhost:5000`
