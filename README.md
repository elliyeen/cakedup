# Cake'd Up

Fresh personal cakes made to order. Order tonight, pick up at school tomorrow.

**Live site:** [elliyeen.github.io/cakedup](https://elliyeen.github.io/cakedup)

---

## Menu

| Item | Price |
|---|---|
| 1 Cake | $3 |
| 2 Cakes | $5 |
| 5-Pack | $10 |
| Birthday Pack | $12–$15 |

**Flavors:** Carrot Cake · Berry Explosion · Cookies & Cream · Texas Vanilla Bean

---

## How to Update the Site

All edits are made in `index.html`. After any change, push to GitHub and the live site updates automatically.

```bash
git add index.html
git commit -m "describe your change here"
git push
```

### Things still to add

- [ ] Instagram handle (replace `YOUR_HANDLE` in the contact section)
- [ ] Cash App handle (add to contact section and order confirmation DM)
- [ ] Cake photos — create a `photos/` folder, add images, replace gallery placeholders
- [ ] AT's photo — add to `photos/at.jpg` and update the about section

### Adding cake photos

1. Create a folder called `photos/` next to `index.html`
2. Name your photos `cake1.jpg`, `cake2.jpg`, etc.
3. In `index.html`, find the gallery section and replace placeholder divs with:
```html
<div class="gallery-item"><img src="photos/cake1.jpg" alt="Cake" /></div>
```
4. Push to GitHub

---

## Order System

- **Order form:** Google Form embedded in the site — orders close at 8pm for next-day pickup
- **Payment:** Cash App or cash in person
- **Order tracker:** Google Sheets (run `build_order_sheet.js` in Google Apps Script)

---

## Tech Stack

| Tool | Purpose | Cost |
|---|---|---|
| GitHub Pages | Website hosting | Free |
| Google Forms | Order intake | Free |
| Google Sheets | Order tracking | Free |
| Canva | Brand design | Free |

---

*Cake'd Up by AT — Built with love and a lot of butter*
