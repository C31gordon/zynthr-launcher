# ZYNTHR Operating Environment

**Pentagon Briefing — Corry Station · July 28, 2026**

A Vision Pro-style kiosk launcher. Every ZYNTHR capability launches from a radial wheel. No slides. No architecture diagrams. You've entered the system.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Radial wheel launcher (8 wedges) |
| `deployment.html` | Deployment Model + Economics |
| `vision.html` | Black screen closing statement |
| `evidence.html` | Evidence capability preview |
| `integrations.html` | Integrations capability preview |
| `governance.html` | Governance capability preview |
| `analytics.html` | Analytics capability preview |

## Wheel Navigation

| Key | Destination |
|-----|-------------|
| `1` | COMMAND → Today's Brief |
| `2` | INSTALLATIONS → Attention View |
| `3` | OPERATIONS → FORTE |
| `4` | DEPLOYMENT → Scale & Investment |
| `5` or `V` | VISION → Closing statement |

`Escape` or `Backspace` returns to the wheel from any interior page.

## Wedge Map

```
           COMMAND (1)
    DEPLOYMENT      INSTALLATIONS (2)
  ANALYTICS           OPERATIONS (3)
    GOVERNANCE      EVIDENCE
           INTEGRATIONS
```

Clockwise from top: COMMAND · INSTALLATIONS · OPERATIONS · EVIDENCE · INTEGRATIONS · GOVERNANCE · ANALYTICS · DEPLOYMENT

## External links

- COMMAND → https://zynthr-todays-brief.vercel.app
- INSTALLATIONS → https://installation-attention-view.vercel.app
- OPERATIONS → https://baas-maintenance.vercel.app

## Design System

R13 visual language: near-black (`#050507`), teal accent (`#14b8a6`), monospace labels, no percentages, no marketing language.

## Kiosk Setup

Set browser to full-screen (F11) on 1920×1080 or 2560×1600. The wheel auto-scales to `min(84vw, 84vh)`. Bring Verizon hotspot; `vision.html` works fully offline.
