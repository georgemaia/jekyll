# Jekyll

Jekyll guide for static pages

## Enviroment

First create your new repository named *username*.github.io, where *username *is your username on GitHub. Second install Ruby on system.

### Linux

Check if ruby in running with

```bash
ruby -v
```

Second install all dependencies:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

### Windows

Install Chocolatey on Administrator mode or Powershell

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Second install ruby:

```bash
cinst ruby
```

## Install Jekyll

Install Jekyll:

```bash
gem install jekyll bundler
```

Create your new site:

```bash
jekyll new myblog
```

where myblog is your *username * or repository name.

Change the bash to your new directory:

```bash
cd myblog
```

Build the site and make it available on a local server:

```bash
bundle exec jekyll serve
```

Now browse to http://localhost:4000

## Install Jekyll Theme

Example link theme in github: [https://github.com/sujaykundu777/devlopr-jekyll](https://github.com/sujaykundu777/devlopr-jekyll)

Edit *_config.yml* and add :

```apacheconf
remote_theme: sujaykundu777/devlopr-jekyll
```

or

```bash
git clone https://github.com/sujaykundu777/devlopr-jekyll.git
cd devlopr-jekyll
bundle install
bundle exec jekyll serve
```

## Inicie o Jekyll

```bash
jekyll serve
```

## References

[GitHub Pages](https://pages.github.com/)

[Working with GitHub Pages](https://help.github.com/en/github/working-with-github-pages)

[Jekyll Quickstart](https://jekyllrb.com/docs/)

[Configurando Jekyll para GitHub Pages em 60 Segundos](https://webdesign.tutsplus.com/pt/tutorials/setting-up-jekyll-for-github-pages-in-60-seconds--cms-27256)

[Jekyll Installation](https://jekyllrb.com/docs/installation/)

[Jekyll Resources](https://jekyllrb.com/resources/)

[Setting up a GitHub Pages site with Jekyll](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)

[Colocando um site no ar com Jekyll: usando o terminal](https://jtemporal.com/do-tema-ao-ar/)

[Jekyll Theme: Developr](http://jekyllthemes.org/themes/devlopr/)

[Build a blog using Devlopr Jekyll](https://devlopr.netlify.com/guides/2019/05/20/build-a-blog-using-devlopr-jekyll/)
