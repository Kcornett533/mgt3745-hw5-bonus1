
# MGT 3745 HW5 Bonus — Tools Evaluation

## Platform Comparison & Crossing Statement

| Tool / Platform | Category | Evaluation & Usage Context | Crossing Statement |
| :--- | :--- | :--- | :--- |
| **Google Cloud Run** | Serverless Container Hosting | Containerized Express.js execution engine deployed via `gcloud` CLI. | **Crossing Statement:** While Cloudflare Workers / AWS Lambda offer superior cold-start speeds for isolated event handlers, Google Cloud Run is the superior choice for express gateways because it accepts un-refactored Node.js containers directly without requiring specialized edge routing frameworks. |
| **Express.js** | Web Framework | Lightweight HTTP router and JSON response handler (`index.js`). | Provides standardized web server patterns that can migrate between Cloud Run, Docker containers, or traditional VPS deployments with zero code modifications. |
