# coronainfoapp.net


export JEKYLL_VERSION=3.8                                     
docker run --rm -p 35729:35729 -p 4000:4000\
  --volume="$PWD:/srv/jekyll" \
  --volume="$PWD/vendor/bundle:/usr/local/bundle" \
  -it jekyll/jekyll:$JEKYLL_VERSION \
  jekyll serve --livereload


  https://github.com/vvalchev/creative-theme-jekyll-new