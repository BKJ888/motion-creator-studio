# Motion Creator Studio

A browser-based video composition studio. The interface is in Traditional Chinese.

## Deploy to GitHub + Vercel

1. Create a GitHub repository, e.g. `motion-creator-studio`.
2. Upload `index.html` and `README.md` to the root of the repository.
3. In Vercel, select **Add New → Project → Import Git Repository**.
4. Select the repository; choose **Other** as the Framework Preset (if prompted), leave Build Command empty, and deploy.
5. Visit the generated `*.vercel.app` URL.

No npm installation or environment variables are required.

## Notes

- Videos are selected and processed locally in the browser; this static deployment does not provide cloud media storage or user accounts.
- Exports rely on the browser's `MediaRecorder` and `canvas.captureStream` support. Output may be MP4 or WebM depending on browser.
- Use a recent desktop Chrome or Edge for the best chance of successful export.
- The built-in music is synthesized in the browser; custom audio should be properly licensed.
- Generated videos and edits are not saved as persistent projects after refresh.
