# vscan-broken-link-checker
Identifies broken links within a website or HTML document, reporting on HTTP status codes and locations. - Focused on Lightweight web application vulnerability scanning focused on identifying common misconfigurations and publicly known vulnerabilities

## Install
`git clone https://github.com/ShadowStrikeHQ/vscan-broken-link-checker`

## Usage
`./vscan-broken-link-checker [params]`

## Parameters
- `-h`: Show help message and exit
- `-v`: No description provided
- `-t`: No description provided
- `-o`: No description provided
- `--ignore-ssl`: Ignore SSL certificate verification errors.

## Notes
If the target page itself cannot be fetched, or a named HTML file cannot be read, the tool prints a fetch failure line and exits with status 1. A scan that fetched nothing reports no link verdict. A page that was fetched is checked as before, and its broken link findings and clean outcomes keep their usual shapes.

## License
Copyright (c) ShadowStrikeHQ
