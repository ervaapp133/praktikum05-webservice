# praktikum05-webservice

Implementasi Web Service REST API Katalog Buku Perpustakaan menggunakan Express 5 dan Node.js dengan dokumentasi OpenAPI / Swagger UI (Praktikum 05 Web Service Engineering).

**Nama:** Erva Aisyana  
**NIM:** 240104040151  
**Lingkungan:** Node.js 24.x, npm, Express 5.3.0  

## Instalasi
Instalasi dari proyek yang sudah mempunyai lockfile:
```bash
npm install
npm run docs
```

## Menjalankan Server
Terminal pertama:
```bash
npm start
```

## Menjalankan Client
Terminal kedua:
```bash
node client.cjs GET /api/buku/1
```

## Endpoint URL
- **API:** http://127.0.0.1:3200/api/buku
- **Dokumen OpenAPI:** http://127.0.0.1:3200/openapi.json
- **Swagger UI:** http://127.0.0.1:3200/docs/

## Catatan / Batasan
- Tanpa login, data array dalam memori.
- Data tambahan hilang setelah server dimulai ulang.
- Hentikan server dengan `Ctrl+C` pada terminal pertama.
