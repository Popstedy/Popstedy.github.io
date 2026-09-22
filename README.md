a/code/Popstedy.github.io/README.md → b/code/Popstedy.github.io/README.md
@@ -0,0 +1,61 @@
+# Popstedy.github.io
+
+Lični sajt — blog, portfolio, landing — hostovan na GitHub Pages.
+
+**URL:** `https://popstedy.github.io`
+
+---
+
+## Šta je ovo
+
+Staticki sajt sa tri sekcije:
+
+| Sekcija | Opis |
+|---------|------|
+| **Blog** | Tekstualni sadržaj — vodiči, postovi, case studije |
+| **Portfolio** | Projekti i radovi (u gradnji) |
+| **Landing** | Početna sa produktnim CTA (Lemon Squeezy) |
+
+Stil: terminal/cyberpunk — tamno, mono font, zelena akcentsna boja (`#00ff41`).
+
+---
+
+## Struktura
+
+```
+Popstedy.github.io/
+├── index.html          # Landing / početna stranica
+└── blog/
+    └── post.html       # Blog članak (Ollama + OpenClaw vodič)
+```
+
+## Ubricavanje
+
+1. Kreiraj novi `.html` fajl u `blog/` (ili direktno u root za landng update)
+2. Commit + push na `main` granu
+3. GitHub Pages automatski rebuilduje — sadržaj je live za ~1-2 minuta
+
+```bash
+git add .
+git commit -m "Update: ..."
+git push origin main
+```
+
+## Tehnički detalji
+
+- **Host:** GitHub Pages
+- **Branch:** `main`
+- **URL:** `https://popstedy.github.io`
+- **Custom domen:** `opsblueprint.rs` (u planu — registracija kroz WebHostingSrbija)
+- **Font:** JetBrains Mono / Fira Code / Cascadia Code (fallback: monospace)
+- **Boje:** `--bg: #0d0d0d`, `--accent: #00ff41`
+
+## Produkt (Lemon Squeezy)
+
+Lični vodič / digitalni proizvod dostupan preko Lemon Squeezy. Checkout link na landing page.
+
+---
+
+**Autor:** Popstedy  
+**Blog:** anddidyouknow.blogspot.com  
+**GitHub:** github.com/Popstedy
