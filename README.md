# CGO 2020
International Symposium on Code Generation and Optimization 2020

# setting up website locally

Clone the git repository (change GIT_REPO_NAME): `git clone GIT_REPO_NAME`

Make sure to have the ruby header files installed on your system, then:

`gem install bundler`

`bundle install`

To build the website: `bundle exec jekyll build`

Then test it locally using a local webserver (this will make sure the website gets rebuilt automatically when any file changes):

`bundle exec jekyll serve --incremental`

To continuously update the local copy of the website while changing it use the command:

`bundle exec jekyll serve --watch`

To see the local version go to the following URL:

http://localhost:4000/

