# news-image-20261119

Sum up 19 November's world news in one image — make.fun bounty entry.

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/rennxddhitz-source/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/rennxddhitz-source/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

## About

This program writes a single PNG image summarizing the world's news of Thursday 19 November 2026 to `/output/entry.png`. It is an entry for the make.fun bounty "Sum up 19 November's world news in one image" (`news-image-20261119`).

## How it works

`main.py` renders the news summary as a PNG image using only the Python standard library (`struct`, `zlib`, `os`), with no network access. It writes the result to `/output/entry.png`. The image names the day and lists the day's most consequential stories across regions and fields.

## Run

```bash
mkdir -p /output
python3 main.py
```

## License

MIT License. See LICENSE.

## Repository

https://github.com/rennxddhitz-source/news-image-20261119
