# Sudip Adhikari | EEE Engineer Portfolio

A responsive, single-page portfolio for Sudip Adhikari, an Electrical and Electronics Engineering student focused on power electronics, motor control, VFD design, and industrial automation.

## Highlights

- Engineering-focused visual design with a dark green, copper, and signal-teal palette.
- Live PWM waveform canvas with animated duty-cycle sweep and SPWM reference trace.
- Three floating animated background blobs for depth.
- Scroll progress indicator and scroll-reveal animations.
- Click or press Enter/Space on portfolio boxes to activate a signal glow.
- Responsive navigation and layouts for desktop, tablet, and mobile.
- No build step or framework required. The site is a static GitHub Pages project.

## Project Structure

```text
.
├── index.html   # Complete portfolio: markup, styles, and JavaScript
└── README.md    # Project documentation
```

## Run Locally

Open `index.html` directly in a browser, or start a local static server:

```bash
python -m http.server 4173
```

Then visit <http://localhost:4173>.

## GitHub Pages

1. Open the repository settings on GitHub.
2. Select **Pages** under **Code and automation**.
3. Choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Save and wait for the deployment to complete.

The expected site URL is:

<https://ujjwal540.github.io/sudip-adhikari-client-portfolio/>

## Customization

Edit the content and inline CSS directly in `index.html`. The primary design tokens are defined in the `:root` block near the top of the file. External Google Fonts are loaded from the document head; the page otherwise has no runtime dependencies.

## Contact

- Email: callmesudip729@gmail.com
- GitHub: <https://github.com/sudipadhikari729-dotcom>
- LinkedIn: <https://www.linkedin.com/in/sudip-adhikari-749857374/>
