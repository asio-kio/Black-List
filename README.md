# Black-List

A curated personal domain blocklist designed for filtering unwanted websites, trackers, and specific content categories. This repository contains plain-text domain rules in an AdGuard-style format and is intended for personal or self-hosted filtering setups.

## Overview

Black-List is a lightweight repository of domain-based filtering rules for use with tools such as AdGuard Home, uBlock Origin, and other DNS or network filtering solutions that support AdGuard-style syntax. The project is structured to keep blocklists easy to review, customize, and deploy.

## Repository contents

This repository currently includes the following rule files:

- `black` — main blacklist containing domains associated with adult content, file-hosting services, social media, and other categories
- `white` — allowlist of trusted or safe domains used to exempt known-good services when supported by your filtering tool
- `FreeFire` — focused list for Free Fire / Garena-related domains

## Rule format

The files use AdGuard-style domain rules such as:

```text
||example.com^
example.com
```

This syntax is commonly supported by:

- AdGuard Home
- AdGuard for Android / iOS
- uBlock Origin custom filters
- DNS or network filtering systems compatible with AdGuard-style rules

## Recommended usage

1. Review each list before enabling it in a live filtering environment.
2. Import the desired file into your AdGuard, DNS, or network filter.
3. Use the `white` file as an exception list when your setup supports allowlisting.
4. Use `FreeFire` only if you specifically want to block or monitor Free Fire-related traffic.
5. Regularly update and review the rules to ensure they match your intended filtering goals.

## Important notes

- This repository is intended for personal and self-hosted use.
- Some entries deliberately block websites, services, or content categories that may not be suitable for all users.
- If you are using this list on a shared network, family network, or production environment, review the rules carefully before deployment.
- The repository is provided for informational and filtering use and should be applied only in compliance with local laws and platform policies.

## Repository structure

```text
Black-List/
├── black
├── white
├── FreeFire
├── README.md
└── LICENSE (if added in the future)
```

## Disclaimer

This project is provided as-is for personal filtering use. Always verify the contents of any blocklist before applying it in a production, shared, or family environment.

## License

This repository does not currently declare a license. Please use it responsibly and only in compliance with applicable laws, policies, and service terms.
