# v1.dinhanhthi.com [![Netlify Status](https://api.netlify.com/api/v1/badges/fa6c0045-fc9e-404d-a1d1-ab2b3c75d4a1/deploy-status)](https://app.netlify.com/sites/stoic-wing-b25942/deploys)

Source code of my personal website (using Jekyll). If you would like to use this source code, please indicate me in the credit and let me know first, thanks! My email: dinhanhthi@gmail.com.

🚀 **Demo**: https://v1.dinhanhthi.com

🔥 **Current version**: https://dinhanhthi.com

<details>
<summary>Some screenshots.</summary>

![Home page](./img/github/front-1.png)

![Home page](./img/github/front-2.png)

![Home page](./img/github/front-3.png)

![Home page](./img/github/front-4.jpg)

![Reading page](./img/github/reading.png)

![Blog page](./img/github/blog.png)

</details>

## How to use quickly?

1. Clone to your github.
2. Create a [Netlify](https://www.netlify.com/) account.
3. Link Netlify to your account.
4. Create a new site and link to the cloned repo.
5. Wait for Netlify to build your site.
6. Voila.

## Build and deploy locally

__Note__: On Windows, you should [use WSL2](https://dinhanhthi.com/docker-wsl2-windows) to run Jekyll site.

After cloning to a local server, run these:

~~~
# install git

# install ruby
ruby --version

# install bundler
gem install bundler

# cd to the repo directory and install gems
bundle install

# run the server (http://localhost:4000)
bundle exec jekyll serve

# incremental build (only build the changes, faster)
bundle exec jekyll serve -I
~~~