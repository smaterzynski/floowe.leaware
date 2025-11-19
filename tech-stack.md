# Tech Stack - Floowe Platform

## Frontend

### Core
- **React**: 18.x
- **TypeScript**: 5.x
- **Build Tool**: Vite
- **Package Manager**: pnpm

### State Management
- Context API
- React Query (TanStack Query)
- Zustand (lightweight store)

### UI & Styling
- TailwindCSS 3.x
- shadcn/ui components
- Radix UI primitives
- Framer Motion (animations)

### Forms & Validation
- React Hook Form
- Zod (schema validation)

### Real-time
- Socket.io-client
- WebSocket native API

### Rich Text Editing
- Draft.js / Slate.js
- TipTap

### Data Visualization
- Recharts
- Chart.js
- D3.js

### Date/Time
- date-fns
- day.js

## Backend

### Runtime & Framework
- **Node.js**: 18+ LTS
- **NestJS**: 10.x (primary framework)
- **Express**: (fallback/simple services)

### API
- RESTful API
- GraphQL (Apollo Server)
- WebSocket (Socket.io)

### Database
- **PostgreSQL**: 15+ (primary)
- **MongoDB**: 6+ (content/drafts)
- **Redis**: 7+ (cache, sessions, queues)
- **Elasticsearch**: 8+ (full-text search)
- **TimescaleDB**: (time-series analytics)

### ORM/ODM
- Prisma (PostgreSQL)
- Mongoose (MongoDB)
- TypeORM (alternative)

### Message Queue
- Bull Queue + Redis
- RabbitMQ
- Apache Kafka (large scale)

### Background Jobs
- Bull (Redis-based)
- Agenda (MongoDB-based)
- node-cron (scheduling)

### Authentication
- Passport.js
- JWT
- OAuth 2.0

### Testing
- Jest
- Supertest
- Playwright (E2E)

## AI/ML Stack

### Languages
- **Python**: 3.10+
- **TypeScript**: (for Node.js services)

### ML Framework
- TensorFlow 2.x
- PyTorch
- scikit-learn
- XGBoost / LightGBM

### NLP
- spaCy
- NLTK
- Transformers (Hugging Face)

### LLM APIs
- Anthropic Claude API
- OpenAI GPT-4 API
- LanguageTool API

### ML Serving
- FastAPI (Python microservices)
- TensorFlow Serving
- Seldon Core

### MLOps
- MLflow (experiment tracking)
- DVC (data version control)
- Apache Airflow (orchestration)
- Feast (feature store)

### Data Processing
- pandas
- numpy
- polars (high performance)

## Web Scraping

- Puppeteer
- Playwright
- Cheerio (HTML parsing)
- Bright Data API
- ScrapingBee API

## External Integrations

### Content & Publishing
- WordPress REST API
- Facebook Graph API
- LinkedIn API
- Twitter API v2

### SEO & Analytics
- Google Analytics 4
- Google Search Console API
- SEMrush API
- Ahrefs API
- Facebook Pixel

### Translation
- DeepL API
- Google Translate API
- Microsoft Translator

### Storage & Media
- AWS S3
- CloudFlare R2
- Unsplash API (images)

### Email
- SendGrid
- Mailgun
- AWS SES

### Payment
- Stripe
- PayPal

## Infrastructure

### Containerization
- Docker
- Docker Compose

### Orchestration
- Kubernetes
- Helm charts

### CI/CD
- GitHub Actions
- GitLab CI
- Jenkins

### Cloud Providers
- AWS (primary)
  - EC2, ECS, EKS
  - RDS, DynamoDB
  - S3, CloudFront
  - Lambda
- GCP (alternative)
- Azure (alternative)

### Monitoring & Logging
- Prometheus
- Grafana
- ELK Stack (Elasticsearch, Logstash, Kibana)
- Sentry (error tracking)
- DataDog (APM)

### CDN
- CloudFlare
- AWS CloudFront
- Fastly

## Development Tools

### Version Control
- Git
- GitHub / GitLab

### API Testing
- Postman
- Insomnia
- Thunder Client (VS Code)

### Documentation
- Swagger / OpenAPI
- Stoplight
- Docusaurus

### Code Quality
- ESLint
- Prettier
- SonarQube
- Husky (git hooks)

## Security Tools

- Helmet.js (HTTP headers)
- CORS
- Rate limiting (express-rate-limit)
- SQL injection prevention (parameterized queries)
- XSS prevention
- CSRF tokens
- SSL/TLS certificates

## Development Environment

- VS Code
- Node Version Manager (nvm)
- Docker Desktop
- Postman
- DBeaver (database client)
