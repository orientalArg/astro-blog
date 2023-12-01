## 🇦🇷 **My First Astro Project**
Astro Blog

> Take a look at the [Production Demo](https://journeyblog.vercel.app/blog)

## 💾 Initial Config:

```
> Minimal starter kit
> Typescript base
```


## 🚀 Project Structure

Inside my Astro project, you'll see the following folders and files:


```
/
├── public/
│    └── images/
│    └── stack/
├── data/
│    └── navData.js
│    └── siteData.js
├── js/
│    └── nav.js
│    └── jsonLD.js
│    └── utils.js
├── src/
│    └─ components/
│         └── nav.astro
│         └── aside.astro
│         └── categoryCloud.astro
│         └── postHeader.astro
│         └── postBody.astro
│         └── postShare.astro
│         └── pagination.astro
│         └── footer.astro
|────── layouts/
│         └── MainLayout.astro
│         └── CardLayout.astro
│         └── PostLayout.astro
|────── pages/
│         └── index.astro
│         └── about.astro
│         └── contact.astro
│         └── 404.astro
│         └── blog.astro
|────── styles/
│         └── global.scss
└── package.json
```


## 🧞 How i make this project
> Characteristics of this project 

| Characteristic            | Description                                      |
| :------------------------ | :----------------------------------------------- |
| `styles`                  | All styles are written in `scss` syntax whitin the `astro` files except the `global` styles file. > npm install sass |
| `routing`                 | Astro includes it's own `routing` api based on folder structure |
| `SEO`                     | All `SEO` and `OG:` structure is based on [Coding In Public](https://www.youtube.com/@CodinginPublic/) scripts. He is one of many Astro project's "embassador", I highly recommend to follow him |


## 🤓 Want to learn more?

Look at the official [Documentation](https://docs.astro.build) 

Get into the [Discord Server](https://astro.build/chat), people are very active there.

Follow Astro build on [Twitter](https://twitter.com/astrodotbuild) to be aware of the news.

## For blog administration look at the [Tina + Astro](https://tina.io/docs/frameworks/astro/) documentation

Tina is a very easy to set up `Headless CMS` wich is usually use as admin panel for `Markdown` files, if you know a little bit about JS OOP it'll be very easy to taloring.
