<h1 align="center">URAI Blog website</h1>

This repository contains the source code of the Blog website of URAI along
with the blogs themselves.

If you want to contribute blogs, you need to add your blog in this repository
by making a contribution.


Code changes in this repository:

### 👉 Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### 👉 Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### 👉 Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

### 👉 Social Links

You can change the social links from the `data/social.json` file. Add your social links here, and they will automatically be displayed on the site.

---

## 🛠 Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### 👉 Update Theme

If you want to update the theme, then you can use the following command. It will update the theme to the latest version.

```bash
npm run update-theme
```

> **Note:** This command will work after running the `project-setup` script.

### 👉 Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### 👉 Remove Dark Mode

If you want to remove dark mode from your project, you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

> **Note:** This command will work before running the `project-setup` script. If you have already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. Afterward, you can run `npm run project-setup` again.

### 👉 Remove Multilingual

If you want to remove multilingual from your project, you can use the following command to remove multilingual from your project.

```bash
npm run remove-multilang
```

> **Note:** This command will work before running the `project-setup` script. If you have already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. Afterward, you can run `npm run project-setup` again.

---

## 🚀 Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere. Let's see the process:

### 👉 Build Command

To build your project locally, you can use the following command.

```bash
npm run build
```

### 👉 Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to host some other hosting platforms. Then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

---

## 🔒 Guide to Staying Compliant

### 🐞 Reporting Issues

We use GitHub Issues as the official bug tracker for this Template. Please search [existing issues](https://github.com/zeon-studio/hugoplate/issues). Someone may have already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new issue](https://github.com/zeon-studio/hugoplate/issues).

### 📝 License

Copyright (c) 2023 - Present, Designed & Developed by [Zeon Studio](https://zeon.studio/)

**Code License:** Released under the [MIT](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their license, we don't have permission to share those images.

---

## 🌠 Showcase

List of some projects people are building with [**Hugoplate**!](https://github.com/zeon-studio/hugoplate/discussions/207)
Don't forget to add yours.

---

## 💻 Need Customization?

If you need a custom theme, theme customization, or complete website development services from scratch, you can [Hire Us](https://zeon.studio/estimate-project).
