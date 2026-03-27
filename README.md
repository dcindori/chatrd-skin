# chatrd-skin

Custom skin for [ChatRD](https://github.com/VortisRD/chatrd) — a multi-platform stream chat overlay.

## Usage

Add the skin URL as the `chatrdSkin` parameter:

```
https://vortisrd.github.io/chatrd/chat.html?chatrdSkin=https://dcindori.github.io/chatrd-skin/skin-stream.css
```

## CSS Variables

Adjust these in `:root` inside `skin-stream.css`:

| Variable | Default | Description |
|---|---|---|
| `--chatrd-bg-opacity` | `0.55` | Message bubble transparency (0-1) |
| `--chatrd-info-width` | `160px` | Username column width |
| `--chatrd-bubble-radius` | `8px` | Bubble corner rounding |
| `--chatrd-bubble-color` | `14, 14, 18` | Bubble background RGB |
| `--chatrd-event-color` | `16, 16, 22` | Event background RGB |
| `--chatrd-mention-bg-opacity` | `0.5` | Mention bubble opacity |
| `--chatrd-mention-border` | `#f59e0b` | Mention accent color |
