<p align="center"><img src="https://may-be.gay/thumbnail.png" width="600px" height="314px" alt="may-be.gay | free subdomains for possibly queer folx" /></p>
<a href="https://gitmoji.dev">
  <img src="https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square" alt="Gitmoji">
</a><br>

<b>may-be.gay</b> is a service in which you can register your own sub-domain for your personal website! Catered to queerfolx, but all inclusive :rainbow_flag:.

# How to Register
1) Fork this repository!
2) Create a new file in the `domains` directory called `<subdomain>.toml`, with the subdomain you would like.
3) Using this template, create your site's file.
```toml
# You need to provide details about yourself that we can use to contact you.
[user]
username = "USERNAME"
# You have to have one of these.
email = "EMAIL"
discord = "DISCORD"

[records]
# Your site's records, i.e.
CNAME = "CNAME here"
```
4) Create a pull request to this repository, one of our owners will merge your website!
