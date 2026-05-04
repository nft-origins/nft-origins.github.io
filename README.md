# NFT Origins

NFT Origins is a research-focused site about early blockchain collectibles and NFT history.

This repository contains the source for the website, including timelines, archived links, and supporting data files covering notable early works, collections, and onchain milestones.

## Website

[Visit nftorigins.com](https://nftorigins.com/)

## Local Development

This site uses Jekyll.

Install dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

Notes:

- The site uses `jekyll-remote-theme`, so the first build may need network access to fetch the remote theme.
- On some macOS setups, you may need to use `/opt/homebrew/opt/ruby/bin/bundle install` and `/opt/homebrew/opt/ruby/bin/bundle exec jekyll serve` instead of `/usr/bin/bundle`.

## Contributing

Issues and pull requests are welcome.

If you spot an error, have a correction, or want to improve the site, feel free to open an issue or submit a PR.

## License

[MIT](LICENSE)
