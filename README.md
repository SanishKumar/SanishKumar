# Sanish Kumar

Software engineer working on spatial systems, backend infrastructure, ML/CV, and developer tooling.

I like building systems where correctness, reliability, and measurable behavior matter more than just getting a demo to work.

## Projects

### [SpatialForge](https://github.com/SanishKumar/Spatial_Forge)
Deterministic 3D reconstruction from calibrated RGB-D scans.

- TSDF reconstruction from depth frames + known camera poses
- validated on real TUM RGB-D data
- sparse fusion optimized from ~210s to ~2s
- optimized path remains byte-identical to the reference implementation
- 434 automated tests

### [VoiceGIS Indoor Spatial Twin](https://github.com/SanishKumar/voicegis-indoor-ar)
Indoor mapping and navigation system with versioned spatial data.

- multi-floor and wheelchair-aware routing
- 2D + 3D spatial views
- route receipts and versioned closures
- localization replay and uncertainty handling
- offline package verification

### [VoiceGIS](https://github.com/SanishKumar/VoiceGIS)
Controlled natural-language execution for GIS applications.

`text/speech → typed plan → policy → confirmation → execution`

Includes permission checks, capability validation, execution receipts, and a reproducible 538-case parser benchmark.

### [System Synthesis](https://github.com/SanishKumar/System-Synthesis)
Architecture change intelligence for pull requests.

Turns infrastructure revisions into canonical graphs, computes semantic changes, runs deterministic policy, and publishes findings through GitHub Actions, SARIF, CLI output, and a review UI.

### [CashFlow](https://github.com/SanishKumar/Cashflow)
Group expense system with a C++/WebAssembly debt-settlement solver, PostgreSQL persistence, RBAC, audit history, and real-time updates.

## Experience

At **NiftyBooks**, I worked on GPU-backed image generation and computer-vision pipelines using ComfyUI, FastAPI, OpenCV, segmentation, inpainting, and model inference.

One workflow went from **90s+ to ~5–6.5s** after profiling it and replacing an unnecessary generative step with deterministic computer vision.

## Tech

**Languages:** Python, TypeScript, JavaScript, C++, SQL  
**Backend:** Node.js, FastAPI, PostgreSQL, Redis, WebSockets, REST  
**Frontend:** React, Next.js, React Three Fiber, Tailwind  
**ML/CV:** PyTorch, TensorFlow, Hugging Face, OpenCV, NumPy  
**Other:** Docker, Linux, GitHub Actions, WebAssembly, Yjs, graph algorithms

## Links

[Portfolio](https://sanishkumar.vercel.app/) ·
[LinkedIn](https://www.linkedin.com/in/sanish-kumar/) ·
[X](https://x.com/TheSanishK) ·
