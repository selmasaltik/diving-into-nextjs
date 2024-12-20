# FullStack React Apps with NextJS
***Building Up On React***

- What Is [NextJS](https://nextjs.org/) & Why Would You Use It?
- Routing, Pages & Server Components
- Fetching & Sending Data
- Styling, Image Upload & Managing Page Metadata

[Filesystem-based Routing](https://www.canva.com/design/DAGWA5wy80o/t1uyFushbFDuS9YAx12oWA/view?utm_content=DAGWA5wy80o&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[NextJS Works With React Server Components](https://www.canva.com/design/DAGWA50u2Lk/Yx-7IRKhvbEX1IYpQHbyGw/view?utm_content=DAGWA50u2Lk&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[Filenames Matter!](https://www.canva.com/design/DAGWBKcUa8Y/zuMyFtfeQ8dtY4L02G2wzw/view?utm_content=DAGWBKcUa8Y&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[NextJS Renders Pages On The Server](https://www.canva.com/design/DAGWBGBNK6s/jn9-_tYzJAS3lcmwzdKDcg/view?utm_content=DAGWBGBNK6s&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[Server-side & Client-side Working Together](https://www.canva.com/design/DAGWBaMERxQ/-swjilwkU7vVryvDLpekiw/view?utm_content=DAGWBaMERxQ&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[Pages & Layouts](https://www.canva.com/design/DAGWBT-lc2M/TJSJAlKNfPUpvMs-KpZ0Zw/view?utm_content=DAGWBT-lc2M&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[Getting Started: Project Structure](https://nextjs.org/docs/app/getting-started/project-structure#colocation)

**Reserved Filenames**

As you already learned, there are some reserved filenames when working with NextJS.

Important: These filenames are only reserved when creating them inside of the `app/` folder (or any subfolder). Outside of the `app/` folder, these filenames are not treated in any special way.

Here's a list of reserved filenames in NextJS - you'll, of course, learn about the important ones throughout this section:

- `page.js` => Create a new page (e.g., `app/about/page.js` creates a `<your-domain>/about` page)
- `layout.js` => Create a new layout that wraps sibling and nested pages
- `not-found.js` => Fallback page for "Not Found" errors (thrown by sibling or nested pages or layouts)
- `error.js` => Fallback page for other errors (thrown by sibling pages or nested pages or layouts)
- `loading.js` => Fallback page which is shown whilst sibling or nested pages (or layouts) are fetching data
- `route.js` => Allows you to create an API route (i.e., a page which does NOT return JSX code but instead data, e.g., in the JSON format)

You also find a list with all supported filenames & detailed explanations in the official docs: https://nextjs.org/docs/app/api-reference/file-conventions
