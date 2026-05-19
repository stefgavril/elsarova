# ElsaRova – Website

Static presentation website for [elsarova.ro](https://elsarova.ro), hosted on Cloudflare Pages.

## Structure

```
elsarova/
├── main/         → elsarova.ro          (lighting & electrical)
│   ├── index.html
│   └── style.css
└── tractari/     → tractari.elsarova.ro (towing services)
    ├── index.html
    └── style.css
```

## Cloudflare Pages Setup

Two separate CF Pages projects, both from this repo:

| Project | Root directory | Domain |
|---------|---------------|--------|
| `elsarova-main` | `main` | `elsarova.ro` |
| `elsarova-tractari` | `tractari` | `tractari.elsarova.ro` |

## Deployment

Push to `main` branch — Cloudflare Pages deploys automatically.

## Photos

Replace placeholder sections in `tractari/index.html` with real images of equipment/interventions.
