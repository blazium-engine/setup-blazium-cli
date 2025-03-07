# Setup Blazium CLI

Setup Blazium CLI to use when getting the engine, templates or tools.

Usage:

```yml
- uses: blazium-engine/setup-blazium-cli@master
name: 🤖 Setup Blazium CLI
with:
    version: 0.0.14

- name: 🔬 Verify CLI
run: |
    blazium-cli --version
```
