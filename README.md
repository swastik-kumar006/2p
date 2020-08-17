# 2PG - Glitch Demo
This demo was created on `03/08/2020`.

## Update `config.json`
Add your values

## Update Music Servers
```ts
const nodes = [{
  host: '[yourHerokuAppName].herokuapp.com',
  port: 80,
  password: 'youshallnotpass',
}];
```
If you do not have a heroku music server -> [Setup Heroku Music Server](https://heroku.com/deploy?template=https://github.com/IamTheRealSami/LavalinkOnHeroku/tree/auto).

## Add Redirect URIs
![Redirects](https://i.ibb.co/9pbfVwL/updated-redirects.png)
at [https://discord.com/developers](https://discord.com/developers)

---

## Update 2PG

```bash
shopt -s extglob && set -H && rm -rfv !("config.json")
git init && git remote add origin https://github.com/theADAMJR/2PG && git pull origin stable
```
1) Remove all files, excluding `config.json`
2) Install 2PG

Type these commands in the terminal to update 2PG.
Please note: some setup steps may need to be recompleted to get your bot to work.