# Venue Explorer - A08

Continues A07 with a promotion video and React hooks.

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## A08 features

- `VideoPlayer` uses `useRef` and `useEffect` to play or pause the video.
- `PromoteCard` starts playing `/vdo/venue.mp4` and provides a Pause/Play button.
- `useWindowListener` blocks the context menu on the home page and removes its listener when the component unmounts.
- Venue browsing, ratings, details, and booking pages are carried over from A07.

## Check

```bash
npm test -- --runInBand
npm run lint
npm run build
```

The original assignment tests are in `__tests__/case1.test.tsx` through `case4.test.tsx`.

## Deployment

The A08 Vercel deployment is pending. Add the actual A08 website link here after deployment, then push the updated README to the assignment repository.
