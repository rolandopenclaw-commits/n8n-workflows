# n8n Workflows Backup

Auto-exported n8n workflow definitions from the content creation pipeline.

## Workflows (15)

| Workflow | Nodes | Description |
|----------|-------|-------------|
| audio-preview | 10 | TTS audio preview with Google TTS |
| tts-preview | 9 | TTS with validation, duration metadata |
| tts-batch | 11 | Batch TTS for multiple scenes |
| split-shots | 6 | AI-powered shot splitting (Qwen 3.5) |
| storyboard | 7 | Gemini storyboard image generation |
| upscale | 12 | Extract panels → full-frame 16:9 shots |
| kenburns | 5 | Image-to-video Ken Burns effect (ncat) |
| video | 7 | Gemini Veo3 video generation |
| montage | 5 | Video concatenation (ncat) |
| shots-combiner | 7 | Concatenate shots + optional audio merge |
| final-cut | 9 | Concatenate chapters + captions + polling |
| custom-animation | 6 | FFmpeg-based custom animations (ncat) |
| storyboard-with-host | 8 | Storyboard with host imagery |
| tts-shot | 9 | Per-shot TTS with audio metadata |
| nca-modules | 46 | Reference: all ncat API examples |

## Restore

1. Import any `.json` file via n8n UI → Workflows → Import from File
2. Re-configure credentials (IDs are redacted)

## Security

All credential IDs are replaced with `REDACTED`. No secrets are stored.
