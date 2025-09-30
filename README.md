<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

## Finish

_Congratulations friend, you've completed this course!_

<img src=https://octodex.github.com/images/constructocat2.jpg alt=celebrate width=300 align=right>

Your blog is now live and has been deployed!

Here's a recap of all the tasks you've accomplished in your repository:

- You enabled GitHub Pages.
- You selected a theme using the config file.
- You learned about proper directory format and file naming conventions in Jekyll.
- You created your first blog post with Jekyll!

### What's next?

- Keep working on your GitHub Pages site... we love seeing what you come up with!
- We'd love to hear what you thought of this course [in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages).
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

## 使用Docker Compose运行Jekyll

如果你想在本地环境中构建和预览你的Jekyll网站，可以使用Docker Compose来避免直接安装Ruby和Jekyll。

### 前提条件
- 安装[Docker Desktop](https://www.docker.com/products/docker-desktop)

### 运行步骤
1. 确保你在项目根目录下（包含`docker-compose.yml`文件）
2. 打开终端并运行以下命令：

   ```bash
   docker-compose up
   ```

3. 第一次运行时，Docker会下载Ruby镜像并安装所需的依赖。这可能需要一些时间。
4. 安装完成后，Jekyll服务器将在http://localhost:4000启动
5. 打开浏览器访问该地址，即可查看你的网站

### 停止服务
要停止正在运行的服务，可以在终端中按`Ctrl+C`，或者在另一个终端窗口中运行：

```bash
docker-compose down
```

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>