# Schemat.io

A unified platform for standardizing Minecraft schematic creation, sharing, and collaboration.

## About

Schemat.io provides infrastructure for Minecraft builders and server communities to manage, share, and discover building schematics. The platform supports multiple schematic formats and integrates directly with Minecraft servers, enabling seamless workflows for builders and server operators.

## Core Projects

### [Schematic Renderer](https://github.com/Schem-at/schematic-renderer)

High-performance 3D schematic visualization built with Three.js and Rust/WASM.

- Real-time rendering with WebGL and optional WebGPU compute
- Greedy meshing via Rust/WASM for efficient geometry
- Resource pack support with texture atlases
- Redstone simulation visualization powered by Nucleation
- Video/screenshot capture with FFmpeg.wasm
- Multiple camera modes: orbit, isometric, first-person

### [Nucleation](https://github.com/Schem-at/Nucleation)

Cross-platform schematic engine and redstone simulator written in Rust.

- Universal format support: `.litematic`, `.schem`, `.schematic`, `.nbt`
- ASCII art circuit builder for programmatic schematic creation
- Full redstone simulation via MCHPRS integration
- Typed circuit execution with high-level IO abstractions
- Multi-language bindings: Rust, JavaScript/WASM, Python, C FFI

### [SchematioConnector](https://github.com/Schem-at/SchematioConnector)

Bukkit/Paper plugin bridging Minecraft servers to the schemat.io platform.

- Upload schematics directly from WorldEdit clipboard
- Download and browse schematics in-game
- GUI-based schematic discovery with search and pagination
- JWT authentication for secure API access

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| Backend | Laravel 12, Livewire, Filament, Laravel Reverb |
| Frontend | Tailwind CSS, Three.js, Vite |
| Rendering | Rust/WASM, WebGL, WebGPU |
| Simulation | Rust, MCHPRS fork |
| Integration | Kotlin, Paper API, WorldEdit |

## Community

- [Discord](https://discord.com/invite/NcbbswJsrC) - Join the community
- [schemat.io](https://schemat.io) - Main platform

## Contributing

Contributions are welcome across all repositories. Check individual project READMEs for setup instructions and contribution guidelines.

## License

Projects use various open source licenses. See individual repositories for details.
