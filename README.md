# Fuwari — blog template

A bright, expressive blog for sharing what you are learning.

![Preview of the Fuwari template](.github/preview.webp)

[Author's demo](https://fuwari.vercel.app) · [All templates](https://leafcloud.in/templates/)

## Make it yours in one step

Paste this prompt into your coding agent:

```text
Set up the LeafCloud "Fuwari" template for me: fetch https://leafcloud.in/templates/fuwari.md and follow it step by step.
```

Works with Claude Code, Codex, Cursor, or any coding agent. It asks a few questions, fills in your details, and puts the site online at `<your-name>.leafcloud.app`.

## Or do it yourself

Choose **Use this template** on [GitHub](https://github.com/leafcloud-in/template-fuwari), or clone it:

```sh
git clone https://github.com/leafcloud-in/template-fuwari.git
cd template-fuwari
pnpm install --frozen-lockfile
pnpm run dev
```

The dev server prints a local address in your terminal. Open that address in a browser and leave the server running while you edit.

Edit src/config.ts and src/content/posts/. Keep the existing design and replace the fictional sample details with your own.

Before publishing, make a production build:

```sh
pnpm run build
```

When you are ready to publish, get LeafCloud access at [leafcloud.in](https://leafcloud.in) (join the waitlist or sign in), then install the CLI:

```sh
curl -fsSL https://leafcloud.in/install.sh | sh
leaf init --name <your-site> --yes
leaf deploy --yes
```

LeafCloud will publish the site at `https://<your-site>.leafcloud.app`.

The local preview is available at http://localhost:4321 for Astro templates or http://localhost:3000 for CV.

## Changing it later

Ask your agent: “add my new project and redeploy”. AGENTS.md tells it which files to update and how to build and publish again.

## Credits

Built on [saicaca/fuwari](https://github.com/saicaca/fuwari) by saicaca, under the MIT licence. The LICENSE file is unchanged. LeafCloud changes are listed in [LEAFCLOUD.md](LEAFCLOUD.md). The original project README is in [docs/UPSTREAM-README.md](docs/UPSTREAM-README.md).
