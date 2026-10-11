# Dislate Lite (fixed)

Fork of [Dislate Lite](https://github.com/rico040/bunny-plugins/tree/main/plugins/dislate) for Revenge/Bunny with a more reliable translator:

- Google Translate via `translate-pa.googleapis.com` (same endpoint as Vencord's Translate plugin), falling back to the old endpoint
- Retries on rate limits (429) and server errors
- DeepL falls back to Google when the free DeepLX proxy is down
- Error toast shows the actual reason

Install in Revenge: **Plugins → + →** `https://lexa-coder.github.io/dislatefixforme/`

Source changes: `src-patch/dislate-fix.patch` (against rico040/bunny-plugins).
