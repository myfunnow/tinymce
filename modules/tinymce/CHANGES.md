# Changes by FunNow Inc.

## 2026-04-21
- `package.json`: renamed package to `@myfunnow/tinymce`, updated repository URL to `https://github.com/myfunnow/tinymce`
- `Gruntfile.js`: use `packageData.name` and `packageData.repository` in zip `package.json` instead of hardcoded values; propagate `publishConfig` if present; add `component-dir` task that unzips `_component.zip` into a directory of the same name
- `package.json`: add `publishConfig` to publish to GitHub Packages (`https://npm.pkg.github.com`)
