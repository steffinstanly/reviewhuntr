FROM circleci/ruby

RUN curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
RUN sudo apt-get update && sudo apt-get install nodejs jpegoptim imagemagick
RUN sudo npm install -g gulp
RUN sudo gem install jekyll bundler jsonlint html-proofer

