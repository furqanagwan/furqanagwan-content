# furqanagwan-content

This repo is the **single source of truth** for all the content and images powering my personal site, [`furqanagwan`](https://github.com/furqanagwan/furqanagwan).

- **Blog posts** are written in MDX and organized in the `content/` folder by category.
- **Images and media** used in posts are stored alongside the relevant articles or in dedicated image folders.

## How it works

- This repo is **not a standalone website**; it’s a content hub used by my main Next.js site.
- Blog content is fetched at build or request time via the GitHub API. No local editing needed!
- Media assets are also referenced directly from this repo—easy version control and instant updates.

## Why this exists

I wanted a clean separation between my site’s code and its content—like a DIY headless CMS, but simpler and cheaper.

If you’re snooping around, feel free to borrow this pattern for your own projects!  
Just don’t hotlink my breakfast recipes. 😉

---

## Contributing

Want to contribute? Love that for you!

- **All changes must be made via Pull Request.**  
  No direct pushes to main, ever.
- Keep content organized and use [MDX](https://mdxjs.com/) for all posts.
- If you’re adding images, please compress them and put them in the appropriate folder.
- By contributing, you agree that your work becomes part of this repo and is licensed as below.
- Be kind, be respectful, and keep it helpful!

PRs are welcome. Please open an issue first if you want to suggest a bigger change.

---

## License

This content is © Furqan Agwan.  
All blog posts, images, and files in this repo are the property of Furqan Agwan unless otherwise noted.

- **You may not reuse, copy, or redistribute this content without permission.**
- Contributors retain rights to their contributions, but by submitting a PR, you agree your content can be published as part of this site.

If you have questions about reusing content or collaborating, please open an issue.

---

**furqanagwan-content** — content for [`furqanagwan`](https://github.com/furqanagwan/furqanagwan), and nothing else.
