GlitzPop - setup
1. Email API: open index.html, find "const EJS=" and paste your EmailJS service ID, template ID and public key.
2. EmailJS template: set "To Email" = {{to_email}}; use {{to_name}}, {{order_id}}, {{order_items}}, {{order_total}}, {{address}} in the body.
3. Colours: edit only the ":root{ --blush ... }" block at the top of index.html.
4. Host: upload this whole folder (index.html + images/) to Netlify Drop, GitHub Pages or Vercel.
