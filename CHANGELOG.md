# Changelog (AYDO-Linux fork)

Versions are `<upstream major>.<AYDO minor>.<patch>`: 86.1.0 is upstream Vitals v86.0.1 plus the
changes below. Upstream's own history is in its release notes on GitHub.

## 86.1.0

- Based on upstream Vitals v86.0.1.
- Storage: "Used %" is a numeric percentage and can be colored; "Free" is colored by the same
  used percentage, since free space shrinks as the disk fills. New setting `storage-colors`.
- Packaged for `aydo-ext`. The packed `metadata.json` version (860100) stays above the
  extensions.gnome.org version numbers, so GNOME doesn't replace this build with upstream's.
