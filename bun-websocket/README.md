# bun-server

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run server.ts
# Start another one in another terminal
bun run client.ts
```

To format:

```bash
bunx @biomejs/biome format --write server.ts client.ts
```

To lint:

```bash
bunx @biomejs/biome lint server.ts client.ts

```

This project was created using `bun init` in bun v1.0.11. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
