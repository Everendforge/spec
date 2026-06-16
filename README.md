# Everend Spec

Everend Spec defines the portable contracts shared by Everend Forge tools. It is the technical source of compatibility for vaults, branching graphs, runtime packages, and validation reports.

This repository starts with human-readable Markdown contracts and examples. Machine-readable JSON Schema and a CLI validator can be added after the first workflows are validated.

## Start Here

- [SPEC-V0.1.md](SPEC-V0.1.md): first human-readable contract.
- [docs/vault-format.md](docs/vault-format.md): Markdown vault expectations.
- [docs/runtime-package.md](docs/runtime-package.md): JSON/YAML runtime package expectations.
- [docs/validation-report.md](docs/validation-report.md): shared validation report concept.
- [examples/demo-vault](examples/demo-vault): synthetic Markdown vault example.
- [examples/runtime-package.json](examples/runtime-package.json): JSON runtime package example.
- [examples/runtime-package.yaml](examples/runtime-package.yaml): YAML runtime package example.

## Design Goals

- Keep canon portable and readable in Markdown tools.
- Keep runtime packages executable without authoring apps installed.
- Use stable IDs for cross-tool references.
- Let apps evolve independently while targeting explicit spec versions.

## License

Spec prose and examples are licensed under CC BY 4.0. Any code added later should use MIT OR Apache-2.0 unless stated otherwise.
