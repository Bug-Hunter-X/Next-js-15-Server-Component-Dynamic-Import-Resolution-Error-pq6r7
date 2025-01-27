This repository demonstrates a bug in Next.js 15 related to dynamic imports within server components used in API routes. The bug causes runtime errors when the import path depends on runtime data unavailable during the build process.  The `bug.js` file showcases the problematic code. The solution, provided in `bugSolution.js`, involves refactoring to avoid runtime-dependent import paths.