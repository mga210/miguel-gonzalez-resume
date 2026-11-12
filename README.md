# Miguel Gonzalez — Resume

Professional HTML resume, deployed via GitHub Pages. Content synced from `mg/content.json`.

**Live:** https://mgsystemsdev.github.io/resume-MG/

Use the segmented control to switch variants (Implementation / Product / Program / Solutions / Operations). Word download always matches the variant on screen. Deep link with `?v=product` (etc.).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Resume (web + print) with live variant switcher |
| `Miguel_Gonzalez_Resume.docx` | Implementation |
| `Miguel_Gonzalez_Resume_Product.docx` | Product |
| `Miguel_Gonzalez_Resume_Program.docx` | Program |
| `Miguel_Gonzalez_Resume_Solutions.docx` | Solutions |
| `Miguel_Gonzalez_Resume_Operations.docx` | Operations |
| `_config.yml` | GitHub Pages config |

## Local preview

```bash
python3 -m http.server 8080
```

## Deploy

Push to `main`. GitHub Pages serves the root folder automatically.
