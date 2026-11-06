# Backlog — CV público (GitHub Pages)

## Pendientes

- [ ] Al actualizar el CV: reemplazar `Carlos_Cardenas_CV_2026.pdf`, regenerar `page-*.png` (PyMuPDF, matrix 2.2x) y push.
- [x] 6-nov-2026: agregada sección RECENT COURSES (Platzi Kubernetes, Docker Avanzado, Java SE Avanzado) en pág. 2 con pymupdf + subset_fonts.
- [ ] Opcional: dominio propio (cv.cardenas.pe) vía CNAME si se quiere URL corta.

## Decisiones tomadas

- Página estática mínima: solo el CV (imágenes de las páginas, nítidas en móvil) + botón de descarga del PDF. Sin nada más.
- Las páginas se sirven como PNG porque los PDF embebidos fallan en móvil (iOS Safari).
- Repo público `cv` → https://unimauro.github.io/cv/ (no tocar unimauro.github.io, que es el portafolio con build.py).
