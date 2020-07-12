## Test locally

bundle exec jekyll serve

## Build

bundle exec jekyll build

# Deploy

rsync -arvz  ./_site/ flemingg@vkps.co.uk:/home/flemingg/emphasisparenthesis.co.uk/
