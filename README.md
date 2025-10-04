# 5-Day Node.js Learning Plan (Beginner)

A comprehensive beginner's guide to learning Node.js in 5 days, designed to be followed alongside the **Learn With Sumit** Bangla playlist.

## 📋 Prerequisites

You should have basic knowledge of:
- JavaScript (ES6+)
- Callbacks, Promises, Async/Await

If you're not familiar with these concepts, spend some time reviewing them before starting this plan.

---

## 📅 Day 1: Introduction, Setup, and Core Concepts

### Goals
- Understand what Node.js is, its uses, and how it works (event loop, non-blocking I/O)
- Install Node.js and set up your development environment
- Write a simple "Hello World" HTTP server

### What to Do

**Watch Sumit's Videos:**
- [Node.js নিয়ে একটি ছোট্ট গল্প (Introduction)](https://www.youtube.com/playlist?list=PLHiZ4m8vCp9PHnOIT7gd30PCBoYCpGoQM)
- [Node.js কি & কিভাবে কাজ করে?](https://m.youtube.com/watch?v=qImH1bFubW4)
- [Node.js Server & Core Modules](https://m.youtube.com/watch?v=6Yv3YXgPBJU)

**Practice:**
- Install Node.js (latest LTS version)
- Create a simple script that prints "Hello from Node" using `node` command
- Build a basic HTTP server using the `http` module that responds with "Hello Node"

**Read:**
- [Node.js Official Documentation - Introduction](https://nodejs.org/en/docs/)
- MDN / NodeSchool tutorials on basic HTTP servers

---

## 📅 Day 2: Modules, Globals, File System, and Events

### Goals
- Understand the module system (CommonJS, export/import)
- Learn about global objects in Node.js
- Work with the File System (fs) module
- Explore event emitters

### What to Do

**Watch Sumit's Videos:**
- [Node.js Global Object & Module System](https://www.youtube.com/watch?v=IFBeIUX3J8M)
- File System and Event Emitter videos from his series

**Practice:**
- Create a `calculator.js` module, export functions, and require/import them in another file
- Use `fs.readFileSync`, `fs.readFile`, and `fs.writeFile` to read and write files
- Create a simple EventEmitter: build your own emitter and trigger custom events

**Read:**
- [Node.js Docs - File System](https://nodejs.org/api/fs.html)
- [Node.js Docs - Events](https://nodejs.org/api/events.html)
- Tutorials on module loading and require cache behavior

---

## 📅 Day 3: Streams, Buffers, and Networking

### Goals
- Understand buffers and streams
- Learn about readable/writable streams and piping
- Work with network modules (e.g., `net`)
- Practice error handling and asynchronous patterns

### What to Do

**Watch Sumit's Videos:**
- [Node.js Stream & Buffer](https://m.youtube.com/watch?v=BPdRVquo5pg)

**Practice:**
- Read a large file using `createReadStream` and write to another file using `createWriteStream` with piping
- Build a small TCP server with the `net` module (optional challenge)
- Experiment with buffer manipulation: conversions, slicing, etc.

**Read:**
- [Node.js Docs - Streams](https://nodejs.org/api/stream.html)
- [Node.js Docs - Buffer](https://nodejs.org/api/buffer.html)
- Tutorials on piping, duplex, and transform streams

---

## 📅 Day 4: Asynchronous Patterns

### Goals
- Master asynchronous code: callbacks, promises, and async/await
- Understand how to avoid "callback hell"
- Use utilities like `util.promisify`

### What to Do

**Watch:**
- Sumit's async topics (if available in his series)
- Supplementary Bangla/English videos on JavaScript asynchronous patterns

**Practice:**
- Write a function that wraps `fs.readFile` in a Promise
- Chain multiple asynchronous operations using both promise style and async/await style
- Implement error handling with `try/catch` in async functions

**Read:**
- [MDN - Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [MDN - Async/Await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await)
- [Node.js Docs - util.promisify](https://nodejs.org/api/util.html#util_util_promisify_original)

---

## 📅 Day 5: Build a Small Project + Explore Express

### Goals
- Consolidate your learning by building a small REST API or file upload server
- Get introduced to Express.js and middleware

### What to Do

**Watch Sumit's Videos:**
- [Express.js Tutorial Bangla Series](https://www.youtube.com/playlist?list=PLHiZ4m8vCp9PHnOIT7gd30PCBoYCpGoQM) - Watch the initial Express videos

**Build:**
- A RESTful API with endpoints like `/users` (GET, POST)
- Use `fs` or a simple JSON file as your "database" initially
- Add basic error handling and validation

**Review:**
- Revisit earlier topics where you felt uncertain
- Try to explain to yourself (or someone else) how Node's event loop works, how streaming works, etc.

---

## 📚 Extra Resources & References

- **[Learn With Sumit GitHub](https://github.com/learnwithsumit)** - Code and projects from his Node.js videos
- **[Node.js Official Documentation](https://nodejs.org/en/docs/)** - Especially: Modules, Streams, Events, API
- **[MDN Web Docs](https://developer.mozilla.org/)** - For JavaScript async/Promise/async-await
- **The Node.js Handbook** - Free online guide
- **[NodeSchool](https://nodeschool.io/)** - Interactive exercises
- **YouTube** - Additional Bangla tutorials for any gaps
- **Technical Blogs** - Articles explaining Node internals (event loop, libuv)

---

## 🎯 Next Steps

After completing this 5-day plan, you should have a solid foundation in Node.js. Consider:
- Building more complex projects
- Learning about databases (MongoDB, PostgreSQL)
- Exploring authentication and security
- Diving into testing (Jest, Mocha)
- Learning about deployment and DevOps

---

## 💡 Tips for Success

- **Practice daily** - Consistency is key
- **Build projects** - Apply what you learn immediately
- **Read documentation** - Get comfortable with official docs
- **Ask questions** - Join Node.js communities
- **Debug actively** - Learn to read error messages

---

Good luck with your Node.js journey! 🚀
