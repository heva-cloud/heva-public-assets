# Contributing to Heva Public Assets

Thank you for your interest in contributing to Heva's public assets repository!

## How to Contribute

### Adding New Assets

1. **Fork the Repository**
   ```bash
   git clone https://github.com/heva-cloud/heva-public-assets.git
   cd heva-public-assets
   ```

2. **Create a New Branch**
   ```bash
   git checkout -b add-new-assets
   ```

3. **Add Your Assets**
   - Place files in the appropriate directory (`logos/`, `icons/`, or `pictos/`)
   - Follow the naming conventions (see below)
   - Ensure files are optimized for web use

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add: [description of assets]"
   ```

5. **Push and Create a Pull Request**
   ```bash
   git push origin add-new-assets
   ```

## Asset Guidelines

### File Formats

**Recommended Formats:**
- **Vector:** SVG (preferred), AI, EPS
- **Raster:** PNG (for transparency), JPG (for photos)

### File Naming Conventions

- Use lowercase letters only
- Use hyphens (-) to separate words
- Be descriptive but concise
- Include variant/size when applicable

**Examples:**
- ✅ `heva-logo-primary.svg`
- ✅ `cloud-icon-48x48.png`
- ✅ `dashboard-picto-dark.svg`
- ❌ `HevaLogo.svg`
- ❌ `icon_1.png`
- ❌ `NEW PICTO.svg`

### File Optimization

- **SVG files:** Remove unnecessary metadata and comments
- **PNG files:** Compress without losing quality (use tools like TinyPNG)
- **JPG files:** Use appropriate quality settings (80-90%)
- Keep file sizes reasonable for web use

### Directory Structure

```
logos/
  ├── primary/        # Primary brand logos
  ├── secondary/      # Alternative logos
  └── variants/       # Special variants (dark mode, monochrome, etc.)

icons/
  ├── app/           # Application icons
  ├── ui/            # User interface icons
  └── social/        # Social media icons

pictos/
  ├── illustrations/ # Illustration elements
  └── graphics/      # Graphic elements
```

## Quality Standards

- Assets should be clean and professional
- Vector files should be properly structured with named layers
- Raster files should be high resolution (at least 72 DPI for web)
- All assets should follow Heva's brand guidelines

## Pull Request Guidelines

When submitting a pull request:
- Provide a clear description of what assets you're adding
- Explain the use case or context for the assets
- List all files being added
- Ensure no copyrighted or licensed materials are included without permission

## Questions?

If you have questions about contributing, please open an issue or contact the Heva team.
