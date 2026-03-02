# Rukshin Portfolio

Static personal portfolio site served with Nginx in Docker.

## Project structure

- `public/index.html` - main page
- `public/avatar.png` - favicon
- `public/rukshin.png` - profile image
- `public/RukshinSanyal2025.pdf` - resume
- `public/SamarpanTranslationCertificate.pdf` - certificate
- `Dockerfile` - container image definition

## Run locally with Docker

```bash
docker build -t rukshin-portfolio .
docker run --rm -p 8080:80 rukshin-portfolio
```

Open `http://localhost:8080`.
