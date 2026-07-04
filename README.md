# Fusion 0.3 UI framework blueprint

An architecture guide for building fully code-authored Roblox UI on [Fusion](https://github.com/dphfox/Fusion) v0.3-beta.

**Read it here: https://filteredasync.github.io/fusion-framework-blueprint/**

Every load-bearing claim was either verified against primary sources (official docs, the Fusion repository, real open-source codebases) or measured directly in Roblox Studio across 16 lab test groups. Covers scopes and lifetimes, state and the lazy dependency graph, component and props conventions, stores and server-data bridging, list rendering with benchmarks, animation, screen routing, performance, the UI-Labs storybook workflow, and a 0.2 to 0.3 translation table.

## Template place

[`fusion-template.rbxlx`](fusion-template.rbxlx) is a runnable starter place: Fusion v0.3-beta plus a small working framework (theme tokens, components, a store, a router, two screens with a live buy flow, and a UI-Labs story). Open it in Roblox Studio and press Play. Fusion is MIT licensed by Elttob/dphfox.
