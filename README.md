
# Voicemail Page (SpeakPipe Inline Widget)

This folder contains a ready-to-publish `voicemail.html` you can drop into your GitHub Pages website.

## How to Use (GitHub Desktop)

1. Open your wedding website repository in **GitHub Desktop**.
2. Drag **`voicemail.html`** into the root of your repo (or a `pages/` folder if you prefer).
3. Commit the change and **Push origin**.
4. Your page will be available at:
   - `https://<your-username>.github.io/<your-repo>/voicemail.html`

### Link it from your homepage

Add a button somewhere on your homepage:

```html
<a class="btn" href="./voicemail.html">🎙️ Leave a Voicemail</a>
```

*(If your site uses a different button style, keep the `href` and replace the classes.)*

### Troubleshooting
- If the recorder doesn't show the mic prompt, the browser may have blocked it. Ask guests to allow microphone access and refresh.
- If your site uses a strict Content Security Policy, ensure `https://www.speakpipe.com` is allowed for `frame-src` and `script-src`.

### Customizing
- To change the header text or styling, edit the `<h1>` and CSS in `voicemail.html`.
- To adjust the recorder height, tweak the `height` attribute on the `<iframe>`.
