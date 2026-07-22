# Guilherme M. Rocha

I build local-first Windows software and developer tools for environments where reliability matters more than permanent connectivity.

Based in Brazil, I work across product delivery, offline-capable desktop systems, and focused engineering tools. I prefer explicit contracts and verifiable behavior over broad claims: what works offline, what fails safely, what automation has proved, and what still needs human validation should all be visible.

## Selected work

| Project | Purpose | Public evidence |
| --- | --- | --- |
| **ClubAL** | Offline-first Windows software for institutional displays and operational routines. The implementation remains private during active development. | [Product site](https://clubal.pages.dev/) · [Delivery and reliability Projects](https://github.com/users/gmdr2022/projects) |
| **Release Evidence** | Dependency-free CLI for deterministic SHA-256 release manifests, strict verification, and portable path handling. | [Source](https://github.com/gmdr2022/release-evidence) · [v1.0.0](https://github.com/gmdr2022/release-evidence/releases/tag/v1.0.0) · [Attested release workflow](https://github.com/gmdr2022/release-evidence/actions/workflows/release.yml) |
| **Local-first Checklist** | Offline checklist CLI with atomic persistence, schema validation, last-known-good backup, and explicit recovery. | [Source](https://github.com/gmdr2022/local-first-checklist) · [v1.0.0](https://github.com/gmdr2022/local-first-checklist/releases/tag/v1.0.0) · [Data contract](https://github.com/gmdr2022/local-first-checklist/blob/main/docs/data-format.md) |

## Engineering principles

- **Local operation is the baseline.** Network services may extend a workflow, but should not become an accidental startup dependency.
- **Failure must be legible.** Validation, recovery, and fallback behavior are explicit rather than silently masking damaged state.
- **Evidence travels with a release.** Tests, cross-platform CI, deterministic manifests, and provenance are connected to the artifact they support.
- **Public and private boundaries are intentional.** Product outcomes can be explained without publishing source code, operational data, credentials, or undisclosed plans.
- **Human gates remain human.** Automated checks are reported separately from visual, physical-device, or operational acceptance.

## Current focus

I am refining local-first product delivery on Windows and publishing small tools whose guarantees can be inspected, tested, and reused independently.

## Links

- [ClubAL product site](https://clubal.pages.dev/)
- [Public engineering Projects](https://github.com/users/gmdr2022/projects)
- [GitHub profile](https://github.com/gmdr2022)
