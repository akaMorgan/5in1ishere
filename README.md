# Event Five in One

Interactive event website for **Youth Leading Youth**. It includes the event agenda, sponsor section, a five-track score challenge, and a leaderboard.

## Run locally

Open `index.html` in a browser, or run the included Node server and visit `http://localhost:3000`.

## Publish on GitHub Pages

1. Create an empty GitHub repository.
2. Open this project folder in VS Code.
3. Use **Source Control** to initialize Git, commit the files, and choose **Publish Branch**.
4. In the GitHub repository, open **Settings → Pages** and choose **GitHub Actions** as the deployment source.

Every push to the `main` branch publishes the site automatically.

## Leaderboard

The interface stores the current score in the browser. To share scores between all participants, connect the Google Sheet through a Google Apps Script web app endpoint.
