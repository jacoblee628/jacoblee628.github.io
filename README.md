# info
customized github.io theme based on [Minimal Mistakes](mmistakes.github.io/minimal-mistakes/), which is built on [Jekyll](https://jekyllrb.com/). Free hosting on github at `https://[your_username].github.io`, just by having your repo uploaded

# install
- first, download or fork this repo, and make your own repo in your own github acc named after your url ([your_username].github.io)
- Then follow [these instructions](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/); they should work for both mac & windows 
- You may need to update jekyll/gem
- You can test your website locally without having to commit to github each time by running the script i made (`start_local.sh`). In console, `cd` to the local repo folder, then type `./start_local.sh`, then go to `http://127.0.0.1:4000//` in your browser.
- To see the live page, after creating your repo, just navigate to `https://[your_username].github.io`

# how to customize
- First, go over `_config.yml` line by line and change everything to your info
    - social media links and most of the sidebar info will be in this file
- Each page is a `.md` (markdown) file, but you can use `.html` if you want.
    - `index.md` is in root directory, every other page is in its own folder
- To edit the navigation bar on top, edit `_navigation.yml`.
- If you want to change font/styles, you can either edit your current `.md` file, the page layout in `_layouts/`,  or the `.scss` files in `_sass/minimal-mistakes/`
    - Sometimes nailing down which setting to change is a pain
- to add images, put the image file in `assets/images/` folder, and reference the relative file URL like I have
- When you google things, check either "minimal mistakes" or "jekyll"; some problems are related to the theme (minimal mistakes), and some are related to the engine (jekyll).

# useful links
- https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
    - guide on how to run things, customize pages, tells you a bit about how jekyll works