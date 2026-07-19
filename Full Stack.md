# Full Stack — Documentation Tree

Below is the documentation site repository tree (MkDocs-style) and project structure. Use this as a quick reference for the docs and content pages.

```
Enterprise-Portfolio
│
├── README.md
├── SUMMARY.md
├── mkdocs.yml
├── portfolio.md
├── Sandeep_Enterprise_Portfolio.md
├── "50 page sandeep career.docx"
├── Full Stack.md
│
├── docs
│   ├── 01-Executive-Summary.md
│   ├── 02-Career-Journey.md
│   ├── 03-Professional-Experience.md
│   ├── 04-Enterprise-Projects.md
│   ├── 05-Enterprise-Architecture.md
│   ├── 06-System-Design.md
│   ├── 07-Shopify-Plus.md
│   ├── 08-Adobe-Commerce.md
│   ├── 09-Headless-Commerce.md
│   ├── 10-AI-Engineering.md
│   ├── 11-Azure.md
│   ├── 12-AWS.md
│   ├── 13-React.md
│   ├── 14-NextJS.md
│   ├── 15-NodeJS.md
│   ├── 16-Python.md
│   ├── 17-PHP.md
│   ├── 18-Microservices.md
│   ├── 19-API.md
│   ├── 20-Performance.md
│   ├── 21-Security.md
│   ├── 22-Leadership.md
│   ├── 23-Interview-Guide.md
│   ├── 24-Technical-Blogs.md
│   ├── 25-Certifications.md
│   ├── 26-Resume.md
│   └── original
│       ├── README.md
│       └── 50-page-sandeep-career.docx.ref
│
├── diagrams
│   └── .gitkeep
├── assets
│   └── .gitkeep
├── samples
│   └── .gitkeep
└── presentations
    └── .gitkeep
```

Notes:
- The mkdocs skeleton and docs/ pages were added on branch `mkdocs-site`.
- The original Word document is stored in the repository (binary). See: `50 page sandeep career.docx` on the main branch.
- If you want the DOCX converted with higher fidelity (including images and tables), please upload the .docx or provide a plain-text export and I will re-run the conversion and update the docs files.

Files to review next:
- docs/01-Executive-Summary.md — contains the seeded executive summary.
- docs/02-.. to docs/26-.. — converted pages (best-effort) and placeholders for manual cleanup.

To publish locally:
- Install MkDocs and run `mkdocs serve` from the repository root (after installing mkdocs-material if you use that theme) to preview the site.
