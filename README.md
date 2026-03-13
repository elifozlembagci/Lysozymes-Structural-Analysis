# lysozyme-structural-analysis

> 🇬🇧 [English](#english) | 🇹🇷 [Türkçe](#türkçe)

---

## English

### Structural Bioinformatics Analysis of Lysozyme (1HEL)

A complete structural bioinformatics workflow applied to hen egg-white lysozyme (HEWL), using real X-ray crystallography data from the RCSB Protein Data Bank.

#### What This Project Does

- Downloads and parses PDB structure **1HEL** using BioPython
- Performs **B-factor analysis** to map structural flexibility across all 129 residues
- Analyzes **amino acid composition** and physicochemical properties
- Calculates **catalytic site geometry** — distance between Glu35 and Asp52
- Generates an **active site neighbor map** (residues within 10 Å of Glu35)
- Produces **interactive 3D visualizations** of the protein, active site, and disulfide bonds

#### Key Results

| Analysis | Result |
|---|---|
| Mean B-factor | 13.65 Å² |
| Most flexible residue | GLY102 (42.83 Å²) |
| Most rigid residue | GLN41 (3.67 Å²) |
| Glu35 B-factor | 11.92 Å² |
| Asp52 B-factor | 5.88 Å² (very rigid — consistent with stabilizer role) |
| Glu35–Asp52 CA-CA distance | 9.34 Å |
| Glu35–Asp52 side chain distance | 7.18 Å |

#### Tools & Libraries

`Python` `BioPython` `py3Dmol` `matplotlib` `pandas` `numpy`

#### How to Run

1. Open `lysozyme_structural_analysis.ipynb` in Google Colab or Jupyter
2. Run cells sequentially from top to bottom
3. Cell 0 installs all dependencies automatically

---

## Türkçe

### Lizozim (1HEL) Yapısal Biyoinformatik Analizi

RCSB Protein Data Bank'tan alınan gerçek X-ray kristalografi verisi kullanılarak tavuk yumurta akı lizozimi (HEWL) üzerinde eksiksiz bir yapısal biyoinformatik iş akışı uygulanmıştır.

#### Proje Kapsamı

- BioPython ile **1HEL** PDB yapısını indirme ve ayrıştırma
- 129 rezidünün tamamında yapısal esnekliği haritalayan **B-factor analizi**
- **Amino asit kompozisyonu** ve fizikokimyasal özellik analizi
- **Katalitik site geometrisi** — Glu35 ve Asp52 arasındaki mesafe hesabı
- **Aktif site komşu haritası** (Glu35'e 10 Å içindeki rezidüler)
- Protein omurgası, aktif site ve disülfid bağlarının **interaktif 3D görselleştirmeleri**

#### Temel Sonuçlar

| Analiz | Sonuç |
|---|---|
| Ortalama B-factor | 13.65 Å² |
| En esnek rezidü | GLY102 (42.83 Å²) |
| En rijit rezidü | GLN41 (3.67 Å²) |
| Glu35 B-factor | 11.92 Å² |
| Asp52 B-factor | 5.88 Å² (çok rijit — stabilizör rolüyle uyumlu) |
| Glu35–Asp52 CA-CA mesafesi | 9.34 Å |
| Glu35–Asp52 yan zincir mesafesi | 7.18 Å |

#### Kullanılan Araçlar

`Python` `BioPython` `py3Dmol` `matplotlib` `pandas` `numpy`

#### Nasıl Çalıştırılır

1. `lysozyme_structural_analysis.ipynb` dosyasını Google Colab veya Jupyter'da açın
2. Hücreleri yukarıdan aşağıya sırayla çalıştırın
3. Cell 0 tüm bağımlılıkları otomatik olarak yükler

---

### Repository Structure

```
lysozyme-structural-analysis/
├── lysozyme-structural-analysis.ipynb     # Main analysis notebook
└── README.md               # This file
```
