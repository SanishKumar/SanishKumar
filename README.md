# Sanish Kumar

Software engineer working on ML systems, computer vision, spatial software, and backend infrastructure.

I like projects where the difficult part can be tested: whether two reconstructions are byte-identical, whether a pull request changed the architecture, whether a route stays accessible during a lift outage, or what a debt simplification changes for the people involved.

I currently work as an AI Engineer Intern at NiftyBooks, and I am interested in software engineering and ML systems roles.

## Selected work

### [SpatialForge](https://github.com/SanishKumar/Spatial_Forge)

Known-pose RGB-D reconstruction for indoor mapping. The sparse TSDF path went from about 210 seconds to 2 seconds on the documented TUM run while staying byte-identical to the scalar reference. The repository has 453 tests across 39 modules and publishes the held-out evaluation separately from the reconstruction inputs.

### [System Synthesis](https://github.com/SanishKumar/System-Synthesis)

Architecture review for Docker Compose pull requests. It derives canonical base and head graphs, reports semantic changes with file-and-line evidence, applies policy from the trusted base branch, and delivers the same verdict through a CLI, GitHub Action, SARIF, and browser review. The browser checks reviewer identity and repository access when the deployment can verify them; an LLM may explain a finding but cannot decide it.

### [VoiceGIS Indoor Spatial Twin](https://github.com/SanishKumar/voicegis-indoor-ar)

An indoor-navigation platform built around compiled, content-addressed venue packages. The same package drives multi-floor A*, wheelchair and outage policies, search, 2D and 3D views, localization replay, and QR check-in. Two unrelated synthetic venues can be switched at runtime without rebuilding the client.

### [VoiceGIS](https://github.com/SanishKumar/VoiceGIS)

A zero-runtime-dependency control layer between natural-language input and GIS applications. It compiles requests into typed plans, checks permissions and adapter capabilities, validates again before execution, and returns per-operation receipts. It includes GeoJSON and OGC API Features adapters, a host-owned place resolver, an MCP server, and a separate 538-case artifact for the earlier parser.

### [CashFlow](https://github.com/SanishKumar/Cashflow)

A group-expense system that keeps the original obligation graph visible. Its browser engine can cancel closed loops without creating a new counterparty, or simplify open chains more aggressively while listing every new relationship that choice creates. The repository reports 129 passing tests and includes seeded benchmarks up to 13,935 obligation pairs.

## Professional work

At **NiftyBooks FlexCo**, I work on the path from story text to multi-page illustrations and on tools for finding and editing the same character across pages. My work uses diffusion workflows, ComfyUI, segmentation, OpenCV, FastAPI, and GPU-backed inference.

One masked editing path went from more than 90 seconds to approximately 5–6.5 seconds after profiling showed that a generative stage could be replaced with mask-constrained OpenCV processing.

## Technologies I use in the work above

- **Languages:** Python, TypeScript, JavaScript, C++, SQL
- **Backend:** Node.js, FastAPI, PostgreSQL, Redis, REST, WebSockets
- **ML and vision:** PyTorch, NumPy, OpenCV, diffusion models, segmentation, model inference
- **Spatial and systems:** RGB-D, TSDF, GIS, Web Workers, WebAssembly, Docker, GitHub Actions
- **Frontend:** React, Next.js, React Three Fiber, Canvas

## Links

[Portfolio](https://sanishkumar.vercel.app/) · [Résumé](https://sanishkumar.vercel.app/CV.pdf) · [LinkedIn](https://www.linkedin.com/in/sanish-kumar/) · [X](https://x.com/TheSanishK) · [npm](https://www.npmjs.com/~sanishkumar)
