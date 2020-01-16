# JuniorDev.SG Website

This site is build with [Hugo](https://gohugo.io).

## Getting Started

1. Clone this git repository

2. Please follow the instructions on Hugo's website on how to install the Hugo CLI on your computer: [https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)

	On MacOS:

	```bash
	brew install hugo
	```

3. Initialize the Git submodule

	```bash
	git submodule update --init --remote
	```

4. To preview the site:

	```bash
	hugo serve
	```

	Open your browser to: [http://localhost:1313](http://localhost:1313)

5. To generate the new site:

	```bash
	hugo
	```

	This will generate the static contents for the site in `docs` directory. Make a new commit and push to master.


6. Add the flag `--forceSyncStatic` for generating non-content static files

	```bash
	hugo --forceSyncStatic
	```

