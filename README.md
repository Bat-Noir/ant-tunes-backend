# Ant Tunes Backend 🎧

Backend service for Ant Tunes — a fast music streaming and downloading app.

## Features
- Search songs
- Get song details
- Stream/download songs
- Song suggestions

## Tech Stack
- Bun / Node.js
- TypeScript
- JioSaavn API (unofficial)

## Status
🚧 In development

## 🔌 Running Locally

1. Clone the repository:

```sh
git clone https://github.com/Bat-Noir/ant-tunes-backend
cd ant-tunes-backend
```

### Using Docker

```sh
docker-compose up
```

OR

### Manually

> [!NOTE]
> You need `Bun(1.0.29+)` or `Node.js(v20+)`

2. Install the required dependencies:

   ```sh
   bun install
   ```

3. Launch the development server:

   ```sh
   bun run dev
   ```

## ☁️ Deploying Your Own Instance

JioSaavn API can be deployed to either Cloudflare Workers or Vercel. Below are the instructions for deploying to each platform.

### Cloudflare Workers

[![Deploy with Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/sumitkolhe/jiosaavn-api)

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/sumitkolhe/jiosaavn-api)

## 📜 License

This project is distributed under the [MIT License](https://opensource.org/licenses/MIT). For more information, see the [LICENSE](LICENSE) file included in this repository.
