# Cascade Chat Conversation

  Note: _This is purely the output of the chat conversation and does not contain any raw data, codebase snippets, etc. used to generate the output._

### User Input

Walk me through the architecture of this repo

### Planner Response

I'll scan the repository to map its structure and identify key components. I'll list the root directory and search for common config and entry-point files (README, requirements, package configs, Docker files, tests, and main app files) in parallel to quickly build an architectural overview.

*Listed directory [Resume-Matcher](file:///Users/hren/Downloads/Resume-Matcher) *

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

*Searched filesystem*

### Planner Response

I'll open and scan the key files and directories in parallel to map the repo’s architecture: root READMEs, Makefile, backend structure and entry point, backend dependencies, frontend setup, and any docs. This will let me summarize components, tech stack, and how they interact.

*Listed directory [apps](file:///Users/hren/Downloads/Resume-Matcher/apps) *

*Listed directory [backend](file:///Users/hren/Downloads/Resume-Matcher/apps/backend) *

*Listed directory [frontend](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend) *

*Viewed [README.md](file:///Users/hren/Downloads/Resume-Matcher/README.md) *

*Viewed [Makefile](file:///Users/hren/Downloads/Resume-Matcher/Makefile) *

*Viewed [main.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/main.py) *

*Viewed [requirements.txt](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/requirements.txt) *

*Viewed [pyproject.toml](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/pyproject.toml) *

*Viewed [package.json](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/package.json) *

*Viewed [README.md](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/README.md) *

*Viewed [package.json](file:///Users/hren/Downloads/Resume-Matcher/package.json) *

*Listed directory [docs](file:///Users/hren/Downloads/Resume-Matcher/docs) *

*Listed directory [app](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app) *

### Planner Response

To provide an accurate architecture walk-through, I'll inspect the backend's [base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0) (app creation), enumerate key subpackages ([api/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api:0:0-0:0), [core/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core:0:0-0:0), [services/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services:0:0-0:0), [models/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models:0:0-0:0), [schemas/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas:0:0-0:0), [agent/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent:0:0-0:0), [prompt/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt:0:0-0:0)) to understand layering and routes, review configuration files ([.env.sample](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/.env.sample:0:0-0:0), [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0)), and list frontend [app/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0) and [components/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components:0:0-0:0) to see the UI structure. I'll run these lookups in parallel for speed.

*Viewed [base.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py) *

*Listed directory [api](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api) *

*Listed directory [core](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core) *

*Listed directory [services](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services) *

*Listed directory [models](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models) *

*Listed directory [schemas](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas) *

*Listed directory [agent](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent) *

*Listed directory [prompt](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt) *

### Planner Response

I'll open the backend's [base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0) and enumerate key subpackages to understand routes and layers, and I'll read the configuration doc to infer environment variables. This will let me describe the architecture accurately.

*Viewed [base.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py) *

### Planner Response

I'll inspect backend configuration, database, routers, and middleware, plus the docs and key frontend folders, to accurately describe components and their interactions. Running these lookups in parallel for speed.

*Viewed [config.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py) *

### Planner Response

I'll open backend router and middleware modules, database and exception helpers, services and agent providers to understand layers and integrations. I'll also read the configuration doc and inspect key frontend folders ([app/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0), [components/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components:0:0-0:0), [hooks/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/hooks:0:0-0:0), [lib/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/lib:0:0-0:0)) to summarize the UI structure and routes.

*Viewed [__init__.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/__init__.py) *

### Planner Response

I’ll inspect backend routers and database setup to map API surface and persistence, check agent providers/strategies to understand LLM integrations, read configuration docs for env variables, and scan frontend directories to outline the UI architecture. Running these lookups in parallel.

*Listed directory [router](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router) *

*Viewed [database.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py) *

*Viewed [CONFIGURING.md](file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md) *

*Listed directory [providers](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers) *

*Listed directory [strategies](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/strategies) *

*Listed directory [app](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/app) *

*Listed directory [components](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components) *

*Listed directory [lib](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/lib) *

*Listed directory [hooks](file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/hooks) *

### Planner Response

# High-level overview

- **Monorepo layout**: [apps/backend](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend:0:0-0:0) (FastAPI API) + [apps/frontend](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend:0:0-0:0) (Next.js UI) orchestrated from root via npm scripts and a Makefile.
- **Tech stack**:
  - Backend: FastAPI, SQLAlchemy (sync/async), Pydantic Settings, Uvicorn, SQLite by default.
  - Frontend: Next.js 15, React 19, Tailwind v4, TypeScript.
  - AI: Pluggable LLM/embedding providers (Ollama default, OpenAI, or any LlamaIndex provider).
- **Dev workflow**: `npm run dev` runs both servers concurrently. Backend Python env managed by `uv`.

Paths to see:
- [README.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/README.md:0:0-0:0), [SETUP.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/SETUP.md:0:0-0:0), [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0)
- [apps/backend/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend:0:0-0:0)
- [apps/frontend/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend:0:0-0:0)
- [package.json](cci:7://file:///Users/hren/Downloads/Resume-Matcher/package.json:0:0-0:0), [Makefile](cci:7://file:///Users/hren/Downloads/Resume-Matcher/Makefile:0:0-0:0)

# Backend architecture ([apps/backend/app/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0))

- **Entry point**
  - [app/main.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/main.py:0:0-0:0) starts Uvicorn and imports [create_app()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:29:0-68:14) from [app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0).

- **App factory**
  - [app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0) exports [create_app()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:29:0-68:14) which configures:
    - Middleware: `SessionMiddleware`, `CORSMiddleware`, `RequestIDMiddleware` from [app/api/middleware.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/middleware.py:0:0-0:0).
    - Exception handlers: `custom_http_exception_handler`, `validation_exception_handler`, `unhandled_exception_handler` from [app/core/exceptions.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/exceptions.py:0:0-0:0).
    - Lifespan: creates tables on startup and disposes the async engine on shutdown using `async_engine` from [app/core/database.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:0:0-0:0).
    - Static mount: mounts frontend static build at [/app](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0) if `settings.FRONTEND_PATH` exists.
    - Routers: `health_check` and `v1_router` (versioned API).

- **Configuration & logging**
  - [app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0)
    - Settings via Pydantic `BaseSettings`, reading `.env` at `apps/backend/.env`.
    - Key variables: `SESSION_SECRET_KEY`, `SYNC_DATABASE_URL`, `ASYNC_DATABASE_URL`, `ALLOWED_ORIGINS`, `LLM_PROVIDER`, `LL_MODEL`, `EMBEDDING_PROVIDER`, `EMBEDDING_MODEL`, etc.
    - [setup_logging()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:43:0-71:58) sets console logging and noise suppression for SQLAlchemy/Uvicorn.
  - See [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0) for detailed `.env` guidance and provider options.

- **Database**
  - [app/core/database.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:0:0-0:0)
    - Creates both sync and async SQLAlchemy engines and session factories.
    - SQLite-specific PRAGMAs (WAL, FK) applied if using SQLite.
    - Dependency providers: [get_db_session()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:119:0-126:17) (async), [get_sync_db_session()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:101:0-116:18).
    - [init_models()](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:129:0-131:53) for programmatic model initialization.
  - ORM base and models in [app/models/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models:0:0-0:0)
    - [base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0), [association.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models/association.py:0:0-0:0), [job.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models/job.py:0:0-0:0), [resume.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models/resume.py:0:0-0:0), [user.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models/user.py:0:0-0:0), [__init__.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/__init__.py:0:0-0:0).

- **API layer**
  - [app/api/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api:0:0-0:0)
    - [router/health.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/health.py:0:0-0:0): health endpoints.
    - [router/v1/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/v1:0:0-0:0): versioned API routers (e.g., endpoints for jobs, resumes, scoring).
    - [middleware.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/middleware.py:0:0-0:0): `RequestIDMiddleware`.
    - [__init__.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/__init__.py:0:0-0:0): re-exports `health_check`, `v1_router`, `RequestIDMiddleware`.

- **Schemas**
  - [app/schemas/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas:0:0-0:0)
    - [pydantic/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas/pydantic:0:0-0:0): request/response models for API.
    - [json/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas/json:0:0-0:0): example payloads or JSON schema artifacts.

- **Services (business logic)**
  - [app/services/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services:0:0-0:0)
    - [job_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/job_service.py:0:0-0:0): operations around job descriptions (ingestion, normalization, structuring).
    - [resume_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/resume_service.py:0:0-0:0): resume ingestion/parsing, structured extraction, embedding.
    - [score_improvement_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/score_improvement_service.py:0:0-0:0): match scoring and improvement suggestions.
    - [exceptions.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/exceptions.py:0:0-0:0), [__init__.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/__init__.py:0:0-0:0).

- **AI agent & prompts**
  - [app/agent/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent:0:0-0:0)
    - [providers/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers:0:0-0:0): adapters for LLMs/embeddings
      - [ollama.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/ollama.py:0:0-0:0) (local inference), [openai.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/openai.py:0:0-0:0) (OpenAI API), [llama_index.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/llama_index.py:0:0-0:0) (LlamaIndex provider bridge), [base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0).
    - [strategies/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/strategies:0:0-0:0): orchestration and selection logic ([base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0), [wrapper.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/strategies/wrapper.py:0:0-0:0)).
    - [manager.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/manager.py:0:0-0:0): ties providers/strategies to services.
  - [app/prompt/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt:0:0-0:0)
    - Prompt templates: [structured_job.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt/structured_job.py:0:0-0:0), [structured_resume.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt/structured_resume.py:0:0-0:0), [resume_improvement.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt/resume_improvement.py:0:0-0:0), [base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0).

# Frontend architecture ([apps/frontend/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend:0:0-0:0))

- **Framework & tooling**
  - Next.js 15 with the App Router, React 19, Tailwind v4, TypeScript.
  - Scripts: `npm run dev` (Turbopack), `build`, `start`, `lint`, `format` in [apps/frontend/package.json](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/package.json:0:0-0:0).

- **Structure**
  - [app/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0):
    - `(default)/`: main route group pages.
    - [layout.tsx](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/app/layout.tsx:0:0-0:0): root layout.
  - [components/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components:0:0-0:0):
    - [ui/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/ui:0:0-0:0): base UI primitives.
    - [common/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/common:0:0-0:0): shared components.
    - [dashboard/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/dashboard:0:0-0:0): dashboard views/widgets.
    - [jd-upload/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/jd-upload:0:0-0:0): job description upload components.
    - [home/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/home:0:0-0:0): homepage components.
  - [hooks/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/hooks:0:0-0:0)
    - [use-file-upload.ts](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/hooks/use-file-upload.ts:0:0-0:0): file selection/drag-drop and client-side preprocessing.
  - [lib/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/lib:0:0-0:0)
    - [api/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api:0:0-0:0): API client wrappers to the backend.
    - [utils.ts](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/lib/utils.ts:0:0-0:0): shared helpers.
  - [next.config.ts](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/next.config.ts:0:0-0:0), [tailwind.config.js](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/tailwind.config.js:0:0-0:0), [tsconfig.json](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/tsconfig.json:0:0-0:0).

- **Backend integration**
  - `NEXT_PUBLIC_API_URL` (in `apps/frontend/.env`) points to the backend base URL.
  - Calls into backend [v1](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/v1:0:0-0:0) endpoints for health, resume/job ingestion, scoring.

# Runtime flow

- **User action**
  - User opens the Next.js UI, uploads a resume and a job description ([components/jd-upload](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components/jd-upload:0:0-0:0), [hooks/use-file-upload.ts](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/hooks/use-file-upload.ts:0:0-0:0)).
- **API calls**
  - Frontend posts to backend (`/api/v1/...`) using `lib/api/*`.
- **Backend processing**
  - Request hits FastAPI `v1_router` → validated by `schemas/pydantic/*`.
  - `services/*` orchestrate parsing, structuring (using `prompt/*`), LLM completion, and embeddings via `agent/*`.
  - Persistence via SQLAlchemy models to the DB configured in `.env`.
- **Response**
  - Returns match score, extracted keywords, and improvement suggestions.
  - Frontend renders dashboard components accordingly.

# Configuration and environments

- **Backend `.env`** (see [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0))
  - `SESSION_SECRET_KEY`, `SYNC_DATABASE_URL`, `ASYNC_DATABASE_URL`, `ALLOWED_ORIGINS`.
  - LLM/embedding provider knobs: `LLM_PROVIDER`, `LL_MODEL`, `LLM_API_KEY`, `LLM_BASE_URL`, `EMBEDDING_PROVIDER`, `EMBEDDING_MODEL`, `EMBEDDING_API_KEY`, `EMBEDDING_BASE_URL`.
  - Defaults favor local Ollama; can switch to OpenAI or any LlamaIndex provider by FQN class name.
- **Frontend `.env`**
  - `NEXT_PUBLIC_API_URL` to point the UI to the backend (important behind reverse proxies).

# Dev, build, and ops

- **Root scripts** ([package.json](cci:7://file:///Users/hren/Downloads/Resume-Matcher/package.json:0:0-0:0))
  - `install`: `install:frontend` + `install:backend` (Python via `uv pip install .`).
  - `dev`: concurrent backend (Uvicorn) and frontend (Next.js).
  - `build`: builds frontend, then runs a placeholder backend build.
  - `start`: concurrent prod start of backend + frontend.
- **Makefile**
  - Friendly wrappers: `make setup`, `make run-dev`, `make build-prod`, `make start-prod`.
- **Static serving option**
  - [app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0) will mount static assets at [/app](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app:0:0-0:0) if `settings.FRONTEND_PATH` exists. In practice, Next.js is often served via its own server or a reverse proxy; this mount is an optional convenience.

# Where to add or change things

- **New API endpoint**: add a router in [apps/backend/app/api/router/v1/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/v1:0:0-0:0), define models in [apps/backend/app/schemas/pydantic/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/schemas/pydantic:0:0-0:0), business logic in [apps/backend/app/services/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services:0:0-0:0).
- **New data model**: add SQLAlchemy model in [apps/backend/app/models/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/models:0:0-0:0) and Pydantic schemas; tables auto-create on startup in dev via [lifespan](cci:1://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:21:0-26:32).
- **Change providers/models**: adjust `.env` per [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0); provider code in [apps/backend/app/agent/providers/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers:0:0-0:0).
- **Frontend feature/view**: add page in `apps/frontend/app/(default)/`, UI in [apps/frontend/components/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/components:0:0-0:0), API calls in [apps/frontend/lib/api/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/lib/api:0:0-0:0).

# Recommended next steps

- **[targets]** If you want, I can open `apps/backend/app/api/router/v1/*` to enumerate the exact endpoints and payload shapes.
- **[envs]** I can also draft sample `.env` files for both backend and frontend tailored to your setup (Ollama vs OpenAI).

Summary: Mapped repo architecture across backend (FastAPI + SQLAlchemy + pluggable LLM/embeddings), frontend (Next.js + Tailwind), configuration, and dev workflow, with file-level pointers to extend endpoints, models, providers, and UI.

### User Input

What is the main use case of this app? What are similar projects? How does this project different from others?

### Planner Response

# Findings

- **Main use case**
  - **Tailor resumes to specific job descriptions to pass ATS screening and improve human review odds.**
  - Core capabilities:
    - **ATS compatibility analysis and match scoring** (see [apps/backend/app/services/score_improvement_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/score_improvement_service.py:0:0-0:0)).
    - **Keyword extraction and gap detection** (see [apps/backend/app/services/job_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/job_service.py:0:0-0:0) and [apps/backend/app/services/resume_service.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/services/resume_service.py:0:0-0:0)).
    - **Actionable, guided improvement suggestions** driven by LLM prompts (see [apps/backend/app/prompt/resume_improvement.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/prompt/resume_improvement.py:0:0-0:0)).
    - Runs **locally** with **Ollama** by default; can switch to **OpenAI** or any **LlamaIndex provider** (see `apps/backend/app/agent/providers/*`, [apps/backend/app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0), and [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0)).
  - This aligns with the README’s value proposition: “Stop getting auto-rejected by ATS bots,” “ATS Compatibility,” “Instant Match Score,” “Keyword Optimizer,” “Guided Improvements” ([README.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/README.md:0:0-0:0) lines 56–61).

- **Similar projects (non-exhaustive)**
  - **SaaS ATS scanners/optimizers**: Jobscan, ResyMatch (by Jobscan), SkillSyncer, Rezi, Teal, VMock.
  - **Open-source resume tooling**: OpenResume (builder), various resume parsers (e.g., spaCy-based or pdfminer.six-based parsers).
  - These serve similar goals (scoring, keyword matching, optimization) but are often closed-source/SaaS or focused on building rather than analyzing/tailoring.

# How this project differs

- **Local-first, privacy-friendly**:
  - Default provider is **Ollama** for on-device inference; no data leaves your machine unless you choose a remote provider ([docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0), [apps/backend/app/agent/providers/ollama.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/ollama.py:0:0-0:0), [README.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/README.md:0:0-0:0) lines 56–61).
- **Pluggable AI provider architecture**:
  - Swap between `ollama`, `openai`, or any `llama_index`-backed provider via env vars without code changes (`apps/backend/app/agent/providers/*.py`, [apps/backend/app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0)).
- **Transparent prompts and services**:
  - Prompt logic lives in code (`apps/backend/app/prompt/*`) and business logic in services (`apps/backend/app/services/*`)—easy to audit and extend.
- **Modern, open stack**:
  - FastAPI + SQLAlchemy + Pydantic on the backend ([apps/backend/app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0), `apps/backend/app/core/*`, `apps/backend/app/models/*`).
  - Next.js 15 + React 19 + Tailwind v4 on the frontend ([apps/frontend/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend:0:0-0:0)), with clear component structure (`apps/frontend/components/*`).
- **Monorepo with cohesive DX**:
  - Single set of scripts to run both apps ([package.json](cci:7://file:///Users/hren/Downloads/Resume-Matcher/package.json:0:0-0:0) at repo root; [Makefile](cci:7://file:///Users/hren/Downloads/Resume-Matcher/Makefile:0:0-0:0)), optional static mount from backend ([apps/backend/app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0)).

# Pointers in the codebase

- **Backend entry and wiring**: [apps/backend/app/main.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/main.py:0:0-0:0), [apps/backend/app/base.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/base.py:0:0-0:0)
- **Config and envs**: [apps/backend/app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0), [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0)
- **DB and models**: [apps/backend/app/core/database.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/database.py:0:0-0:0), `apps/backend/app/models/*`
- **API surfacing**: [apps/backend/app/api/router/v1/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/v1:0:0-0:0), [apps/backend/app/api/router/health.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/health.py:0:0-0:0)
- **LLM providers/strategies**: `apps/backend/app/agent/providers/*`, `apps/backend/app/agent/strategies/*`, [apps/backend/app/agent/manager.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/manager.py:0:0-0:0)
- **Prompts**: `apps/backend/app/prompt/*`
- **Frontend**: [apps/frontend/app/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/frontend/app:0:0-0:0), `apps/frontend/components/*`, `apps/frontend/lib/api/*`

# Recommended actions

- **[compare]** Want me to list the exact [v1](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/api/router/v1:0:0-0:0) endpoints and payloads from `apps/backend/app/api/router/v1/*` for a capabilities matrix?
- **[configure]** I can draft `.env` samples for local Ollama vs OpenAI vs hybrid setups.

Summary: The app’s main use case is local, AI-assisted resume tailoring for ATS and hiring outcomes. It’s similar to Jobscan/SkillSyncer-style scanners but differs by being open-source, local-first, and pluggable across LLM providers with transparent prompts and services.

### User Input

Does this repo uses LangGraph or any other agentic framework? Or does it rely on LLM?

### Planner Response

I'll search the codebase for references to LangGraph, LangChain, or other agent frameworks to confirm whether any are used, and also inspect the custom [agent/](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent:0:0-0:0) provider implementation to see how LLMs are integrated.

*Grep searched codebase*

### Planner Response

I'll open the LlamaIndex provider and the agent manager to confirm if any agent frameworks are used and how LLMs are integrated.

*Viewed [llama_index.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/llama_index.py) *

### Planner Response

I'll open the agent manager and Ollama/OpenAI provider implementations to confirm whether any agent frameworks are used and how LLMs are integrated.

*Viewed [manager.py](file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/manager.py) *

### Planner Response

# Findings

- **No LangGraph/LangChain/etc. detected**
  - Searched for common agent frameworks; only references found were to LlamaIndex base interfaces and docs mentions.
  - Evidence:
    - `grep`: no `langgraph`, `langchain`, `crewai`, `autogen`, `semantic_kernel`, `haystack` hits.
    - LlamaIndex is used only as a provider interface: [apps/backend/app/agent/providers/llama_index.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/llama_index.py:0:0-0:0).

- **Pluggable, provider-based LLM usage**
  - Providers implemented:
    - [apps/backend/app/agent/providers/ollama.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/ollama.py:0:0-0:0) (local Ollama)
    - [apps/backend/app/agent/providers/openai.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/openai.py:0:0-0:0) (OpenAI API)
    - [apps/backend/app/agent/providers/llama_index.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/llama_index.py:0:0-0:0) (any LlamaIndex LLM/Embedding class via FQN)
  - Provider selection and strategy:
    - [apps/backend/app/agent/manager.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/manager.py:0:0-0:0) chooses provider by `LLM_PROVIDER` and wraps prompts via `JSONWrapper`/`MDWrapper` from [apps/backend/app/agent/strategies/wrapper.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/strategies/wrapper.py:0:0-0:0).
    - This is a lightweight orchestration, not a graph/agent framework.

- **Configuration-driven**
  - Env variables pick the backend model/provider: `LLM_PROVIDER`, `LL_MODEL`, `EMBEDDING_PROVIDER`, `EMBEDDING_MODEL`, etc. in [apps/backend/app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0).
  - Detailed in [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0) with examples for Ollama, OpenAI, and LlamaIndex providers.

# Interpretation

- **It relies on LLMs and embeddings via a simple custom “agent” layer**, not on LangGraph or similar frameworks.
- “Agent” here means a minimal wrapper that:
  - Selects a provider (`OpenAI`, `Ollama`, or a `llama_index` class).
  - Applies an output-formatting strategy (`JSONWrapper`/`MDWrapper`).
  - Executes a single completion or embedding call (no multi-step planning/tools/graphs).

# Pointers

- **Provider routing**: [apps/backend/app/agent/manager.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/manager.py:0:0-0:0)
- **LlamaIndex adapter**: [apps/backend/app/agent/providers/llama_index.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/agent/providers/llama_index.py:0:0-0:0)
- **Config keys**: [apps/backend/app/core/config.py](cci:7://file:///Users/hren/Downloads/Resume-Matcher/apps/backend/app/core/config.py:0:0-0:0)
- **Docs**: [docs/CONFIGURING.md](cci:7://file:///Users/hren/Downloads/Resume-Matcher/docs/CONFIGURING.md:0:0-0:0)

# Summary

- **Does it use LangGraph or another agentic framework?** No.
- **Does it rely on LLMs?** Yes. It uses LLMs/embeddings via pluggable providers (Ollama/OpenAI/LlamaIndex), orchestrated by a small in-repo manager and strategy wrappers.