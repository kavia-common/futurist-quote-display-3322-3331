# Environment Variables

The app makes use of several environment variables for configuration. These must be defined in a `.env` file at the root of `jarvis_quote_frontend/` or set in your system environment before running.

| Variable Name                    | Description                                                                              |
| -------------------------------- | ---------------------------------------------------------------------------------------- |
| REACT_APP_API_BASE               | Base API endpoint for fetching quotes or other resources.                                |
| REACT_APP_BACKEND_URL            | URL of the backend service (if distinct from API base).                                  |
| REACT_APP_FRONTEND_URL           | Publicly accessible URL of the frontend application.                                     |
| REACT_APP_WS_URL                 | WebSocket URL, if real-time features are supported.                                      |
| REACT_APP_NODE_ENV               | Node environment (`development`, `production`, etc).                                     |
| REACT_APP_NEXT_TELEMETRY_DISABLED| Disables Next.js telemetry (if relevant; set to `1` to disable).                         |
| REACT_APP_ENABLE_SOURCE_MAPS     | Whether to enable generation of source maps.                                             |
| REACT_APP_PORT                   | Port number the frontend runs on (default: 3000).                                       |
| REACT_APP_TRUST_PROXY            | Trust proxy settings (mainly relevant in proxied deployments).                           |
| REACT_APP_LOG_LEVEL              | Logging verbosity for the frontend.                                                      |
| REACT_APP_HEALTHCHECK_PATH       | Endpoint path for health checks.                                                         |
| REACT_APP_FEATURE_FLAGS          | JSON or comma-separated list of enabled feature flags.                                   |
| REACT_APP_EXPERIMENTS_ENABLED    | Toggle for enabling experiments or beta features (`true` or `false`).                    |

> Define only those environment variables needed for your configuration. All variables must be prefixed with `REACT_APP_` to be available in the React app runtime.

---

**Sample `.env` File:**

```env
REACT_APP_API_BASE=https://api.example.com
REACT_APP_PORT=3000
REACT_APP_NODE_ENV=development
```

**Important:** Do not commit `.env` files or secrets to version control.

Task completed: Environment variable guide documented.
