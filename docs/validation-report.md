# Validation Report

A validation report is the shared shape of compatibility feedback across Everend tools.

Initial report categories:

- missing_frontmatter
- duplicate_id
- broken_wikilink
- missing_canon_ref
- broken_graph_transition
- missing_runtime_asset

Formal JSON shape and error codes are future work. For v0.1, tools should report file or node location, severity, message, and suggested fix when possible.
