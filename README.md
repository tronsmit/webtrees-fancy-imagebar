Fancy Imagebar for webtrees (WSL Dev)
=====================================
This branch is optimized for development in a WSL/Linux environment.

**Key Changes:**
- **.gitattributes:** Enforces LF (Unix) line endings to prevent build errors.
- **package.json:** Explicitly includes `cross-env` and `sass` dependencies.
- **Scripts:** Disables Windows-specific `.bat` scripts (e.g., translation generation) to allow the build chain to complete on Linux.

**Usage:**
Run `npm install` followed by `npm run watch` to start development.
