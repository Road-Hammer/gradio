# Fork workflow policy

`Road-Hammer/gradio` is a fork and does not hold the upstream Gradio project's production publishing credentials.

Upstream-only deployment workflows that publish to Hugging Face buckets/Spaces or upstream documentation infrastructure are intentionally removed from this fork when they create recurring false-red runs. Build/test workflows remain in place so code quality and dependency changes can still be validated.

Removed fork-inapplicable deploy workflows:

- `previews-deploy`
- `docs-deploy`

If this fork later needs its own external deployment targets, restore equivalent workflows with Road-Hammer-owned credentials and destinations rather than upstream secrets.
