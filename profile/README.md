<p align="center">
  <a href="https://popnow.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/popnow-ai/.github/main/profile/assets/popnow-wordmark-light.png">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/popnow-ai/.github/main/profile/assets/popnow-wordmark.png">
      <img alt="PopNow" src="https://raw.githubusercontent.com/popnow-ai/.github/main/profile/assets/popnow-wordmark.png" width="240">
    </picture>
  </a>
</p>

<p align="center"><b>Make it pop.</b></p>

<p align="center">
  PopNow is a browser-based AI studio for videos, images and music: image-to-video, text-to-video, AI images, music and speech, and one-tap trending video effects, all on one credit balance.
</p>

<p align="center">
  <a href="https://popnow.ai">Website</a> &nbsp;·&nbsp;
  <a href="https://popnow.ai/docs">Docs</a> &nbsp;·&nbsp;
  <a href="https://popnow.ai/docs/openapi">API</a> &nbsp;·&nbsp;
  <a href="https://popnow.ai/mcp">MCP</a> &nbsp;·&nbsp;
  <a href="https://popnow.ai/pricing">Pricing</a>
</p>

### Build with PopNow

| Repository | What it is |
| --- | --- |
| [**popnow-mcp**](https://github.com/popnow-ai/popnow-mcp) | Remote MCP server: create AI images, videos, music and voiceovers from Claude, ChatGPT, Cursor and other MCP clients |
| [**popnow-skills**](https://github.com/popnow-ai/popnow-skills) | Agent skills that teach coding agents to generate media with PopNow |
| [**popnow-python**](https://github.com/popnow-ai/popnow-python) | Python SDK for AI video, image and music generation (`pip install popnow`) |
| [**popnow-js**](https://github.com/popnow-ai/popnow-js) | JavaScript and TypeScript SDK for AI video, image and music generation (`npm install popnow`) |
| [**popnow-go**](https://github.com/popnow-ai/popnow-go) | Go SDK with zero dependencies |
| [**popnow-php**](https://github.com/popnow-ai/popnow-php) | PHP 8.1+ SDK with zero dependencies |
| [**popnow-java**](https://github.com/popnow-ai/popnow-java) | Java 17+ SDK for Maven and Gradle |
| [**popnow-cli**](https://github.com/popnow-ai/popnow-cli) | Command-line client: generate from your terminal or CI, with prices shown first (`npm i -g @popnow/cli`) |
| [**popnow-comfyui**](https://github.com/popnow-ai/popnow-comfyui) | ComfyUI custom nodes for every PopNow model, no GPU needed |
| [**n8n-nodes-popnow**](https://github.com/popnow-ai/n8n-nodes-popnow) | n8n community node for AI video, image and music steps in workflows (`n8n-nodes-popnow` on npm) |
| [**popnow-proxy**](https://github.com/popnow-ai/popnow-proxy) | Server-side proxy: call PopNow from a browser app without exposing your API key |
| [**popnow-bot**](https://github.com/popnow-ai/popnow-bot) | Self-hosted Telegram and Discord bot for AI images, videos and video effects |
| [**popnow-api**](https://github.com/popnow-ai/popnow-api) | REST API reference, OpenAPI spec and copy-paste examples |
| [**popnow-blender**](https://github.com/popnow-ai/popnow-blender) | Blender add-on: turn a camera view into AI renders, video and textures |

### Use PopNow in your AI assistant

Add the remote MCP server once, then ask for a picture, video or song in plain words. Sign in with OAuth, or send an API key as a Bearer token.

```bash
claude mcp add --transport http popnow https://api.popnow.ai/mcp
```

```json
{
  "mcpServers": {
    "popnow": { "type": "http", "url": "https://api.popnow.ai/mcp" }
  }
}
```

Prices are quoted before anything runs, and failed runs are refunded.

### Models

Kling · Seedance · Wan · Vidu · MiniMax · Nano Banana · GPT Image · Flux · Suno · and more. Live list: [`GET /api/v1/models`](https://popnow.ai/docs/models).

<p align="center"><sub>Credit packs, no subscription. Get an API key at <a href="https://popnow.ai/api/console/keys">popnow.ai/api/console/keys</a>.</sub></p>
