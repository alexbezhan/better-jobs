# Goals:
- Single dependency - SQLite.
- Embedded in the app - easy to create jobs, don't need an API. Create jobs within main thread. Then pull jobs in the worker thread.
- Support queues.
- Assume there will be multiple Node instances each with its own Job worker.
- Persist.
- Admin UI that can be embedded into existing express-like server.
