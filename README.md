# mend

One patch tool for every AI edit format: a command-line tool that reads a patch in
one of four formats — unified diff, SEARCH/REPLACE blocks, V4A, JSON edits — finds
the lines each edit names at the first of three matching tiers, and changes every
file or none.

Built for make.fun's "Build mend, one patch tool for every AI edit format" bounty.

## Usage

    node main.ts [--format=NAME] [--check] [--strict] [PATCH]

See `SPEC.md` in the bounty kit for the full contract. `main.ts` is the CLI;
`runner.ts` is the kit's trial runner, kept as it is.
