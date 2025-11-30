# vkpostsender

This is a bot for your VK group that sends out new posts to subscribers.
It works through the VK "Рассылки" widget and uses its API when sending messages. Read more here: https://vk.com/@hs-instrukciya-po-servisu-rassylki

This project was created using `bun init` in bun v1.1.42. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run src/index.ts
```

To build:

```bash
bun run build && node build/index.js
```

After build, find the `.env.example`, rename it to `.env`, and fill out your mailing lists using the sample. It can be used for multiple groups at the same time, to do this, you just need to specify in the sequence from `_1` to `_n`, depending on the number of groups. 

After editing `.env` build a project again.
