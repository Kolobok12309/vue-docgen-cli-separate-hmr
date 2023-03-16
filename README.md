# vue-docgen-cli-separate-hmr
Reproduce repo for bug while vue-docgen-cli parsing model property

Steps to reproduce:

1. pnpm install
2. pnpm docgen:watch

If change something in `index.vue`, hmr update `.md`(normally)
If change something in `index.js`, hmr not update `.md`(but)
