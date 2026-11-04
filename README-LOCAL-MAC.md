# Run Ophthalmicmart locally on macOS

This project copy is prepared for local macOS development.

## Start the storefront

1. Open this folder in VS Code.
2. In VS Code, choose **Terminal → New Terminal**.
3. Confirm the terminal is in this folder, then run:

   ```sh
   pnpm install --no-frozen-lockfile
   PORT=5173 BASE_PATH=/ pnpm --filter @workspace/ophthalmicmart-store run dev
   ```

4. Open `http://localhost:5173` in your browser.

Keep the terminal running while you use the site. Press `Control+C` in the
terminal to stop the local server.

The storefront source is in `artifacts/ophthalmicmart-store/`.
