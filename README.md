# SPIRIT Smartphone – Assets Repository

<p align="center">
    <img src="https://github.com/user-attachments/assets/60e87523-02cf-482b-8433-5f611e48ca2d" width="40%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Purpose-Centralized%20Assets-blue">
  <img src="https://img.shields.io/badge/License-Open%20Source-green">
  <img src="https://img.shields.io/badge/Type-Resources-orange">
</p>

---

## About

This repository serves as a **centralized hub for shared assets** used across multiple GitHub repositories and projects. Instead of duplicating files across different projects, all commonly used resources are stored here and referenced by other repositories.

### Why Centralize Assets?
- **Reduce duplication** – One source of truth for shared resources
- **Easy maintenance** – Update assets in one place, used everywhere
- **Version control** – Track changes to assets over time
- **Consistent branding** – Ensure all projects use the same logos and images
- **Bandwidth efficiency** – Smaller individual repositories

---

## Repository Structure

```
assets/
├── imgs/
│   ├── design/          # Hardware design images and renderings
│   ├── logo/            # Project logos and branding assets
│   └── velectronics/    # V Electronics branded assets
├── CONTRIBUTING.md      # Guidelines for contributing assets
├── LICENSE             # License information
└── README.md          # This file
```

### Asset Categories

| Directory | Description | Contents |
|-----------|-------------|----------|
| **`imgs/design/`** | Hardware design visuals | PCB layouts, 3D renderings, component images |
| **`imgs/logo/`** | Project branding | Logos, icons, brand variants in multiple formats |
| **`imgs/velectronics/`** | Company branding | V Electronics logos, patches, and branded assets |

---

## Using Assets in Other Repositories

### GitHub Markdown (Recommended)
Reference assets directly using GitHub's raw content URLs:

```markdown
![Logo](https://raw.githubusercontent.com/username/assets/main/imgs/logo/logo-black-on-white.png)
```

### Git Submodules
For more complex integration, add this repository as a submodule:

```bash
git submodule add https://github.com/username/assets.git assets
git submodule update --init --recursive
```

### Direct Download
Download specific files when needed:

```bash
wget https://raw.githubusercontent.com/username/assets/main/imgs/logo/logo-variants.svg
```

---

## Current Assets

### Design Assets
- `alt3view26-12-2024.png` - Alternative hardware design view
- `headphonejack.png` - Headphone jack design rendering
- `pcblayout26-12-2024.png` - PCB layout visualization

### Logo Assets
- `logo-black-on-white.png` - Standard logo (black on white)
- `logo-github-black-on-white.png` - GitHub-optimized logo
- `logo-variants.svg` - Multiple logo variations in SVG format

### V Electronics Assets
- `V-logoclear.png` - Clear V Electronics logo
- `ve-ic-patch-logo.png` - IC patch logo design
- `ve-logo-cropped.png` - Cropped version of VE logo
- `ve-logo-text-clear.png` - Logo with clear text
- `ve-logo.png` - Standard VE logo
- `ve-original-logo.png` - Original VE logo design

---

## Contributing Assets

### Adding New Assets
1. **Choose the right directory** based on asset type
2. **Use descriptive filenames** (e.g., `logo-white-on-black-small.png`)
3. **Optimize file sizes** without compromising quality
4. **Include multiple formats** when appropriate (PNG, SVG, JPG)
5. **Update this README** to document new assets

### File Naming Conventions
- Use lowercase with hyphens: `my-asset-name.png`
- Include relevant descriptors: `logo-black-on-white-large.svg`
- Use appropriate extensions: `.png`, `.jpg`, `.svg`, `.pdf`

### Quality Guidelines
- **Images**: High resolution for print, optimized for web
- **Logos**: Provide both raster (PNG) and vector (SVG) formats
- **Screenshots**: Use consistent formatting and annotations
- **Diagrams**: Export in multiple formats when possible

---

## Projects Using These Assets

This repository provides assets for:
- Hardware design projects
- Software documentation
- Marketing materials
- Technical documentation
- Project websites and READMEs

*To add your project to this list, please update this README when referencing assets.*

---

## License

All assets in this repository are released under open-source licenses. See the [LICENSE](LICENSE) file for detailed information.

**Note:** Some assets may have different licensing requirements. Check individual file documentation or metadata for specific license information.

---

<p align="center">
  <strong>Centralized Assets – Powering Projects Across GitHub</strong>
</p>
