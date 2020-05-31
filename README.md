# My Webpage 
Currently being served at https://rupesh.info/

Cause hosting personal blog and website using github pages is so easy ❤️

- Template Credit : [daattali/beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)
- Design Credit   : [anudit.in](https://github.com/anuditverma/anuditverma.github.io) , [deanattali.com](http://deanattali.com/)



### Running it locally

To run it locally you need to install Jekyll and bundle which you can do from [here](https://jekyllrb.com/docs/installation/)

For Linux machine I can summarize it as

```bash
sudo apt-get update -y && sudo apt-get upgrade -y
sudo apt-add-repository ppa:brightbox/ruby-ng
sudo apt-get update
sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf

ruby -v # to test the installation
gem update # sudo might be needed but try to avoid using sudo
gem install jekyll bundler
jekyll -v   # to test the installation
```



```bash
cd ~/[path to this repo home]
bundle install # add your sudo password if asked for password
bundle exec jekyll serve
```
