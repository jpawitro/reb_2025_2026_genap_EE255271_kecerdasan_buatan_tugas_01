# Tugas Review Jurnal AI

Dokumen ini berisi hasil review jurnal:
**"Review of artificial intelligence applications in engineering design perspective"**
dengan penyesuaian personal berdasarkan pengalaman penulis.

## File Utama

- `review_jurnal_ai_joko_pawitro_6022251005.tex` → source LaTeX utama
- `review_jurnal_ai_joko_pawitro_6022251005.pdf` → hasil akhir PDF
- `references.bib` → daftar pustaka (BibTeX)
- `ITS_pojok.pdf` → aset logo/header

## Cara Kompilasi (1 Baris)

Jalankan perintah berikut di root folder project:

```bash
pdflatex -interaction=nonstopmode review_jurnal_ai_joko_pawitro_6022251005.tex && bibtex review_jurnal_ai_joko_pawitro_6022251005 && pdflatex -interaction=nonstopmode review_jurnal_ai_joko_pawitro_6022251005.tex && pdflatex -interaction=nonstopmode review_jurnal_ai_joko_pawitro_6022251005.tex
```

## Kompilasi Ulang Cepat

Jika referensi tidak berubah, cukup jalankan:

```bash
pdflatex -interaction=nonstopmode review_jurnal_ai_joko_pawitro_6022251005.tex
```

## Catatan Repository

File/folder berikut sudah diatur agar tidak ikut terunggah melalui `.gitignore`:

- `.venv/`
- `references/template` (symlink)
- `references/plans` (symlink)
- file sementara hasil kompilasi LaTeX (`*.aux`, `*.log`, dll.)
- `.DS_Store`
