# LIBSYS VTU - 7th Sem Simulation (GitHub Pages)

**Live Demo**: Will be at `https://YOURUSERNAME.github.io/libsys-vtu-lab/` after deploy

100% static - No backend, No database, No data collection.
All 5 labs are simulated in browser:
- L1 Schema (3NF)
- L2 Backend (CRUD, SELECT FOR UPDATE, OpenAPI)
- L3 Frontend (React from schema)
- L4 SRE (Docker, /health)
- L5 AI Agent (search_books tool, RAG, Guardrail, Evaluation Set, Failure Museum)

## How this repo was deployed
Just push `index.html` to main branch. GitHub Action auto-deploys to Pages.
No build step.

## For Students
Open the live link. Try queries:
- "ML books for beginners" -> Should find Python ML
- "Quantum Cooking" -> Must say "No books found" (hallucination test)
