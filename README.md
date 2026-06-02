# AIOP Analyzer - Vercel Proxy

API Proxy untuk AIOP Analyzer (Claude AI Vision untuk analisis chart saham IDX).

## Setup Quick Start

1. Download semua files di folder ini
2. Buat folder: aiop-vercel/
3. Structure:
   - aiop-vercel/
     - api/
       - proxy.js (rename dari aiop-vercel-proxy.js)
     - package.json
     - vercel.json
     - README.md

4. Upload ke GitHub:
   - Buat repo baru: github.com/akupraz/aiop-vercel
   - Upload semua files
   - Push ke GitHub

5. Deploy ke Vercel:
   - Buka: https://vercel.com
   - Click "Import Project"
   - Pilih GitHub repo: aiop-vercel
   - Click "Deploy"
   - Copy Vercel URL (format: https://aiop-vercel-xxx.vercel.app)

6. Paste URL di AIOP HTML app di field "Vercel Proxy URL"

## Files di folder ini:

- aiop-vercel-proxy.js → Rename jadi proxy.js & masuk folder api/
- package.json → Root folder
- vercel.json → Root folder
- aiop_cf_worker.html → Vercel version (update URL field)
- README.md → Ini file

## Support

GitHub: github.com/akupraz/aiop-vercel
