# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

```mermaid
gantt
    title Peta Jalan Hilirisasi Companion
    dateFormat YYYY-MM
    axisFormat %b '%y

    section Sebelum Program
        Riset & desain arsitektur             :done, r1, 2025-07, 2025-10
        Pengembangan Vexa (Voice)             :done, r2, 2025-10, 2026-01
        Vexa v0.9 - Zoom, bot interaktif, MCP :done, r3, 2026-01, 2026-03
        CompanionCore POC + auth              :done, r4, 2026-03, 2026-03
        Multi-mode, multi-provider, Skills    :done, r5, 2026-03, 2026-04
        Web & CLI setup                       :done, r6, 2026-03, 2026-04
        Hardening & persiapan mitra           :active, r7, 2026-04, 2026-05

    section Program PPI 2026 (Mei-Nov)
        Q1 - Co-design & onboarding           :q1, 2026-05, 2026-07
        Q2 - Integrasi & pilot                :q2, 2026-07, 2026-10
        Q3 - Validasi & hilirisasi            :q3, 2026-10, 2026-12
        Peluncuran komersial                  :milestone, launch, 2026-09, 0d
```
