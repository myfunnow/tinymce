# Changes by FunNow Inc.

## 2026-04-21
- `package.json`: renamed package to `@myfunnow/tinymce`, updated repository URL to `https://github.com/myfunnow/tinymce`
- `Gruntfile.js`: use `packageData.name` and `packageData.repository` in zip `package.json` instead of hardcoded values; propagate `publishConfig` if present
- `package.json`: add `publishConfig` to publish to GitHub Packages (`https://npm.pkg.github.com`)
