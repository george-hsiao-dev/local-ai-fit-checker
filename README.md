# Local AI Fit Checker

An offline-first static MVP that estimates whether a quantized local language model fits GPU, unified, or system memory.

Open `index.html` directly, or serve the folder with any static web server. No account, analytics, network request, or uploaded data is used.

The estimate combines model weights, a configurable KV-cache approximation, and runtime headroom. It is a planning aid rather than a benchmark or compatibility guarantee.

## Custom analysis

Need a model shortlist or a hardware recommendation for a specific workload? [Hire me on Fiverr](https://www.fiverr.com/george_hsiao).

Found a bad estimate or want another input? [Open an issue](https://github.com/george-hsiao-dev/local-ai-fit-checker/issues/new).
