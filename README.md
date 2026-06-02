# Didina SoulFood Riznica
🎨 Design Language & Visual System Tokens
This project features a custom "Warm Organic Modern" design identity crafted specifically to showcase real-life smartphone food photography without losing its appetizing warmth.
Canvas Base: #FDFBF7 (Soft Almond Cream) — High-readability canvas texture.
Primary Type: #23211F (Dark Chocolate Espresso) — Soft-contrast luxury typography.
Healthy Token: #607A66 (Sage Olive Green) — Reserved for ingredient grids and nutrition labels.
Upbeat Accent: #E5A93C (Mustard Gold) — Applied to layout grid lines, numbers, and meta tags.
Soul Details: #8C7AA6 (Lavender Purple) — Dedicated exclusively to Didi's personal voice, commentary boxes, and intimate quotes.
🏗️ Multi-Channel System Architecture
The codebase enforces a single-source configuration workflow where the master recipe text remains structured as standardized data attributes, feeding cleanly into separate distribution channels:
                       ┌──> [Web Channel] ───> WordPress Studio Local / Independent Cloud
                       │
[Master Data Backup] ──┼──> [E-Book Channel] ──> Universal EPUB3 Layout (Apple Books & Android)
                       │
                       └──> [Asset Processing] ─> Cloud Jupyter Notebook Pipeline Tool (Zero Local Load)
📁 System Directory Tree Structure Matrix
📁 didina-soulfood-riznica/
├── 📁 assets/
│   ├── 📁 css/
│   │   └── 📄 style.css          # Unified brand visual design stylesheet
│   └── 📁 images/             # Target deployment image output container (Optimized WebP/JPG)
├── 📁 raw_assets/
│   └── 📁 raw_images/         # Raw, heavy smartphone photos repository
│       ├── 📄 1.pdf              # Raw Master Manuscript Backup
│       └── 📄 2.zip              # Compressed Raw Assets Archive
├── 📁 web/
│   └── 📄 index.html             # Responsive web portfolio interface base file
├── 📄 .gitignore                 # Safety filtering configurations for binary assets
└── 📄 README.md                  # Core project documentation blueprint
📊 Data Modeling Schema Instance
Recipes are parsed from unformatted text paragraphs into strict relational properties:
Ingredient Attribute    Base Quantity   Unit Measurement    Target Section
Proteinska tortilja 1   komad   Sastojci
Feta sir    50  g   Sastojci
Grčki jogurt   1   kašika Sastojci
🏁 Phase-by-Phase Development Roadmap
 Phase 1: Initialize repository scaffold, connect remote tracking main branches, and deploy secure developer access tokens.
 Phase 2: Cloud-sync master text backups (1.pdf, 2.zip) via remote server virtualization.
 Phase 3: Establish local container framework inside isolated WordPress Studio environments matching the visual style palette.
 Phase 4: Build the clean component templates for semantic recipe data views.
 Phase 5: Ship the universal e-book packages and deploy cloud-hosted preview environments.
About
A headless content pipeline and multi-channel publishing engine converting raw culinary manuscripts into optimized web blogs and universal EPUB architectures using VS Code and Python
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Releases
No releases published
Create a new release
Deployments
7
 github-pages 1 hour ago
+ 6 deployments
Packages
No packages published
Publish your first package
Contributors
1
@natasha0824inkf
natasha0824inkf Natasha0824
Languages
HTML
91.7%
 
CSS
8.3%
Footer
Collapse









