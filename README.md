# JolonB.github.io

## Modifying the page

If you want to run this page locally (not sure why you would), you can simply clone this repo, install a bunch of stuff.

```shell
git clone https://github.com/JolonB/JolonB.github.io.git
cd JolonB.github.io
sudo snap install ruby --classic --channel=2.7/stable
bundle install
```

To view the page, run

```shell
bundle exec jekyll serve
```

You should be able to access the page at [localhost:4000](http://localhost:4000). If you make any changes to **.md** files, the page will update automatically (just refresh it). If you change another file, you may need to rerun the command to generate the page again.