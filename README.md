# neriyasoup.github.io

Root GitHub Pages site. Holds a self-hosted copy of the Firebase Auth helper
(`/__/auth/*`) for project `client-manager-97cf2`, so Google sign-in on
https://neriyasoup.github.io/patient-manager/ runs on the same domain as the app
(needed since Chrome partitions third-party storage, which breaks the popup flow
when authDomain is `*.firebaseapp.com`).

Files under `__/auth/` were copied from
`https://client-manager-97cf2.firebaseapp.com/__/auth/{handler,handler.js,experiments.js,iframe,iframe.js}`.
Refresh them occasionally the same way.

`.nojekyll` is required, otherwise GitHub Pages drops the `__` folder.
