Fix for makq24-cloud/Background (not part of TeeSort). Apply in that repo with:
  git am 0001-ios-crash-yellow-keepsolid.patch
then rebuild (cd source && npm ci && npx vite build) and copy dist/index.html + dist/assets to the repo root.
Parked here only because this session cannot push to makq24-cloud.
