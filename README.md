<h1 align="center">Destyle 🛠</h1>

<p align="center">
  <img src="https://img.shields.io/tokei/lines/github/sineylo/destyle?color=6CBA41&style=for-the-badge" alt="Lines of code">
  <img src="https://img.shields.io/github/languages/code-size/SineYlo/destyle?color=6CBA41&style=for-the-badge" alt="Code size">
  <img src="https://img.shields.io/github/repo-size/SineYlo/destyle?color=6CBA41&style=for-the-badge" alt="GitHub repo size">
  <img src="https://img.shields.io/github/languages/top/SineYlo/destyle?color=6CBA41&style=for-the-badge" alt="GitHub top language">
  <img src="https://img.shields.io/github/license/SineYlo/destyle?color=6CBA41&style=for-the-badge" alt="GitHub license">
</p>

<p align="center">
  <b>It's more than just resetting and normalizing styles</b>
</p>

<p align="center">
  <a href="https://github.com/nicolas-cusan/destyle.css">The author of the original version is Nicolas Cusan</a>
</p>

<p align="center">
  <a href="https://github.com/SineYlo/destyle/blob/master/README-RU.md">README in Russian</a>
</p>

## 🌠 Why was this version created
Initially, I doubt whether to release my own version of Destyle or not, but then I decided that it would make sense. We live on a planet full of people, and they are all different. Someone wants one thing, and someone else. It's hard enough to please everyone, but I tried to at least get close to it. The original version of Destyle does not give a choice. Only one option. I have three of them. You can use a basic reset by tags. If you don't like it, there is an option to reset through classes. Well, if this option is not suitable, then there are mixins that solve many problems. You have the right to choose the option that you like the lost and is suitable for a particular task.

## ⚙️ Using
```
git clone https://github.com/SineYlo/destyle.git
```
```
git clone git@github.com:SineYlo/destyle.git
```
```
gh repo clone SineYlo/destyle
```
## 🛡 What you need to know before using

If you choose the option using classes or mixins, it is important not to forget to immediately apply classes or mixins to these tags: html (`html-dereset`), body (`margin-dereset`). Also, if you use the `main` tag, it is advisable to apply `main-dereset`.

## 💡 Classes or mixins
Which of these to choose is up to you. It is important to remember one detail. Classes, like regular tags, are transferred with the entire code, and mixins only when they are used. But mixins have a problem compared to classes. They are constantly duplicating the code. While classes call the same one. I.e., there is more code with mixins at the end, most likely, than when using the usual option through tags or through classes.

## 🚀 Testing

| Browser | Version     | Report       |
|---------|-------------|--------------|
| Edge    | 97 – 100    | Successfully |
| Firefox | 96 – 99     | Successfully |
| Chrome  | 97 – 100    | Successfully |
| Opera   | 82 – 85     | Successfully |
| Yandex  | 14.12       | Successfully |
| Safari  | 13.1 - 15.3 | Successfully |

## 🔑 FAQ
```
- Question: Which of the three reset options should I choose?
- Answer: All options are good, but for example I use resetting through classes.
```
```
- Question: Why are there no minified versions for SCSS?
- Answer: Because I'm counting on the fact that you have a project builder, for example, Gulp or Webpack.
```
```
- Question: Will this version be uploaded to NPM?
- Answer: Most likely yes, but I can't say exactly when it will happen.
```
```
- Question: What should I do if I want to add something or have questions?
- Answer: You can write to the issues section or make a pull request.
```

## 🔱 Created with the support of 

<a href="https://www.browserstack.com">
  <img src="temp/Browserstack-logo.svg?sanitize=false" width="200" alt="browserstack">
</a> 

## 📃 What is used in this repository
- Semantic versioning - [semver.org](https://semver.org)
- Conventional commits - [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)
