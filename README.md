# My Blog Nuxt

This Nuxt.js application is my personal blog. It allows users to view, filter, and sort blog posts.

## Build Setup

```bash
# Install dependencies
$ npm install

# Serve with hot reload at localhost:3000
$ npm run dev

# Build for production and launch server
$ npm run build
$ npm run start

# Generate static project
$ npm run generate
```

For detailed explanations on how things work in Nuxt.js, please check out the [official documentation](https://nuxtjs.org).

## Project Structure

The project structure consists of several directories:

- `assets`: Contains uncompiled assets like stylesheets, images, and fonts.
- `components`: Houses reusable Vue.js components for various parts of the application.
- `layouts`: Provides layout templates to change the app's look and feel.
- `pages`: Contains application views and routes, automatically set up by Nuxt.
- `plugins`: Contains JavaScript plugins that run before initializing the Vue.js app.
- `static`: Holds static files mapped to the server root, like `robots.txt`.
- `store`: Contains Vuex store files for state management.

## Index Page (pages/index.vue)

This page displays all the blog posts along with their title, author, likes, popularity, reads, and tags.

- Available Tags: Users can filter blog posts by tags.
- Filter and Sort: Users can enter tags separated by commas to filter blog posts. They can also choose the "Sort By" and "Direction" options to sort posts based on different criteria.

## Blog Post Component (components/BlogPost.vue)

This component displays individual blog posts. It receives a `post` prop with data for a specific blog post.

Details shown for each post:

- Title: The blog post's title.
- Author: The author's name.
- Likes: The number of likes the post has received.
- Popularity: The post's popularity score.
- Reads: The number of times the post has been read.
- Tags: The tags associated with the post, displayed as a comma-separated list.

Feel free to customize the project structure and components according to your blog's requirements. Happy blogging!
