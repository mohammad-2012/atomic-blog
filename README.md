# 📝 Atomic Blog

🌐 Live Demo
The project is published on GitHub Pages:

👉 https://mohammad-2012.github.io/atomic-blog/

A simple React project that displays hacker-style posts using fake data.

## ✨ Features

- Display a list of posts with titles and content
- Uses `useState` and `useEffect` hooks
- Generates random fake data with `@faker-js/faker`
- Choose how many posts to display
- Simple and responsive design
- Ready to deploy on **GitHub Pages**

## 🧠 Fake Post Generator Function

The following function is used to generate each post:

```js
function createRandomPost() {
  return {
    title: `${faker.hacker.adjective()} ${faker.hacker.noun()}`,
    body: faker.hacker.phrase(),
  };
}
