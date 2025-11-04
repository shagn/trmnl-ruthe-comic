# trmnl-ruthe-comic

![Screenshot](https://github.com/shagn/trmnl-ruthe-comic/blob/master/screenshot.png?raw=True)

## Description
TRMNL Plugin developed for [BYOS Laravel](https://github.com/usetrmnl/byos_laravel) showing every day a different cartoon from the archive of https://ruthe.de/cartoon/. It does not show the most recent one.

## Development

Use [trmnlp](https://github.com/usetrmnl/trmnlp/) to run the plugin locally. 

```bash
docker run \
    --publish 4567:4567 \
    --volume ".:/plugin" \
    trmnl/trmnlp serve
```
