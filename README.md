# pa11y-crawl-docker

A Docker image for [pa11y-crawl](https://github.com/18f/pa11y-crawl)

## Using this image

Pull the image:

```
docker pull 18fgsa/pa11y-crawl-docker:latest
```

Assuming your host has a web server running at `http://localhost:3000`:

```
docker run -t --net="host" 18fgsa/pa11y-crawl-docker:latest pa11y-crawl http://localhost:3000
```

## Public domain

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.
