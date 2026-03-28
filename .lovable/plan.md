

## Plan: Deploy Ife Portfolio HTML as a Single Page

The uploaded file `ife_portfolio_light.html` is a complete, self-contained HTML page (743 lines) with inline CSS and JS. The goal is to render it exactly as-is.

### Approach

1. **Copy the HTML file** to `public/ife_portfolio_light.html`
2. **Update `Index.tsx`** to render the HTML using a full-page iframe (`src="/ife_portfolio_light.html"`) with no border, 100vw/100vh dimensions
3. **Update `index.html`** title to "Ife Dare-Johnson, AI Product Portfolio"
4. **Clean up `App.css`** — remove default Vite styles that add padding/max-width to `#root`

This preserves the original HTML exactly — no content, layout, or styling changes.

