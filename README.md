# strukdat8

Praktikum Struktur Data - Visualisasi Data (Matplotlib + Streamlit), dikelola dengan [uv](https://docs.astral.sh/uv/).

## Isi

| File | Keterangan |
|---|---|
| `praktikum1.py` | Kegiatan Praktikum 1: visualisasi data penjualan dari file Excel |
| `praktikum2.py` | Kegiatan Praktikum 2: visualisasi data Pokémon dari PokeAPI |
| `penjualan.xlsx` | Data untuk Praktikum 1 (unggah lewat aplikasi) |

## Menjalankan

```bash
uv sync
uv run streamlit run praktikum1.py
uv run streamlit run praktikum2.py
```

## Cara project ini dibuat

```bash
uv init strukdat8
cd strukdat8
uv add pandas streamlit openpyxl matplotlib requests
```

## Push ke GitHub

```bash
git add .
git commit -m "Praktikum 8: visualisasi data"
git branch -M main
git remote add origin https://github.com/<username>/strukdat8.git
git push -u origin main
```
