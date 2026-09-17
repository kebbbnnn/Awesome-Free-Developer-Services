# 🚀 Awesome Free Developer Services

> A curated list of developer-friendly services with **generous free tiers** for solo developers, indie hackers, students, hobby projects, prototypes, and small SaaS applications.

The goal of this list is to help you build and run real projects with **$0 infrastructure cost for as long as possible**.

> ⚠️ **Free doesn't always mean unlimited.** Always check the provider's current pricing and fair-use policies before relying on a service for production workloads.

## Contents

* [Databases](#-databases)
* [Backend & App Hosting](#-backend--app-hosting)
* [Serverless & Edge](#-serverless--edge)
* [Object & File Storage](#-object--file-storage)
* [CDN & DNS](#-cdn--dns)
* [Monitoring & Uptime](#-monitoring--uptime)
* [Error Tracking](#-error-tracking)
* [Email](#-email)
* [Authentication](#-authentication)
* [Caching & Redis](#-caching--redis)
* [Search](#-search)
* [Analytics](#-analytics)
* [Queues & Messaging](#-queues--messaging)
* [Cron Jobs & Scheduling](#-cron-jobs--scheduling)
* [CI/CD](#-cicd)
* [Containers & Registries](#-containers--registries)
* [AI / LLM APIs](#-ai--llm-apis)
* [Image & Media Processing](#-image--media-processing)
* [Maps & Geolocation](#-maps--geolocation)
* [Authentication / Identity](#-authentication--identity)
* [Feature Flags](#-feature-flags)
* [API Gateways & Reverse Proxies](#-api-gateways--reverse-proxies)
* [Developer Utilities](#-developer-utilities)
* [Free VPS / Compute](#-free-vps--compute)
* [Mobile Development](#-mobile-development)
* [Useful Free APIs](#-useful-free-apis)
* [No-Credit-Card Services](#-no-credit-card-services)

---

# 🗄️ Databases

| Service                                        | Type          | Free Tier                                                | CC Required |
| ---------------------------------------------- | ------------- | -------------------------------------------------------- | ----------- |
| [Neon](https://neon.com)                       | PostgreSQL    | 100 projects, 100 CU-hours/project/month, 0.5 GB/project | ❌           |
| [Turso](https://turso.tech)                    | SQLite/LibSQL | Generous database/storage/read quotas                    | ❌           |
| [Supabase](https://supabase.com)               | PostgreSQL    | 500 MB DB, 1 GB storage, 50K MAU                         | ❌           |
| [Firebase](https://firebase.google.com)        | NoSQL         | Spark plan with free quotas                              | ❌           |
| [MongoDB Atlas](https://www.mongodb.com/atlas) | MongoDB       | Free shared cluster                                      | ❌*          |
| [CockroachDB](https://www.cockroachlabs.com)   | SQL           | Free serverless tier                                     | ❌*          |
| [Convex](https://www.convex.dev)               | Reactive DB   | Free developer tier                                      | ❌           |
| [Appwrite](https://appwrite.io)                | SQL/Backend   | Free cloud tier                                          | ❌           |
| [PlanetScale](https://planetscale.com)         | MySQL         | Free developer options may vary                          | ⚠️          |
| [Turso](https://turso.tech)                    | Edge SQLite   | Free developer tier                                      | ❌           |
| [Upstash](https://upstash.com)                 | Redis         | Free Redis tier                                          | ❌           |
| [Tinybird](https://www.tinybird.co)            | ClickHouse    | Free tier                                                | ❌           |
| [Nhost](https://nhost.io)                      | PostgreSQL    | Free backend tier                                        | ❌           |
| [PocketBase](https://pocketbase.io)            | SQLite        | Self-hosted                                              | —           |

### ⭐ Particularly useful

**Neon** is excellent when you simply need PostgreSQL without maintaining a server. Its current Free plan includes 100 projects, 100 CU-hours per project/month and 0.5 GB storage per project.

**Supabase** combines PostgreSQL, authentication, storage and APIs. Its current Free plan includes a 500 MB database, 1 GB file storage and 50,000 MAU, although inactive free projects can be paused.

---

# ☁️ Backend & App Hosting

| Service                                                          | Free Tier                                  | Best For               |
| ---------------------------------------------------------------- | ------------------------------------------ | ---------------------- |
| [Render](https://render.com)                                     | Free services                              | APIs, Node, Python     |
| [Vercel](https://vercel.com)                                     | Hobby                                      | Next.js, React, APIs   |
| [Netlify](https://www.netlify.com)                               | Free                                       | Frontend + functions   |
| [Deno Deploy](https://deno.com/deploy)                           | Free                                       | TypeScript/JavaScript  |
| [Cloudflare Pages](https://pages.cloudflare.com)                 | Free                                       | Static/JAMstack        |
| [Firebase Hosting](https://firebase.google.com/products/hosting) | Free                                       | Web apps               |
| [GitHub Pages](https://pages.github.com)                         | Free                                       | Static websites        |
| [GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)   | Free                                       | Static websites        |
| [Surge](https://surge.sh)                                        | Free                                       | Simple static hosting  |
| [Koyeb](https://www.koyeb.com)                                   | Free instance                              | Containers/APIs        |
| [Zeabur](https://zeabur.com)                                     | Free plan                                  | Containers/apps        |
| [Railway](https://railway.com)                                   | $1/month free credit                       | APIs/workers/databases |
| [Fly.io](https://fly.io)                                         | Limited free allowances / credits may vary | Containers             |
| [PythonAnywhere](https://www.pythonanywhere.com)                 | Free plan                                  | Python                 |
| [Replit](https://replit.com)                                     | Free plan                                  | Prototyping            |
| [Glitch](https://glitch.com)                                     | Free options                               | Small web projects     |

Vercel's current Hobby plan is $0 and includes items such as automatic CI/CD, CDN, DDoS mitigation and serverless/edge functionality.

Netlify currently offers a $0 Free plan with 300 monthly credits and includes deployment, previews, functions, database/blob functionality and CDN delivery.

Railway is worth including, but with an important caveat: its current free plan provides **$1/month of free usage after the initial $5/30-day trial**, rather than unlimited free hosting.

---

# ⚡ Serverless & Edge

| Service                                                                          | Free Tier              | Runtime     |
| -------------------------------------------------------------------------------- | ---------------------- | ----------- |
| [Cloudflare Workers](https://workers.cloudflare.com)                             | Generous free requests | JS/TS/WASM  |
| [Deno Deploy](https://deno.com/deploy)                                           | 1M requests/month      | JS/TS       |
| [Vercel Functions](https://vercel.com/docs/functions)                            | Free Hobby quota       | JS/TS       |
| [Netlify Functions](https://www.netlify.com/products/functions/)                 | Included in Free       | JS/TS       |
| [Firebase Functions](https://firebase.google.com/docs/functions)                 | Limited no-cost usage  | Node/Python |
| [AWS Lambda](https://aws.amazon.com/lambda/)                                     | Free tier              | Multiple    |
| [Google Cloud Run](https://cloud.google.com/run)                                 | Free quota             | Containers  |
| [Azure Functions](https://azure.microsoft.com/products/functions)                | Free quota             | Multiple    |
| [Koyeb](https://www.koyeb.com)                                                   | Free instance          | Containers  |
| [Modal](https://modal.com)                                                       | Free credits           | Python/GPU  |
| [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) | Free allowance         | JS/TS       |

Deno Deploy currently lists **1 million requests/month**, 20 GiB monthly egress and 500,000 KV write units/month on its Free plan.

---

# 📦 Object & File Storage

| Service                                                                                 | Type              | Free Tier                 |
| --------------------------------------------------------------------------------------- | ----------------- | ------------------------- |
| [Cloudflare R2](https://developers.cloudflare.com/r2/)                                  | Object storage    | Free monthly allowance    |
| [Supabase Storage](https://supabase.com/storage)                                        | Object storage    | 1 GB                      |
| [Firebase Storage](https://firebase.google.com/products/storage)                        | Object storage    | Free quotas               |
| [Backblaze B2](https://www.backblaze.com/cloud-storage)                                 | Object storage    | Free allowance            |
| [Cloudinary](https://cloudinary.com)                                                    | Media storage     | Free tier                 |
| [ImageKit](https://imagekit.io)                                                         | Media CDN/storage | Free tier                 |
| [UploadThing](https://uploadthing.com)                                                  | File uploads      | Free tier                 |
| [Bunny Storage](https://bunny.net/storage/)                                             | Object storage    | Low-cost rather than free |
| [GitHub Releases](https://docs.github.com/en/repositories/releasing-projects-on-github) | File distribution | Free                      |
| [GitHub LFS](https://git-lfs.com)                                                       | Large files       | Limited free quota        |

---

# 🌐 CDN & DNS

| Service                                                                                             | Free Offering                       |
| --------------------------------------------------------------------------------------------------- | ----------------------------------- |
| [Cloudflare](https://www.cloudflare.com)                                                            | DNS, CDN, SSL, DDoS protection, WAF |
| [Cloudflare Pages](https://pages.cloudflare.com)                                                    | Static hosting + CDN                |
| [Cloudflare Workers](https://workers.cloudflare.com)                                                | Edge compute                        |
| [Cloudflare R2](https://developers.cloudflare.com/r2/)                                              | Object storage                      |
| [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) | Secure tunnels                      |
| [Bunny CDN](https://bunny.net)                                                                      | Limited/low-cost CDN                |
| [jsDelivr](https://www.jsdelivr.com)                                                                | Free public CDN                     |
| [unpkg](https://unpkg.com)                                                                          | npm CDN                             |
| [cdnjs](https://cdnjs.com)                                                                          | Public CDN                          |

Cloudflare's free ecosystem is particularly useful because DNS/CDN/DDoS protection, Pages, Workers, R2 and Tunnel can be combined into a small application stack.

---

# 📈 Monitoring & Uptime

| Service                                                     | Free Tier                           |
| ----------------------------------------------------------- | ----------------------------------- |
| [UptimeRobot](https://uptimerobot.com)                      | 50 monitors, 5-minute interval      |
| [Better Stack](https://betterstack.com)                     | Free monitoring tier                |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma)      | Self-hosted                         |
| [HetrixTools](https://hetrixtools.com)                      | Free monitoring                     |
| [Pingdom](https://www.pingdom.com)                          | Limited trial/free options may vary |
| [Cronitor](https://cronitor.io)                             | Free cron monitoring                |
| [Healthchecks.io](https://healthchecks.io)                  | Free cron monitoring                |
| [Oh Dear](https://ohdear.app)                               | Free/limited options                |
| [Freshping](https://www.freshworks.com/website-monitoring/) | Free monitoring                     |

UptimeRobot currently offers **50 monitors**, HTTP/port/ping/keyword/API/UDP/DNS/SSL monitoring and a 5-minute interval on its $0 plan, with no credit card required.

---

# 🐛 Error Tracking

| Service                                                                  | Free Tier               |
| ------------------------------------------------------------------------ | ----------------------- |
| [Sentry](https://sentry.io)                                              | Free error monitoring   |
| [GlitchTip](https://glitchtip.com)                                       | Open-source/self-hosted |
| [Rollbar](https://rollbar.com)                                           | Free tier               |
| [Bugsnag](https://www.bugsnag.com)                                       | Free tier               |
| [LogRocket](https://logrocket.com)                                       | Free tier               |
| [Highlight.io](https://highlight.io)                                     | Free tier + open source |
| [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) | Free                    |

---

# ✉️ Email

| Service                                   | Free Tier                                       |
| ----------------------------------------- | ----------------------------------------------- |
| [Resend](https://resend.com)              | 3,000 emails/month                              |
| [Brevo](https://www.brevo.com)            | Free daily email allowance                      |
| [Mailjet](https://www.mailjet.com)        | Free tier                                       |
| [MailerSend](https://www.mailersend.com)  | Free tier                                       |
| [Loops](https://loops.so)                 | Free tier                                       |
| [Amazon SES](https://aws.amazon.com/ses/) | Limited free allowance under certain conditions |
| [SendGrid](https://sendgrid.com)          | Free/trial options vary                         |
| [Mailgun](https://www.mailgun.com)        | Trial/free options vary                         |

Resend currently offers **3,000 emails/month**, with a 100-email/day limit on its Free plan.

---

# 🔐 Authentication

| Service                                                              | Free Tier               |
| -------------------------------------------------------------------- | ----------------------- |
| [Supabase Auth](https://supabase.com/auth)                           | 50K MAU                 |
| [Firebase Authentication](https://firebase.google.com/products/auth) | Free authentication     |
| [Clerk](https://clerk.com)                                           | Free developer tier     |
| [Auth0](https://auth0.com)                                           | Free tier               |
| [Kinde](https://kinde.com)                                           | Free tier               |
| [WorkOS](https://workos.com)                                         | Free developer features |
| [Logto](https://logto.io)                                            | Free tier + open source |
| [PocketBase](https://pocketbase.io)                                  | Self-hosted             |
| [Appwrite](https://appwrite.io)                                      | Free tier               |

---

# 🧠 Caching & Redis

| Service                                                | Free Tier               |
| ------------------------------------------------------ | ----------------------- |
| [Upstash](https://upstash.com)                         | Free Redis              |
| [Redis Cloud](https://redis.io/cloud/)                 | Free tier               |
| [Valkey](https://valkey.io)                            | Open source/self-hosted |
| [Dragonfly](https://www.dragonflydb.io)                | Open source             |
| [Momento](https://www.gomomento.com)                   | Free tier               |
| [Cloudflare KV](https://developers.cloudflare.com/kv/) | Free allowance          |
| [Deno KV](https://deno.com/kv)                         | Free allowance          |

---

# 🔎 Search

| Service                                                | Free Tier           |
| ------------------------------------------------------ | ------------------- |
| [Typesense Cloud](https://cloud.typesense.org)         | Free tier           |
| [Meilisearch Cloud](https://www.meilisearch.com/cloud) | Free tier           |
| [Algolia](https://www.algolia.com)                     | Free tier           |
| [OpenSearch](https://opensearch.org)                   | Open source         |
| [Typesense](https://typesense.org)                     | Open source         |
| [Meilisearch](https://www.meilisearch.com)             | Open source         |
| [Tantivy](https://github.com/quickwit-oss/tantivy)     | Open source library |

---

# 📊 Analytics

| Service                                                               | Free Tier               |
| --------------------------------------------------------------------- | ----------------------- |
| [PostHog](https://posthog.com)                                        | Generous free usage     |
| [Plausible](https://plausible.io)                                     | Limited trial           |
| [Umami](https://umami.is)                                             | Open source/self-hosted |
| [GoatCounter](https://www.goatcounter.com)                            | Free                    |
| [Google Analytics](https://analytics.google.com)                      | Free                    |
| [Microsoft Clarity](https://clarity.microsoft.com)                    | Free                    |
| [Cloudflare Web Analytics](https://www.cloudflare.com/web-analytics/) | Free                    |
| [Vercel Web Analytics](https://vercel.com/docs/analytics)             | Free allowance          |

---

# 📨 Queues & Messaging

| Service                                                        | Free Tier              |
| -------------------------------------------------------------- | ---------------------- |
| [Upstash QStash](https://upstash.com/qstash)                   | Free allowance         |
| [Cloudflare Queues](https://developers.cloudflare.com/queues/) | Free allowance         |
| [Inngest](https://www.inngest.com)                             | Free tier              |
| [Trigger.dev](https://trigger.dev)                             | Free tier              |
| [RabbitMQ](https://www.rabbitmq.com)                           | Open source            |
| [NATS](https://nats.io)                                        | Open source            |
| [Redpanda](https://redpanda.com)                               | Free developer options |
| [Kafka](https://kafka.apache.org)                              | Open source            |

---

# ⏰ Cron Jobs & Scheduling

| Service                                                                                                    | Free Tier             |
| ---------------------------------------------------------------------------------------------------------- | --------------------- |
| [GitHub Actions](https://github.com/features/actions)                                                      | Free for public repos |
| [GitHub Actions Scheduled Workflows](https://docs.github.com/en/actions)                                   | Cron scheduling       |
| [Cron-job.org](https://cron-job.org)                                                                       | Free                  |
| [EasyCron](https://www.easycron.com)                                                                       | Free tier             |
| [GitHub Actions](https://github.com/features/actions)                                                      | Scheduled jobs        |
| [Cloudflare Workers Cron Triggers](https://developers.cloudflare.com/workers/configuration/cron-triggers/) | Free allowance        |
| [Deno Cron](https://deno.com/deploy)                                                                       | Included with Deno    |
| [Vercel Cron](https://vercel.com/docs/cron-jobs)                                                           | Free/Hobby allowance  |
| [Netlify Scheduled Functions](https://docs.netlify.com/functions/scheduled-functions/)                     | Free allowance        |
| [Inngest](https://www.inngest.com)                                                                         | Free tier             |
| [Trigger.dev](https://trigger.dev)                                                                         | Free tier             |

---

# 🔄 CI/CD

| Service                                               | Free Tier                                 |
| ----------------------------------------------------- | ----------------------------------------- |
| [GitHub Actions](https://github.com/features/actions) | Free for public repos + monthly allowance |
| [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)        | Free CI/CD minutes                        |
| [CircleCI](https://circleci.com)                      | Free tier                                 |
| [Buildkite](https://buildkite.com)                    | Free for open source                      |
| [Codemagic](https://codemagic.io)                     | Free build allowance                      |
| [Bitrise](https://bitrise.io)                         | Free tier                                 |
| [Semaphore](https://semaphoreci.com)                  | Free tier                                 |
| [Drone CI](https://www.drone.io)                      | Open source                               |
| [Woodpecker CI](https://woodpecker-ci.org)            | Open source                               |
| [Act](https://github.com/nektos/act)                  | Run GitHub Actions locally                |

---

# 🐳 Containers & Registries

| Service                                                                                   | Free Tier                |
| ----------------------------------------------------------------------------------------- | ------------------------ |
| [GitHub Container Registry](https://ghcr.io)                                              | Free public images       |
| [Docker Hub](https://hub.docker.com)                                                      | Free repositories        |
| [GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/) | Free tier                |
| [Google Artifact Registry](https://cloud.google.com/artifact-registry)                    | Free allowance           |
| [AWS ECR](https://aws.amazon.com/ecr/)                                                    | Free allowance           |
| [Azure Container Registry](https://azure.microsoft.com/products/container-registry)       | Free allowance           |
| [Quay.io](https://quay.io)                                                                | Free public repositories |

---

# 🤖 AI / LLM APIs

Free AI quotas change particularly often, so verify current limits before building around them.

| Service                                                                | Free Offering                       |
| ---------------------------------------------------------------------- | ----------------------------------- |
| [Google AI Studio / Gemini API](https://ai.google.dev)                 | Free API quotas for selected models |
| [Groq](https://groq.com)                                               | Free developer API limits           |
| [Cerebras](https://www.cerebras.ai)                                    | Free developer access/limits        |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | Free allowance                      |
| [OpenRouter](https://openrouter.ai)                                    | Free models                         |
| [Hugging Face](https://huggingface.co)                                 | Free inference options              |
| [Mistral](https://mistral.ai)                                          | Free API tier                       |
| [Cohere](https://cohere.com)                                           | Developer/free options              |
| [Together AI](https://www.together.ai)                                 | Free/trial credits may vary         |
| [Ollama](https://ollama.com)                                           | Local models                        |
| [LM Studio](https://lmstudio.ai)                                       | Local inference                     |
| [Jan](https://jan.ai)                                                  | Local inference                     |
| [llama.cpp](https://github.com/ggml-org/llama.cpp)                     | Local inference                     |

> 💡 For a genuinely $0 AI application, local inference through Ollama/llama.cpp/LM Studio can be more predictable than depending on changing hosted API quotas.

---

# 🖼️ Image & Media Processing

| Service                                  | Free Tier                            |
| ---------------------------------------- | ------------------------------------ |
| [Cloudinary](https://cloudinary.com)     | Free media management/transformation |
| [ImageKit](https://imagekit.io)          | Free image/video CDN                 |
| [imgix](https://www.imgix.com)           | Trial/developer options              |
| [Uploadcare](https://uploadcare.com)     | Free tier                            |
| [Transloadit](https://transloadit.com)   | Free tier                            |
| [Sharp](https://sharp.pixelplumbing.com) | Open source                          |
| [FFmpeg](https://ffmpeg.org)             | Open source                          |
| [ImageMagick](https://imagemagick.org)   | Open source                          |

---

# 🗺️ Maps & Geolocation

| Service                                        | Free Offering           |
| ---------------------------------------------- | ----------------------- |
| [OpenStreetMap](https://www.openstreetmap.org) | Free map data           |
| [MapLibre](https://maplibre.org)               | Open source maps        |
| [MapTiler](https://www.maptiler.com)           | Free developer tier     |
| [Geoapify](https://www.geoapify.com)           | Free API quota          |
| [Nominatim](https://nominatim.org)             | OpenStreetMap geocoding |
| [Photon](https://github.com/komoot/photon)     | Open geocoder           |
| [Open-Meteo](https://open-meteo.com)           | Free weather API        |

---

# 🚩 Feature Flags

| Service                                  | Free Tier                |
| ---------------------------------------- | ------------------------ |
| [PostHog](https://posthog.com)           | Feature flags included   |
| [GrowthBook](https://www.growthbook.io)  | Open source + free cloud |
| [Flagsmith](https://flagsmith.com)       | Free tier + open source  |
| [Unleash](https://www.getunleash.io)     | Open source              |
| [ConfigCat](https://configcat.com)       | Free tier                |
| [LaunchDarkly](https://launchdarkly.com) | Free developer tier      |

---

# 🔀 API Gateways & Reverse Proxies

| Service                                                                                             | Free Offering             |
| --------------------------------------------------------------------------------------------------- | ------------------------- |
| [Cloudflare Workers](https://workers.cloudflare.com)                                                | Edge proxy/API            |
| [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) | Secure inbound tunnel     |
| [ngrok](https://ngrok.com)                                                                          | Free tunnels              |
| [Tailscale](https://tailscale.com)                                                                  | Free personal network     |
| [Caddy](https://caddyserver.com)                                                                    | Open source reverse proxy |
| [Traefik](https://traefik.io)                                                                       | Open source               |
| [Nginx](https://nginx.org)                                                                          | Open source               |

---

# 🖥️ Free VPS / Compute

| Service                                                     | Free Offering                   |
| ----------------------------------------------------------- | ------------------------------- |
| [Oracle Cloud](https://www.oracle.com/cloud/free/)          | Always Free compute             |
| [Google Cloud](https://cloud.google.com/free)               | Free-tier resources             |
| [AWS](https://aws.amazon.com/free/)                         | Free-tier resources             |
| [Azure](https://azure.microsoft.com/free/)                  | Free-tier resources             |
| [Cloudflare Workers](https://workers.cloudflare.com)        | Edge compute                    |
| [Deno Deploy](https://deno.com/deploy)                      | Free edge compute               |
| [Koyeb](https://www.koyeb.com)                              | Free instance                   |
| [Fly.io](https://fly.io)                                    | Limited free/credit offers vary |
| [GitHub Codespaces](https://github.com/features/codespaces) | Free monthly allowance          |
| [Google Colab](https://colab.research.google.com)           | Free compute                    |
| [Kaggle](https://www.kaggle.com)                            | Free notebooks/compute          |

> ⚠️ Cloud-provider "Always Free" programs frequently have region, account, capacity and eligibility restrictions. Treat them differently from simple $0 SaaS tiers.

---

# 📱 Mobile Development

| Service                                                                          | Free Offering                   |
| -------------------------------------------------------------------------------- | ------------------------------- |
| [Expo](https://expo.dev)                                                         | Free development platform       |
| [EAS](https://expo.dev/eas)                                                      | Free build/update allowance     |
| [Firebase](https://firebase.google.com)                                          | Backend + analytics + messaging |
| [Supabase](https://supabase.com)                                                 | Backend                         |
| [Appwrite](https://appwrite.io)                                                  | Backend                         |
| [OneSignal](https://onesignal.com)                                               | Push notifications              |
| [Firebase Cloud Messaging](https://firebase.google.com/products/cloud-messaging) | Free push notifications         |
| [RevenueCat](https://www.revenuecat.com)                                         | Free until revenue threshold    |
| [Sentry](https://sentry.io)                                                      | Crash/error monitoring          |
| [PostHog](https://posthog.com)                                                   | Product analytics               |

---

# 🔌 Useful Free APIs

| API                                                     | Purpose             |
| ------------------------------------------------------- | ------------------- |
| [Open-Meteo](https://open-meteo.com)                    | Weather             |
| [REST Countries](https://restcountries.com)             | Country information |
| [Frankfurter](https://www.frankfurter.app)              | Currency exchange   |
| [ExchangeRate API](https://www.exchangerate-api.com)    | Currency            |
| [Nager.Date](https://date.nager.at)                     | Public holidays     |
| [Open Library](https://openlibrary.org/developers/api)  | Books               |
| [OpenAlex](https://openalex.org)                        | Academic data       |
| [Crossref](https://www.crossref.org)                    | Academic metadata   |
| [NASA APIs](https://api.nasa.gov)                       | NASA data           |
| [OpenStreetMap](https://www.openstreetmap.org)          | Geographic data     |
| [PokéAPI](https://pokeapi.co)                           | Pokémon data        |
| [Jikan](https://jikan.moe)                              | MyAnimeList API     |
| [TMDB](https://www.themoviedb.org)                      | Movie/TV metadata   |
| [TVMaze](https://www.tvmaze.com/api)                    | TV metadata         |
| [Open-Meteo](https://open-meteo.com)                    | Weather             |
| [JSONPlaceholder](https://jsonplaceholder.typicode.com) | Test API            |
| [DummyJSON](https://dummyjson.com)                      | Test data           |
| [ReqRes](https://reqres.in)                             | API testing         |

---

# 💳 No-Credit-Card Services

This section is particularly useful for developers who want to build without entering payment information.

| Service                                  | Category       | Notes                                    |
| ---------------------------------------- | -------------- | ---------------------------------------- |
| [Neon](https://neon.com)                 | PostgreSQL     | Free plan explicitly says no credit card |
| [UptimeRobot](https://uptimerobot.com)   | Monitoring     | Free plan explicitly says no credit card |
| [Supabase](https://supabase.com)         | Backend        | Free signup                              |
| [Firebase](https://firebase.google.com)  | Backend        | Spark plan requires no payment method    |
| [Vercel](https://vercel.com)             | Hosting        | Free Hobby                               |
| [Netlify](https://www.netlify.com)       | Hosting        | Free plan                                |
| [Render](https://render.com)             | Hosting        | Free services                            |
| [Zeabur](https://zeabur.com)             | Hosting        | Free plan explicitly says no credit card |
| [Railway](https://railway.com)           | Hosting        | Current free plan says no credit card    |
| [Resend](https://resend.com)             | Email          | Free plan                                |
| [Cloudflare](https://www.cloudflare.com) | Infrastructure | Large free ecosystem                     |
| [GitHub](https://github.com)             | Git/CI         | Free developer account                   |
| [GitLab](https://gitlab.com)             | Git/CI         | Free tier                                |
| [Deno Deploy](https://deno.com/deploy)   | Edge           | Free plan                                |
| [Koyeb](https://www.koyeb.com)           | Hosting        | Free instance                            |
| [PostHog](https://posthog.com)           | Analytics      | Free tier                                |
| [Sentry](https://sentry.io)              | Error tracking | Free tier                                |
| [Expo](https://expo.dev)                 | Mobile         | Free development tooling                 |

Firebase's current pricing explicitly describes its Spark/no-cost plan as requiring **no payment method**, while Zeabur and Railway explicitly advertise no-credit-card signup/free usage.

---

# 🧰 Open-Source Alternatives

When a hosted service's free tier isn't enough, self-hosting can turn many services into effectively unlimited software.

| Hosted Service Category | Open Source Alternative |
| ----------------------- | ----------------------- |
| PostgreSQL              | PostgreSQL              |
| Redis                   | Valkey                  |
| MongoDB                 | MongoDB Community       |
| Search                  | Meilisearch             |
| Search                  | Typesense               |
| Analytics               | Umami                   |
| Analytics               | Matomo                  |
| Monitoring              | Uptime Kuma             |
| Error Tracking          | GlitchTip               |
| Auth                    | Keycloak                |
| Auth                    | Authelia                |
| Backend                 | Appwrite                |
| Backend                 | PocketBase              |
| Backend                 | Supabase                |
| Object Storage          | MinIO                   |
| Git                     | Gitea                   |
| CI/CD                   | Woodpecker CI           |
| Reverse Proxy           | Caddy                   |
| Reverse Proxy           | Traefik                 |
| VPN                     | WireGuard               |
| Network                 | Tailscale               |
| Workflow                | n8n                     |
| Automation              | Activepieces            |
| LLM                     | Ollama                  |
| LLM                     | llama.cpp               |
| Vector DB               | Qdrant                  |
| Vector DB               | Chroma                  |
| Vector DB               | Weaviate                |

---

# 🏗️ Example $0 Stack

A surprisingly capable solo-developer stack can be assembled from these services:

```text
                    ┌──────────────────────┐
                    │       Cloudflare     │
                    │ DNS / CDN / WAF      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       Vercel         │
                    │ Frontend / API       │
                    └──────────┬───────────┘
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
          ┌────────────┐ ┌───────────┐ ┌───────────┐
          │    Neon    │ │  Upstash  │ │ Cloudflare│
          │ PostgreSQL │ │   Redis   │ │    R2     │
          └────────────┘ └───────────┘ └───────────┘
                 │
                 ▼
          ┌────────────┐
          │   Resend   │
          │   Email    │
          └────────────┘

          ┌────────────┐
          │ UptimeRobot│
          │ Monitoring │
          └────────────┘
```

For a more backend-heavy application:

```text
Cloudflare
    │
    ├── DNS
    ├── CDN
    ├── WAF
    ├── Workers
    ├── R2
    └── Tunnel
          │
          ▼
       Render
          │
          ├── API
          ├── Worker
          └── Cron
                 │
                 ▼
              Neon
            PostgreSQL

        + Resend
        + Sentry
        + UptimeRobot
```

---

# 🔍 What Counts as "Generous"?

A service is particularly interesting for this list when it satisfies several of these:

* ✅ $0 permanent tier
* ✅ No credit card required
* ✅ No forced trial
* ✅ Reasonable monthly quota
* ✅ Suitable for production hobby projects
* ✅ API/SDK available
* ✅ No artificial "demo only" restrictions
* ✅ Multiple projects allowed
* ✅ Doesn't require a sales call
* ✅ Clear published limits
* ✅ Can be combined with other free services
* ✅ Useful to solo developers

## 🏆 Suggested Labels

Use these labels when contributing:

* `🟢 Free Forever`
* `💳 No Credit Card`
* `🔥 Generous`
* `⚡ Serverless`
* `🐘 PostgreSQL`
* `🗄️ Database`
* `📦 Storage`
* `🌐 Hosting`
* `⏰ Cron`
* `📈 Monitoring`
* `🤖 AI`
* `📧 Email`
* `🔐 Auth`
* `🧑‍💻 Developer Tool`
* `🏠 Self-Hostable`

---

# ⚠️ Important

Free-tier information changes frequently.

Before deploying something important, verify:

1. Monthly quotas
2. Whether the service requires a credit card
3. Whether overages are possible
4. Whether the service automatically upgrades you
5. Idle/sleep behavior
6. Data retention
7. Geographic restrictions
8. Terms of service
9. Commercial-use restrictions
10. Whether the free tier is permanent or promotional

**This repository should prefer official pricing/documentation sources over third-party lists.**

---

# 🤝 Contributing

Pull requests are welcome.

When adding a service, please include:

* Service name
* Category
* Official website
* Free-tier limits
* Credit-card requirement
* Whether the tier is permanent
* Important restrictions
* Last-verified date

Example:

```markdown
| [Example](https://example.com) | Database | 1 GB storage, 100K requests/month | ❌ | Free forever |
```

Please **do not submit services that only offer a short free trial** unless they also have a permanent free tier.

---

# 📚 Related Lists

* [free-for.dev](https://github.com/ripienaar/free-for-dev) — Large infrastructure-focused free-tier list
* [free-services-dev](https://github.com/servicosgratis/free-services-dev) — Free developer services
* [Free Developer Tools](https://github.com/mathewlewallen/awesome-free-tools) — Free developer-friendly tools
* [Free Developer Resources](https://github.com/papanito/free-dev-resources) — XaaS resources

The established `free-for.dev` project is a particularly useful reference point: it restricts inclusion to services with a free tier rather than merely a temporary trial and has accumulated contributions from a large developer community.

---

## ⭐ Philosophy

> **Build more. Pay less. Ship sooner.**

The purpose of this list isn't to find the cheapest paid infrastructure.

It's to discover combinations of genuinely useful free services that allow an individual developer to build surprisingly capable applications without spending money on infrastructure.
