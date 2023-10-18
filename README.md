<div align="center">
  <div style="margin-bottom: 24px">
    <img src="https://www.kelisto.es/images/kelisto-logo.svg" width="180">
  </div>
  <div style="margin-bottom: 24px;">
    <a style="margin-right: 8px;" href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /></a>
    <a href="https://conventionalcommits.org"><img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" /></a>
  </div>
</div>

---

## ✨ Features

- [n8n](https://n8n.io/) (pronounced n-eight-n) helps you to connect any app with an API with any other, and manipulate its data with little or no code.
- Customizable: highly flexible workflows and the option to build custom nodes.
- Privacy-focused: self-host n8n for maximum privacy and security.
- Examples of workflows: https://n8n.io/workflows.
- Forked from [n8n-heroku button](https://github.com/n8n-io/n8n-heroku/tree/main).

## 🚀 Deploy

Use the **Deploy to Heroku** button above to launch n8n on Heroku. When deploying, make sure to check all configuration options and adjust them to your needs. It's especially important to set `N8N_ENCRYPTION_KEY` to a random secure value. 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kelkoo-services/kelisto-n8n-heroku)

Refer to the [Heroku n8n tutorial](https://docs.n8n.io/hosting/server-setups/heroku/) for more information.

If you have questions after trying the tutorials, check out the [forums](https://community.n8n.io/).

## ❓ FAQ

<details>
  <summary>How to update to the latest version?</summary>

```bash
## Installing Heroku CLI
$ npm i -g heroku
$ heroku login

## Deploying a new version
$ git clone https://github.com/kelkoo-services/kelisto-n8n-heroku
$ cd kelisto-n8n-heroku
$ heroku git:remote -a kelisto-n8n
$ git commit --allow-empty -m "release: deploying new version"
$ git push heroku main
```
</details>
