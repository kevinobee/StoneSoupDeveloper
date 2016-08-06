# Stone Soup Developer Blog

You will need [Node.js](https://docs.npmjs.com/getting-started/installing-node) and [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) as pre-requisites for using Hexo CLI. My blog post on [development machine setup](https://kevinobee.wordpress.com/2016/08/02/rebuilding-my-developer-platform/) shows how easy [Chocolatey](https://chocolatey.org) makes the task of installing application level dependencies today.

## Getting Started

From an __administrative__ level account run the following commands to install everything necessary to get started with [Hexo](https://hexo.io/), the blogging framework that will be used here.

```
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install hexo-browsersync --save
hexo server --draft --open
```


## References

By reading the following blog posts my experience with blogging using Markdown and open source tooling has been greatly enhanced, many thanks to the authors.

* [Getting Started with the Hexo Blogging Framework](https://www.cgmartin.com/2016/01/03/getting-started-with-hexo-blog/)

