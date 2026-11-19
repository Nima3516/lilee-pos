# Lilee POS

A simple point-of-sale for Lilee clothing shop. It is a single web page (`index.html`) with no server or build step.

## Features
- Sell items by size, with discounts, cash or card payment and change calculation
- A numbered bill after every sale, with print and reprint
- Stock reduces automatically on each sale
- Receive stock, edit prices and counts, add and delete products, low-stock alerts and a stock movement log
- Owner PIN: cashiers can only sell and reprint today's bills. Stock, voids and settings are owner-only
- White and brown theme

## Run it
Open `index.html` in a browser, or publish it with GitHub Pages (steps below).

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `lilee-pos`.
2. Upload `index.html`, `.nojekyll` and `README.md` to the repository.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then save.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/lilee-pos/`.

## Important notes
- Data (products, stock, bills) is saved in the browser of the device in use. Each device has its own data, and clearing the browser's site data erases it.
- The owner PIN keeps ordinary staff out of the owner screens, but it is not strong security. A shared database and real logins would need a backend.
- If the repository is public, anyone can open the page and use the POS, but they cannot see your shop's data because it stays in your own browser.
