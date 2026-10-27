# n8n studio

A free tool for testing and debugging [n8n](https://n8n.io) workflows. Load a workflow, give it an input, hit run, and see what every node did on one screen.

**[Try it](https://n8n-studio.vercel.app)** · Not affiliated with n8n.io

## What you get

- The workflow graph, each node's input, output and resolved parameters, all in one view
- Several n8n instances saved side by side (prod, dev, cloud, self-hosted)
- Messy payloads made readable, including HTML hidden inside JSON strings
- Replay any past execution's input against today's workflow

Your n8n URL and API key stay in your browser. There's no account and no database.

## Run it

```bash
npm install
npm run dev
```

Open `http://localhost:3000`, click the gear and paste your n8n URL and API key.

## License

[MIT](LICENSE)
