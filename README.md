This Readme is currently just tools used in development.

If you don't know what you're doing consider using webstorm (they give coppies of their pro IDE to people with .edu email addresses!)

Here is a guide to using webstorm with react apps: https://www.jetbrains.com/help/webstorm/react.html#react_transfer_html_attributes_to_jsx

Webstorm allows you to authenticate github for clone / push / pull. Some opperations will need to be run through the terminal (either inside or outside webstorm) which will require setting up a personal access token with Github. Instructions can be found online. You then use whatever you want as a username and the personal access tokken as the password.

Deploy to github pages guide used: https://github.com/gitname/react-gh-pages

From here on out we should just need to delete the gh-pages branch and redeploy it. This will work: `git push origin --delete gh-pages; npm run deploy -- -m "Deploy React app to GitHub Pages"` Consider setting git to cache your credentials: `git config --global credential.helper cache`
