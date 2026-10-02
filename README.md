# Richmond Goh — portfolio

A static, dependency-free portfolio for GitHub Pages. The site is plain HTML and CSS; there is no build step, tracking, or external font service.

## Preview locally

From this directory, run `python3 -m http.server 8080` and open <http://127.0.0.1:8080>.

## Publish

1. Create a public GitHub repository named `richmondgoh8.github.io` under the `richmondgoh8` account.
2. Push these files to its `main` branch.
3. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Check <https://richmondgoh8.github.io/> after GitHub finishes publishing.

The portfolio intentionally links to verified public repositories rather than claiming a live demo where one is not confirmed. Add a public email or professional social link to the **Elsewhere** section when you have chosen one to share.

## Update content

Project descriptions and links are in `index.html`. Visual styles are in `styles.css`. Keep claims specific and verifiable, and replace projects as stronger work becomes public.
