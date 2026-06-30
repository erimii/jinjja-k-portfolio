# JinJJa-K Project Portfolio

K-drama scene learning product portfolio covering the flow from MVP2 kduck to kduck-home and the JinJJa-K Android shell.

## Live

- Portfolio: https://erimii.github.io/jinjja-k-portfolio/
- PDF: [JinJJa-K-Portfolio.pdf](./JinJJa-K-Portfolio.pdf)

## What This Covers

- MVP2 kduck: scene learning loop, Scene Decoder, acting flow, media/permission constraints
- kduck-home: production web service boundary, vertical feed, My Room, analytics/admin/push surfaces
- kduck_react: Android WebView shell, native Google Sign-In, notification permission, release QA

## Key Contributions

- Designed the product flow from scene watching to decoding, acting, saving, and returning.
- Split the experimental MVP surface into a production web service with clearer runtime boundaries.
- Connected the web app to an Android shell without duplicating the web UI in native code.
- Verified release-sensitive details including OAuth clients, signing SHA-1 values, permissions, and device QA.

## Files

```text
.
├── README.md
├── index.html
├── JinJJa-K-Portfolio.pdf
├── images/
└── .gitignore
```

## Stack

React, TypeScript, Vite, Cloudflare Pages, D1, R2, HLS, React Native, WebView, Google OAuth, Firebase Messaging.
