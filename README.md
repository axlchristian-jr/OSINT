# OSINT
Open Source Intelligence (OSINT) resources, tools, and notes for information gathering and analysis.
https://osintframework.com/
# 👾 Axl Christian Jr

> "Curiosity builds skill — consistency sharpens the blade."

🔍 Learner: OSINT | Ethical Hacking | Python  
📍 Current mission: Termux + OSINT tooling  
🧱 Alias: **noob-ply.kit** — where experiments turn into tools  
🔥 Goal: from zero-to-somebody — step by step, commit by commit

---

[ ] Minggu 1 — Basic & Setup
    - Kenal OSINT, mindset, legal boundary
    - Install tools dasar: termux / linux / windows
    - Pahami footprint: username, email, domain, phone

[ ] Minggu 2 — Username & Email Investigation
    - Sherlock & Maigret: username hunting
    - holehe & howmanyofme: email lookup
    - Writeup 1: dokumentasi investigasi username target dummy

[ ] Minggu 3 — Domain & Network Recon
    - theHarvester, whois lookup, dnsrecon
    - Subdomain enumeration basic
    - Writeup 2: mapping domain organisasi dummy

[ ] Minggu 4 — Metadata & File OSINT
    - exiftool, exifscan, metadata2go
    - Reverse Image Search & geolocation dasar
    - Writeup 3: analisa gambar + lokasi

[ ] Minggu 5 — Automation Basic
    - Python basic scraping
    - Buat modul automation kecil di folder `modules/`
    - Simpan hasil di folder `data/`

[ ] Minggu 6 — Final Mini Project
    - Pilih target simulasi legal (ex: profile online palsu)
    - Lakuin full cycle investigasi
    - Buat laporan markdown di repo
    ---
    osint-framework/
├── README.md               # Dokumentasi utama
├── data/                   # Hasil investigasi & dump data
│   ├── usernames.txt
│   └── leaked_emails.txt
├── modules/                # Script OSINT modular
│   ├── username_lookup.py
│   ├── email_checker.py
│   └── phone_osint.py
├── tools.md                # List tools OSINT
├── method.md               # Metode + workflow investigasi
└── references.md           # Resource & referensi OSINT
---
1. Tentukan target (username / email / domain / phone)
2. Kumpulkan footprint awal (passive recon)
3. Jalankan tools sesuai kebutuhan
4. Dokumentasikan progres + temuan di repo
5. Simpan data mentah di `/data`
6. Kembangkan modul otomatisasi di `/modules`
---
- theHarvester : domain, email, subnet
- holehe : email dipakai dimana aja
- sherlock : hunting username multi-platform
- phoneinfoga : OSINT nomor telepon
- exiftool : metadata foto & file
- dnsrecon : recon domain
---
# Placeholder modul OSINT username lookup
# Next: tambahin API check & scraping

def check_user(username):
    return f"Investigasi username: {username} (placeholder)"

if __name__ == "__main__":
    target = input("Masukkan username: ")
    print(check_user(target))
  ---
  - osintframework.com
- haveibeenpwned.com
- intelx.io
- meta.osint.ninja
