# Gisty Authorization Page

This page displays the verification code needed during GitHub’s Device Authorization Flow used by the **Gisty** Chrome extension.

## About Gisty

Gisty lets users quickly create GitHub Gists from code snippets, saving time and hassle by generating shareable gist links.

## How It Works

- Gisty requests a device code from GitHub.
- This page shows the user the code to enter on GitHub.
- The code expires in 15 minutes.
- After verification, Gisty obtains an access token to create gists.
