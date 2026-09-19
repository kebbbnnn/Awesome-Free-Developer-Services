# 🚀 Awesome Free Developer Services

> A curated list of developer-friendly services with **generous free tiers** for solo developers, indie hackers, students, hobby projects, prototypes, and small SaaS applications.

The goal of this list is to help you build and run real projects with **$0 infrastructure cost for as long as possible**.

> ⚠️ **Free doesn't always mean unlimited.** Always check the provider's current pricing and fair-use policies before relying on a service for production workloads.

## Contents

* [Databases](#-databases)
* [Vector Databases & Embeddings](#-vector-databases--embeddings)
* [Backend & App Hosting](#-backend--app-hosting)
* [Serverless & Edge](#-serverless--edge)
* [Object & File Storage](#-object--file-storage)
* [CDN & DNS](#-cdn--dns)
* [Monitoring & Uptime](#-monitoring--uptime)
* [Logging & Observability](#-logging--observability)
* [Error Tracking](#-error-tracking)
* [Email](#-email)
* [Authentication](#-authentication)
* [Headless CMS & Content](#-headless-cms--content)
* [Forms & Feedback](#-forms--feedback)
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
* [Feature Flags](#-feature-flags)
* [API Gateways & Reverse Proxies](#-api-gateways--reverse-proxies)
* [Developer Utilities](#-developer-utilities)
* [Free VPS / Compute](#-free-vps--compute)
* [Mobile Development](#-mobile-development)
* [Useful Free APIs](#-useful-free-apis)
* [No-Credit-Card Services](#-no-credit-card-services)
* [Open-Source Alternatives](#-open-source-alternatives)
* [Example $0 Stacks](#-example-0-stacks)

---

# 🗄️ Databases

| Service                                        | Type                               | Free Tier                                                | CC Required |
| ---------------------------------------------- | ---------------------------------- | -------------------------------------------------------- | ----------- |
| [Neon](https://neon.com)                       | PostgreSQL                         | 100 projects, 100 CU-hours/project/month, 0.5 GB/project | ❌           |
| [TiDB Cloud](https://tidbcloud.com)            | MySQL (Serverless)                 | 25 GiB storage, 50M Request Units/month                  | ❌           |
| [Turso](https://turso.tech)                    | SQLite/LibSQL                      | Generous database/storage/read quotas                    | ❌           |
| [Supabase](https://supabase.com)               | PostgreSQL                         | 500 MB DB, 1 GB storage, 50K MAU                         | ❌           |
| [Xata](https://xata.io)                        | PostgreSQL Data Platform           | 15 GB storage, unlimited schema branches                 | ❌           |
| [Firebase](https://firebase.google.com)        | NoSQL                              | Spark plan with free quotas                              | ❌           |
| [MongoDB Atlas](https://www.mongodb.com/atlas) | MongoDB                            | Free shared cluster                                      | ❌*          |
| [CockroachDB](https://www.cockroachlabs.com)   | SQL                                | Free serverless tier                                     | ❌*          |
| [Convex](https://www.convex.dev)               | Reactive DB                        | Free developer tier                                      | ❌           |
| [SurrealDB](https://surrealdb.com)             | Multi-Model (Relational/Graph/Doc) | Free local and developer tiers                           | ❌           |
| [Appwrite](https://appwrite.io)                | SQL/Backend                        | Free cloud tier                                          | ❌           |
| [PlanetScale](https://planetscale.com)         | MySQL                              | Free developer options may vary                          | ⚠️          |
| [Upstash](https://upstash.com)                 | Redis                              | Free Redis tier                                          | ❌           |
| [Tinybird](https://www.tinybird.co)            | ClickHouse                         | Free tier                                                | ❌           |
| [Nhost](https://nhost.io)                      | PostgreSQL                         | Free backend tier                                        | ❌           |
| [PocketBase](https://pocketbase.io)            | SQLite                             | Self-hosted                                              | —           |

### ⭐ Particularly useful

**Neon** is excellent when you simply need PostgreSQL without maintaining a server. Its current Free plan includes 100 projects, 100 CU-hours per project/month and 0.5 GB storage per project.

**TiDB Cloud (Serverless)** provides a remarkably generous 25 GiB free storage and 50 million Request Units/month with zero credit card required, making it one of the largest free MySQL-compatible database offerings available.

**Supabase** combines PostgreSQL, authentication, storage and APIs. Its current Free plan includes a 500 MB database, 1 GB file storage and 50,000 MAU, although inactive free projects can be paused.

---

# 🧠 Vector Databases & Embeddings

| Service                                                              | Type                   | Free Tier                                              | CC Required |
| -------------------------------------------------------------------- | ---------------------- | ------------------------------------------------------ | ----------- |
| [Pinecone](https://www.pinecone.io)                                  | Serverless Vector DB   | 1 serverless index, up to 2 GB storage (~100k vectors) | ❌           |
| [Qdrant Cloud](https://cloud.qdrant.io)                              | Vector DB              | 1 free cluster, 1 GB RAM, 0.5 vCPU, 4 GB disk          | ❌           |
| [Zilliz Cloud](https://zilliz.com/cloud)                             | Milvus-based Vector DB | 2 collections, 500k vectors, 50 CU free monthly        | ❌           |
| [Cloudflare Vectorize](https://developers.cloudflare.com/vectorize/) | Edge Vector DB         | 30M queried dimensions/mo, 5M stored dimensions        | ❌           |
| [pgvector](https://github.com/pgvector/pgvector)                     | PostgreSQL Extension   | Included in free Neon and Supabase tiers               | ❌           |
| [Chroma](https://www.trychroma.com)                                  | Embedded Vector DB     | Open source / local / self-hostable                    | —           |
| [Weaviate Cloud](https://weaviate.io)                                | Hybrid/Vector DB       | 14-day dynamic sandboxes or free open source           | —           |

### ⭐ Particularly useful

**Qdrant Cloud** offers a permanent 1 GB cluster (no credit card) running true native Rust vector search. If you are building with PostgreSQL on Neon or Supabase, **pgvector** is pre-installed and uses your existing database quota without requiring a separate vector provider.

---

# ☁️ Backend & App Hosting

| Service                                                          | Free Tier                                  | Best For                           |
| ---------------------------------------------------------------- | ------------------------------------------ | ---------------------------------- |
| [Render](https://render.com)                                     | Free services                              | APIs, Node, Python                 |
| [Vercel](https://vercel.com)                                     | Hobby                                      | Next.js, React, APIs               |
| [Netlify](https://www.netlify.com)                               | Free                                       | Frontend + functions               |
| [Hugging Face Spaces](https://huggingface.co/spaces)             | Free basic CPU (2 vCPU, 16 GB RAM)         | Python, Gradio, Streamlit, Docker  |
| [Deno Deploy](https://deno.com/deploy)                           | Free                                       | TypeScript/JavaScript              |
| [Cloudflare Pages](https://pages.cloudflare.com)                 | Free                                       | Static/JAMstack                    |
| [Firebase Hosting](https://firebase.google.com/products/hosting) | Free                                       | Web apps                           |
| [Coolify](https://coolify.io)                                     | Open source / self-hosted                  | Unlimited apps on any VPS/compute  |
| [Northflank](https://northflank.com)                             | Free micro developer plan                  | 1 service, 1 cron job, 1 database  |
| [GitHub Pages](https://pages.github.com)                         | Free                                       | Static websites                    |
| [GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)   | Free                                       | Static websites                    |
| [Surge](https://surge.sh)                                        | Free                                       | Simple static hosting              |
| [Koyeb](https://www.koyeb.com)                                   | Free instance                              | Containers/APIs                    |
| [Zeabur](https://zeabur.com)                                     | Free plan                                  | Containers/apps                    |
| [Railway](https://railway.com)                                   | $1/month free credit                       | APIs/workers/databases             |
| [Fly.io](https://fly.io)                                         | Limited free allowances / credits may vary | Containers                         |
| [PythonAnywhere](https://www.pythonanywhere.com)                 | Free plan                                  | Python                             |
| [Replit](https://replit.com)                                     | Free plan                                  | Prototyping                        |
| [Glitch](https://glitch.com)                                     | Free options                               | Small web projects                 |

Vercel's current Hobby plan is $0 and includes items such as automatic CI/CD, CDN, DDoS mitigation and serverless/edge functionality.

**Hugging Face Spaces** is an exceptional free resource for backend Python applications, Gradio/Streamlit dashboards, and Dockerized microservices, offering 2 vCPU and 16 GB of RAM on its basic CPU tier with $0 infrastructure cost.

Netlify currently offers a $0 Free plan with 300 monthly credits and includes deployment, previews, functions, database/blob functionality and CDN delivery.

Railway is worth including, but with an important caveat: its current free plan provides **$1/month of free usage after the initial $5/30-day trial**, rather than unlimited free hosting.

---

# ⚡ Serverless & Edge

| Service                                                                          | Free Tier                          | Runtime              |
| -------------------------------------------------------------------------------- | ---------------------------------- | -------------------- |
| [Cloudflare Workers](https://workers.cloudflare.com)                             | Generous free requests (100k/day)  | JS/TS/WASM           |
| [Deno Deploy](https://deno.com/deploy)                                           | 1M requests/month                  | JS/TS                |
| [Vercel Functions](https://vercel.com/docs/functions)                            | Free Hobby quota                   | JS/TS                |
| [Netlify Functions](https://www.netlify.com/products/functions/)                 | Included in Free                   | JS/TS                |
| [Fastly Compute](https://www.fastly.com/products/compute)                       | $50/month free developer credit    | Rust, JS, Go, WASM   |
| [Val Town](https://www.val.town)                                                 | 50,000 runs/month                  | JS/TS                |
| [Firebase Functions](https://firebase.google.com/docs/functions)                 | Limited no-cost usage              | Node/Python          |
| [AWS Lambda](https://aws.amazon.com/lambda/)                                     | Free tier (1M requests/mo)         | Multiple             |
| [Google Cloud Run](https://cloud.google.com/run)                                 | Free quota (2M requests/mo)        | Containers           |
| [Azure Functions](https://azure.microsoft.com/products/functions)                | Free quota (1M executions/mo)      | Multiple             |
| [Koyeb](https://www.koyeb.com)                                                   | Free instance                      | Containers           |
| [Modal](https://modal.com)                                                       | $30/month free recurring credits   | Python/GPU           |
| [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) | Free allowance                     | JS/TS                |

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

| Service                                                     | Free Tier                                          |
| ----------------------------------------------------------- | -------------------------------------------------- |
| [UptimeRobot](https://uptimerobot.com)                      | 50 monitors, 5-minute interval                     |
| [Better Stack](https://betterstack.com)                     | Free monitoring tier                               |
| [Checkly](https://www.checklyhq.com)                        | 10,000 checks/month, API & Playwright browser synthetic checks |
| [Instatus](https://instatus.com)                            | Free status page, custom domain, unlimited subscribers |
| [OpenStatus](https://openstatus.dev)                        | 10 synthetic monitors, free status page, open source |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma)      | Self-hosted                                        |
| [HetrixTools](https://hetrixtools.com)                      | Free monitoring                                    |
| [Pingdom](https://www.pingdom.com)                          | Limited trial/free options may vary                |
| [Cronitor](https://cronitor.io)                             | Free cron monitoring                               |
| [Healthchecks.io](https://healthchecks.io)                  | Free cron monitoring                               |
| [Oh Dear](https://ohdear.app)                               | Free/limited options                               |
| [Freshping](https://www.freshworks.com/website-monitoring/) | Free monitoring                                    |

UptimeRobot currently offers **50 monitors**, HTTP/port/ping/keyword/API/UDP/DNS/SSL monitoring and a 5-minute interval on its $0 plan, with no credit card required.

---

# 📋 Logging & Observability

| Service                                             | Free Tier                                               | CC Required |
| --------------------------------------------------- | ------------------------------------------------------- | ----------- |
| [Axiom](https://axiom.co)                           | 0.5 TB ingestion/month, 30-day retention, 3 users        | ❌           |
| [Grafana Cloud](https://grafana.com/products/cloud) | 10k metric series, 50 GB logs, 50 GB traces, 3 users     | ❌           |
| [New Relic](https://newrelic.com)                   | 100 GB/month forever free data ingest, 1 platform user  | ❌           |
| [Better Stack Logs](https://betterstack.com/logs)   | 1 GB/month, 3-day retention, Live Tail search           | ❌           |
| [HyperDX](https://www.hyperdx.io)                   | Open-source Datadog alternative + free developer cloud  | ❌           |

### ⭐ Particularly useful

**Axiom** provides an extraordinary **0.5 TB (500 GB) per month** log ingestion allowance on its Free plan with no credit card required, making it unmatched for serverless and container logging.

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

| Service                                   | Free Tier                                                 |
| ----------------------------------------- | --------------------------------------------------------- |
| [Resend](https://resend.com)              | 3,000 emails/month (100 emails/day)                       |
| [Plunk](https://useplunk.com)             | 3,000 emails/month free, open-source transactional platform|
| [Brevo](https://www.brevo.com)            | Free daily email allowance (300 emails/day)               |
| [Mailjet](https://www.mailjet.com)        | Free tier (6,000 emails/month, 200 emails/day)            |
| [Forward Email](https://forwardemail.net) | 100% free open-source email forwarding for custom domains |
| [ImprovMX](https://improvmx.com)          | Free email forwarding for 1 domain (up to 25 aliases)     |
| [Mailtrap](https://mailtrap.io)           | Email Sandbox: 100 test emails/month, safe staging testing|
| [MailerSend](https://www.mailersend.com)  | Free tier                                                 |
| [Loops](https://loops.so)                 | Free tier                                                 |
| [Amazon SES](https://aws.amazon.com/ses/) | Limited free allowance under certain conditions           |
| [SendGrid](https://sendgrid.com)          | Free/trial options vary                                   |
| [Mailgun](https://www.mailgun.com)        | Trial/free options vary                                   |

Resend currently offers **3,000 emails/month**, with a 100-email/day limit on its Free plan.

---

# 🔐 Authentication

| Service                                                              | Free Tier                                     |
| -------------------------------------------------------------------- | --------------------------------------------- |
| [Supabase Auth](https://supabase.com/auth)                           | 50K MAU                                       |
| [Firebase Authentication](https://firebase.google.com/products/auth) | Free authentication                           |
| [Clerk](https://clerk.com)                                           | Free developer tier (10,000 MAU)              |
| [Zitadel](https://zitadel.com)                                       | 25,000 requests/month free cloud + open source|
| [Auth0](https://auth0.com)                                           | Free tier (7,500 active users)                |
| [Kinde](https://kinde.com)                                           | Free tier                                     |
| [SuperTokens](https://supertokens.com)                               | 5,000 MAU free managed cloud + open source    |
| [Ory Network](https://www.ory.sh)                                    | 200 DAU free developer tier + open source     |
| [WorkOS](https://workos.com)                                         | Free developer features                       |
| [Logto](https://logto.io)                                            | Free tier + open source                       |
| [Better-Auth](https://better-auth.com)                               | Open-source, framework-agnostic TypeScript auth|
| [PocketBase](https://pocketbase.io)                                  | Self-hosted                                   |
| [Appwrite](https://appwrite.io)                                      | Free tier                                     |

---

# 📝 Headless CMS & Content

| Service                               | Free Tier                                                    | Best For                           | CC Required |
| ------------------------------------- | ------------------------------------------------------------ | ---------------------------------- | ----------- |
| [Sanity.io](https://www.sanity.io)    | 3 users, 10k documents, 100k API CDN requests, 100 GB assets | Structured content & modern web    | ❌           |
| [Contentful](https://www.contentful.com)| Community: 1 space, 25k records, 2 locales                 | Traditional headless CMS           | ❌           |
| [Prismic](https://prismic.io)         | Free for 1 user, unlimited API calls, 100 documents          | Visual page building               | ❌           |
| [Decap CMS](https://decapcms.org)     | Open source (formerly Netlify CMS), Git-based                 | Static / Jamstack sites            | —           |
| [Payload CMS](https://payloadcms.com) | Open source Next.js-native headless CMS                      | Full-stack TypeScript applications | —           |
| [Strapi](https://strapi.io)           | Community Edition (open source)                              | Self-hosted REST/GraphQL CMS       | —           |

---

# 📬 Forms & Feedback

| Service                             | Free Tier                                                      | CC Required |
| ----------------------------------- | -------------------------------------------------------------- | ----------- |
| [Web3Forms](https://web3forms.com)  | Unlimited form submissions to email, access keys, spam filter  | ❌           |
| [Tally.so](https://tally.so)        | Unlimited forms, unlimited responses, 99% of features free     | ❌           |
| [Formspree](https://formspree.io)   | 50 submissions/month, email notifications                      | ❌           |
| [FormSubmit](https://formsubmit.co) | Unlimited submissions via simple HTML action URL, zero signup  | ❌           |

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

| Service                                                                                                    | Free Tier                                                 |
| ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [GitHub Actions Scheduled Workflows](https://docs.github.com/en/actions)                                   | Free cron scheduling (public & included private minutes)  |
| [Cron-job.org](https://cron-job.org)                                                                       | Free webcron execution                                    |
| [EasyCron](https://www.easycron.com)                                                                       | Free tier                                                 |
| [Cloudflare Workers Cron Triggers](https://developers.cloudflare.com/workers/configuration/cron-triggers/) | Free allowance                                            |
| [Deno Cron](https://deno.com/deploy)                                                                       | Included with Deno                                        |
| [Vercel Cron](https://vercel.com/docs/cron-jobs)                                                           | Free/Hobby allowance                                      |
| [Netlify Scheduled Functions](https://docs.netlify.com/functions/scheduled-functions/)                     | Free allowance                                            |
| [Inngest](https://www.inngest.com)                                                                         | Free tier                                                 |
| [Trigger.dev](https://trigger.dev)                                                                         | Free tier                                                 |

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

| Service                                                                | Free Offering                                              |
| ---------------------------------------------------------------------- | ---------------------------------------------------------- |
| [Google AI Studio / Gemini API](https://ai.google.dev)                 | Generous free rate limits for Gemini 1.5 & 2.0 Flash       |
| [GitHub Models](https://github.com/marketplace/models)                 | Free playground & API access (GPT-4o, Llama 3.3, Mistral)  |
| [Groq](https://groq.com)                                               | Free developer API limits with ultra-fast LPU inference     |
| [Cerebras](https://www.cerebras.ai)                                    | Free developer access / high token-per-second inference    |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | Free daily allowance (10,000 Neurons/day)                  |
| [OpenRouter](https://openrouter.ai)                                    | Free models (endpoints tagged with `:free`)                |
| [Voyage AI](https://www.voyageai.com)                                   | First 200M tokens free for high-accuracy embeddings        |
| [Hugging Face](https://huggingface.co)                                 | Free serverless inference API                              |
| [Mistral](https://mistral.ai)                                          | Free developer API tier (Le Chat & Mistral models)         |
| [Cohere](https://cohere.com)                                           | Developer trial API key for testing                        |
| [Together AI](https://www.together.ai)                                 | Free trial credits                                         |
| [Ollama](https://ollama.com)                                           | Local models                                               |
| [LM Studio](https://lmstudio.ai)                                       | Local inference                                            |
| [Jan](https://jan.ai)                                                  | Local inference                                            |
| [llama.cpp](https://github.com/ggml-org/llama.cpp)                     | Local inference                                            |

> 💡 **Pro-Tip**: **GitHub Models** allows developers to test leading commercial LLMs (like GPT-4o and Mistral Large) via standard OpenAI-compatible SDKs using a personal GitHub token at $0 cost. **Google AI Studio** offers one of the highest hosted free-tier throughput allowances for Gemini models (up to 15 RPM / 1M TPM on Flash tiers).
>
> For a genuinely zero-cost, permanent AI application without external API rate limits, running local models via **Ollama** or **llama.cpp** provides complete predictability.

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

# 🛠️ Developer Utilities

### 🚇 Local Tunnels & Port Forwarding

| Tool | Free Offering | Notes |
| ---- | ------------- | ----- |
| [Cloudflare Tunnel (cloudflared)](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) | 100% free, unlimited bandwidth, HTTPS, no open inbound ports | Requires free Cloudflare account & domain |
| [ngrok](https://ngrok.com) | 1 static domain, 1 online tunnel, 1 GB/month bandwidth | Standard tool for testing webhook delivery |
| [Pinggy.io](https://pinggy.io) | Free HTTP/TCP tunnels via single SSH command | `ssh -p 443 -R0:localhost:3000 a.pinggy.io` (no CLI install required) |
| [zrok](https://zrok.io) | Open-source peer-to-peer & public tunneling service | Free SaaS tier available |
| [Localtunnel](https://localtunnel.me) | Free open-source tunnel client | Instant HTTPS URL for localhost |

### 🔍 Webhooks & API Testing

| Tool | Free Offering | Best For |
| ---- | ------------- | -------- |
| [Webhook.site](https://webhook.site) | Instant unique URL to inspect incoming requests and headers in real-time | Webhook debugging & custom mock responses |
| [Beeceptor](https://beeceptor.com) | Instant mock REST API endpoints (50 requests/day free) | Mocking endpoints without writing code |
| [Smee.io](https://smee.io) | Webhook payload delivery service | Forwarding GitHub webhooks to localhost |
| [Bruno](https://www.usebruno.com) | 100% free, offline-first, Git-friendly open-source API client | Postman alternative (stores collections in your Git repo) |
| [Hoppscotch](https://hoppscotch.com) | Lightweight, open-source web-based API testing client | Fast browser-based API testing |

### 📐 Architecture & Diagrams

| Tool | Free Offering | Best For |
| ---- | ------------- | -------- |
| [dbdiagram.io](https://dbdiagram.io) | Free quick database ER diagrams via simple DBML syntax | Database schema design |
| [Eraser.io](https://www.eraser.io) | Free tier for technical architecture docs & diagrams | System diagrams & flowcharts |
| [Excalidraw](https://excalidraw.com) | Free, open-source, end-to-end encrypted virtual whiteboard | Architecture sketching |
| [Mermaid Live Editor](https://mermaid.live) | Free online editor and live renderer for Mermaid diagrams | Markdown-compatible text-to-diagrams |

### 🎨 Assets & Presentation

| Tool | Free Offering | Best For |
| ---- | ------------- | -------- |
| [Ray.so](https://ray.so) | Free code-to-image generator with customizable syntax themes | Documentation & social code snippets |
| [SVGOMG](https://svgomg.net) | Free open-source SVGO optimizer | Minimizing SVG asset sizes |
| [Favicon.io](https://favicon.io) | Free favicon generator from emoji, text, or image | Generating complete ICO, PNG, and manifest assets |

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

| API                                                     | Purpose                                                    |
| ------------------------------------------------------- | ---------------------------------------------------------- |
| [Open-Meteo](https://open-meteo.com)                    | Weather & forecasts (no API key required)                  |
| [REST Countries](https://restcountries.com)             | Country facts, borders, currencies                         |
| [Frankfurter](https://www.frankfurter.app)              | Currency exchange rates & historical forex                 |
| [ExchangeRate API](https://www.exchangerate-api.com)    | Currency conversion rates                                  |
| [ip-api.com](https://ip-api.com)                        | IP Geolocation (45 req/min free, no API key required)      |
| [ipapi.co](https://ipapi.co)                            | IP Geolocation (30,000 requests/month free)                |
| [GitHub API](https://docs.github.com/en/rest)           | Public repo, user, and commit data (5,000 req/hr with PAT) |
| [Hacker News API](https://github.com/HackerNews/API)    | Official real-time Firebase API for stories and comments   |
| [Nager.Date](https://date.nager.at)                     | Public holidays worldwide                                  |
| [Open Library](https://openlibrary.org/developers/api)  | Book metadata and covers                                   |
| [OpenAlex](https://openalex.org)                        | Scientific papers & scholarly data                         |
| [Crossref](https://www.crossref.org)                    | Academic DOI metadata                                      |
| [NASA APIs](https://api.nasa.gov)                       | Astronomy images, Mars rovers, asteroid data               |
| [OpenStreetMap](https://www.openstreetmap.org)          | Global geographic map data                                 |
| [Unsplash API](https://unsplash.com/developers)         | High-resolution photography (50 req/hour free)             |
| [Open Food Facts](https://world.openfoodfacts.org/data) | Open database of food barcodes and ingredients             |
| [PokéAPI](https://pokeapi.co)                           | Pokémon data & sprites                                     |
| [Jikan](https://jikan.moe)                              | Unofficial MyAnimeList REST API                            |
| [TMDB](https://www.themoviedb.org)                      | Movie, TV, and actor metadata                              |
| [TVMaze](https://www.tvmaze.com/api)                    | TV schedule and show metadata                              |
| [JSONPlaceholder](https://jsonplaceholder.typicode.com) | Fake REST API for prototyping and testing                  |
| [DummyJSON](https://dummyjson.com)                      | Realistic dummy JSON data (products, users, carts)         |
| [ReqRes](https://reqres.in)                             | REST API endpoint simulation for frontends                 |

---

# 💳 No-Credit-Card Services

This section is particularly useful for developers who want to build without entering payment information.

| Service                                                | Category       | Notes                                    |
| ------------------------------------------------------ | -------------- | ---------------------------------------- |
| [Neon](https://neon.com)                               | PostgreSQL     | Free plan explicitly says no credit card |
| [TiDB Cloud](https://tidbcloud.com)                    | MySQL          | 25 GiB storage, 50M RU/mo free           |
| [Turso](https://turso.tech)                            | SQLite         | Generous quotas with no credit card      |
| [Supabase](https://supabase.com)                       | Backend        | Free signup without payment details      |
| [Firebase](https://firebase.google.com)                | Backend        | Spark plan requires no payment method    |
| [Pinecone](https://www.pinecone.io)                    | Vector DB      | 1 serverless index, up to 2 GB vectors   |
| [Qdrant Cloud](https://cloud.qdrant.io)                | Vector DB      | 1 free cluster, 1 GB RAM forever free    |
| [Axiom](https://axiom.co)                              | Logging        | 0.5 TB log ingestion/month, 30-day retention |
| [Sanity.io](https://www.sanity.io)                    | Headless CMS   | 10k documents, 100k API requests/month   |
| [Web3Forms](https://web3forms.com)                     | Forms          | Unlimited form submissions to email      |
| [Tally.so](https://tally.so)                           | Forms          | Unlimited forms and submissions          |
| [GitHub Models](https://github.com/marketplace/models) | AI / LLM       | Free access to GPT-4o, Llama 3.3 via PAT |
| [Vercel](https://vercel.com)                           | Hosting        | Free Hobby                               |
| [Netlify](https://www.netlify.com)                     | Hosting        | Free plan                                |
| [Render](https://render.com)                           | Hosting        | Free services                            |
| [Zeabur](https://zeabur.com)                           | Hosting        | Free plan explicitly says no credit card |
| [Railway](https://railway.com)                         | Hosting        | Current free plan says no credit card    |
| [Resend](https://resend.com)                           | Email          | Free plan (3k emails/mo)                 |
| [UptimeRobot](https://uptimerobot.com)                 | Monitoring     | Free plan explicitly says no credit card |
| [Cloudflare](https://www.cloudflare.com)               | Infrastructure | Large free ecosystem                     |
| [GitHub](https://github.com)                           | Git/CI         | Free developer account                   |
| [GitLab](https://gitlab.com)                           | Git/CI         | Free tier                                |
| [Deno Deploy](https://deno.com/deploy)                 | Edge           | Free plan                                |
| [Koyeb](https://www.koyeb.com)                         | Hosting        | Free instance                            |
| [PostHog](https://posthog.com)                         | Analytics      | Free tier                                |
| [Sentry](https://sentry.io)                            | Error tracking | Free tier                                |
| [Expo](https://expo.dev)                               | Mobile         | Free development tooling                 |

Firebase's current pricing explicitly describes its Spark/no-cost plan as requiring **no payment method**, while Zeabur, TiDB Cloud, and Railway explicitly advertise no-credit-card signup/free usage.

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
| PaaS / Hosting          | Coolify                 |
| Headless CMS            | Payload CMS / Strapi    |
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

# 🏗️ Example $0 Stacks

A surprisingly capable solo-developer stack can be assembled from these services:

### 1. Modern Web / SaaS Application
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

### 2. Backend-Heavy / Worker Architecture
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

        + Resend (Transactional Email)
        + Sentry (Error Tracking)
        + UptimeRobot (Heartbeat & Uptime)
```

### 3. Modern AI / RAG Application ($0 Stack)
```text
                    ┌─────────────────────────┐
                    │       Cloudflare        │
                    │  DNS / CDN / WAF / SSL  │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │         Vercel          │
                    │  Next.js Frontend & API │
                    └──────┬───────────┬──────┘
                           │           │
            ┌──────────────┴──────┐    └──────────────┐
            │                     │                   │
            ▼                     ▼                   ▼
    ┌───────────────┐     ┌───────────────┐   ┌───────────────┐
    │  TiDB / Neon  │     │Pinecone/Qdrant│   │ GitHub Models │
    │ Relational DB │     │   Vector DB   │   │  / Gemini API │
    └───────┬───────┘     └───────────────┘   └───────────────┘
            │
            ▼
    ┌───────────────┐     ┌───────────────┐   ┌───────────────┐
    │    Resend     │     │     Axiom     │   │  UptimeRobot  │
    │  Email / Auth │     │0.5TB Log Ingest│  │Uptime & Alerts│
    └───────────────┘     └───────────────┘   └───────────────┘
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
