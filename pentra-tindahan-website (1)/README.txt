PENTRA TINDAHAN WEBSITE

Put it online (the same way you deploy the Pentra app)
1. Open app.netlify.com and create a new site by dragging this folder (or this zip) onto the deploy area.
2. Netlify gives you an address such as https://something.netlify.app.
   You can rename it in the site's settings, for example to pentra-tindahan.
3. Send that address to store owners on Messenger or Facebook.

Change your details
Open index.html in a text editor and search for CONFIG (near the bottom):
- appUrl     where "Start your free trial" goes (now https://demotindahan.netlify.app/)
- email      shown as "Email us for a demo" (now pentrascans@gmail.com); set to '' to hide
- messenger  your page link, e.g. https://m.me/yourpage; empty = hidden
- phone      your number, e.g. +639171234567; empty = hidden
- trialDays  free trial days, used everywhere on the page (now 30)
- price      pesos per store per month, used everywhere on the page (now 149)

Share preview on Messenger and Facebook
Once the site is online, replace content="og-image.png" in index.html with the full address,
for example https://pentra-tindahan.netlify.app/og-image.png, then upload the folder again.
