# docker-wp-cli
Dockerised WP-CLI.

# Usage
Run the wp-cli mapping the current directory:
```
docker run -it --rm -u=www-data -v `pwd`:/source -w /source conversionmedia/wp-cli wp
```
