# Collaborative Plugin Development

---

## Concept:
- To have a built in version control plugin for music artists inside the DAW, built on the same logic as git (primarily for FL Studio possible generalization implement in the future)

## Steps:
0. Testing the limitations of git:
Possible to commit simple file changes, however unable to merge due to binary files
1. Creating a VST3 plugin shell using Rust and CLAP API:
My choice of code language is rust since C++ was the only other option
