<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->
<img src=".\images\2025-01-09 172238.png" style="zoom:75%;" />

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

2025.01.09 13:35 Add Image
2025.01.09 13:39 Change ".\images\2025-01-09 172238.png"
2025.01.09 14:08 Edit by VS Code
2025.02.03 09:42 github는 .md 를 사용한다.
chooyk.github.io
- 소스코드는 로컬에 내려받은 후 (C:\GitHub\chooyk.github.io) 편집한다.
   . 소소코드 수정은 VSCode(Visual Studio Code, 소스 편집툴)를 사용(특별히 정해진것은 아님)
   . 소스를 수정하고 저장하면 VSCcode화면 좌측에 커밋이 체크된다. 커밋용 메세지를 넣고 커밋을 클릭한다.
   . github Desktop를 실행하면 상단 메뉴에 push orign 이 표시된다. 클릭하면 fetch가 된다.
   . 새로고침 하면 적용된 것을 볼 수 있다 (chooyk.github.io)
   


<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
