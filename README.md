## Creating a static website using Hugo

### To edit
1. `cd` to where it should be; `git pull`.
2. Edit locally. To add new contents, `hugo new content content/<...>`.
3. `hugo server [--BuildDrafts]` to preview. See [here](https://gohugo.io/getting-started/usage/).
4. `hugo` to deploy.
5. Finally, `git commit -a -m <Message>` and `git push`. Then github will deploy the website, which can be checked from the tab "Actions".
