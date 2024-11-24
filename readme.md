# Hugo Picocss Theme

Create a new project and go to the themes folder.

```bash
hugo new site quickstart && cd quickstart/themes
```

Dead-simple Hugo theme made using [picocss]([url](https://picocss.com/docs)) with everything you need to get started.
## Getting started

Inside your project folder, copy the theme to your `themes` folder. Since you're just using it as a starter for your theme, remove the git history.

```bash
git clone https://github.com/ericmurphyxyz/hugo-picocss-theme/ themes/your-theme-name
rm -rf themes/hugo-picocss-theme/.git
```

If you'd like some example content and an example config file to get started, you can copy the `exampleSite` directory into your root Hugo directory.

```bash
cp -r themes/hugo-picocss-theme/exampleSite/* ./
```

To learn more about this project check out the original creators [video]([url](https://www.youtube.com/@EricMurphyxyz)) 
To learn more about picocss refer to Picocss' [documentation]([url](https://picocss.com/docs))
To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).
