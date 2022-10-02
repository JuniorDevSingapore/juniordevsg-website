# JuniorDev.SG Website

This site is build with [Hugo](https://gohugo.io).

## Getting Started

1. Clone this git repository

2. Please follow the instructions on Hugo's website on how to install the Hugo CLI on your computer: [https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)

	On MacOS:

    ```bash
    brew install hugo
    ```
   
	On Windows WSL2:

    ```bash
   sudo apt update 
   sudo apt upgrade
   sudo apt install hugo
    ```

4. Initialize the Git submodule

    ```bash    
   git submodule update --init --remote
    ```

5. To preview the site:

    ```bash
    hugo serve
    ```

    Open your browser to: [http://localhost:1313](http://localhost:1313)

6. To generate the new site:

    ```bash
    hugo
    ```

    This will generate the static contents for the site in `docs` directory. Make a new commit and push to master.


6. Add the flag `--forceSyncStatic` for generating non-content static files

	```bash
	hugo --forceSyncStatic
	```

## Add a New Post
1. Add your new post as `title.md` to the `content` -> `posts` folder.
2. Copy the following format for `title.md`
```markdown
---
title: "Title of your new post"
date: YYYY-MM-HHTMM:SS:48+08:00 
slug: "title-post"
---

Enter your content here

```
