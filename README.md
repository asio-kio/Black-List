# Black-List

A curated personal domain blocklist for filtering unwanted websites, trackers, and content categories. This repository stores plain-text domain rules in a format commonly used by AdGuard-style filtering setups.

## What is in this repo?

The repository contains a few small blocklist files:

- `black` — a main blacklist containing domains for adult content, file-hosting services, social media, and other categories
- `white` — a whitelist / allowlist of safe or trusted domains
- `FreeFire` — a focused list of Free Fire / Garena related domains

## Example format

The files use AdGuard-style domain rules such as:

```text
||example.com^
example.com
```

This format is compatible with tools such as:

- AdGuard Home
- AdGuard for Android / iOS
- uBlock Origin custom filters
- DNS or network filtering systems that support AdGuard-style rules

## Recommended usage

1. Review each file before enabling it in a live filtering setup.
2. Add the desired file to your AdGuard or DNS filter list.
3. Use `white` as an allowlist/exception list when your setup supports it.
4. Use `FreeFire` only if you specifically want to block or monitor Free Fire-related traffic.

## Notes

- This repository is intended for personal and self-hosted filtering.
- Some entries may intentionally block websites, services, or content categories that are not suitable for all users.
- If you are using this on a shared network, family network, or production environment, review the rules carefully before deploying.

## Repository layout

```text
Black-List/
├── black
├── white
├── FreeFire
└── README.md
```

## Disclaimer

This project is a community-maintained list and is provided as-is for filtering use cases. Always verify the list contents before applying it in a production or shared environment.

## License

This repository does not currently declare a license. Please use it responsibly and only in compliance with local laws and platform policies.
