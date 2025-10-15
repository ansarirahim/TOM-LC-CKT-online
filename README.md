# TOM‑LC CKT — Online Simulation (GitHub Pages)

This package lets you publish a simple landing page where Tom can copy the web‑safe ngspice netlist and run it directly in the browser via **ngspice‑js**.

## Files
- `index.html` — landing UI (copy netlist, open runner, download `.cir`).
- `TOM_LC_websafe_min.cir` — minimal, browser‑friendly SPICE deck.
- `LICENSE` — MIT.

## How to publish on GitHub Pages
1. Create a new repo on GitHub, e.g. `TOM-LC-CKT-online`.
2. Upload **index.html** and **TOM_LC_websafe_min.cir** to the repository root (branch: `main`).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Set **Branch = main** and **Folder = /** (root). Click **Save**.
6. After the site builds, your public link will be:

   ```
   https://<your-username>.github.io/TOM-LC-CKT-online/
   ```

7. Share that link with Tom. On the page, he clicks **Open ngspice‑js**, pastes the netlist, and runs.

## Notes
- If a corporate firewall blocks external JS, use another browser/network.
- For a direct, self‑contained run-in-browser experience, you can also fork `ngspice-js` and host it under your pages, but the above method is usually enough.
