# Frontend checklist

This is a technology stack agnostic checklist and therefore it does not care about what framework you decide to use.

## Why?

Frontend is extremely complicated. There are (too) many topics to cover for a single person as part of a development team.
This checklist helps reducing the failure by compensating for potential limits and human memory and attention. It helps
to ensure consistency and completeness.

## Table of contents

- [Head](#head)
- [Performance](#performance)
  - [Images](#images)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [Fonts](#fonts)
  - [Scripts](#scripts)
- [Accessibility](#accessibility)
- [SEO](#seo)
- [Security](#security)
- [Progressive Web App](#progressive-web-app)
- [References](#references)
- [License](#license)

## Head
- [ ] **Viewport meta tag** is declared correctly `<meta name="viewport" content="width=device-width, initial-scale=1">`
- [ ] **Language attribute** `<html lang="en">`
- [ ] **Favicon** is set and displayed correctly
- [ ] **Title** is used on all pages
- [ ] **Description meta tag** is used on all pages and unique for each page
## Performance

### Images

- [ ] **WebP** is used to transform images to reduce filesize
- [ ] **CDN** is used to transform, optimize and deliver images
- [ ] **Responsive** images are served and use srcset and sizes attributes to serve images to different display densities
- [ ] **Dimensions** (height and width attributes) are set on images to improve page load time
- [ ] **Imagemin** is used to compress images
- [ ] **GIF's** are replaced by video for faster page loads
- [ ] **Lazy-loading** is done for all applicable image

### HTML

### CSS
- [ ] **Minification** is done for all files

### JavaScript
- [ ] **Minification** is done for all files

### Fonts

### Scripts
## Acessibility

## SEO

## Security

## Progressive Web App

## References

- 📚 [Google Developers - Web.dev vitals](https://web.dev/vitals/)
- 📚 [Google Developers - Web Fundamentals](https://developers.google.com/web/fundamentals)

## Licenses

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details