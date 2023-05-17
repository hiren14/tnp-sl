<div align="center">
  <h1>Notiolink</h1>
  <p>⚡ Self-hostable branded link shortener built with Next.js & Notion API</p>
  <p>Made by <a href="https://hirenlalani.netlify.app/">Hiren Lalani</a></p>
</div>



If you are migrating from v0 to v1, I suggest to re-fork the project and add the environment variables.

## Features

- ⚡ Unlimited branded links (use your own domain!)
- ☝ Self-hostable with Vercel
- 💨 Fast redirect using Next.js Middleware Functions
- 🌑 Awesome CMS using Notion
- ➕ See click count statistics
- 💠 Zero config, all customizable via env
- 💅 Numerous themes

### Link Tree Page

You can easily configure it on the notion database

![Link Tree](https://user-images.githubusercontent.com/55318172/150363654-f70477ae-fef6-4cf0-87d6-6bc9285a7f49.png)

### Add New Link

Route: `/new`

You can add link straight from the website for easy access, don't worry **this is protected with login page** so no one will mess with your links

![New Link](https://user-images.githubusercontent.com/55318172/152929343-279e175e-d63b-4c1e-81be-1823746d0f49.png)

### Link Details & Count

You can see the statistics with `/:slug/detail` route

![Link Details](https://user-images.githubusercontent.com/55318172/150364397-a867dba4-c2a6-4d18-b930-724074c6c654.png)

### Categorized Tree

Every category will be made into a standalone tree on `/c/:category` route

![Category](https://user-images.githubusercontent.com/55318172/152929498-2e44d6a3-5d49-4fbd-9ed3-b2e22aeffbd2.png)

