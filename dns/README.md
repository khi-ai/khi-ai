# Khi-AI: DNS Block List for AdGuardHome

Khi-AI provides a DNS block list for AdGuardHome, offering protection against ads, malicious sites, and other unwanted content.

## Overview

This repository includes a comprehensive DNS block list configuration tailored for AdGuardHome, compiled from various reliable sources. Each list has been processed to remove empty lines, comments, and duplicate entries, ensuring optimal performance.

## Source List Configuration

The following sources are included in this block list configuration:

| Name | Source URL |
|------|------------|
| AdGuard DNS filter | [link](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) |
| AdGuard MobileFilter | [link](https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/specific_app.txt) |
| VNM: ABPVN List | [link](https://abpvn.com/android/abpvn.txt) |
| bigdargon - hostsVN | [link](https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/domain.txt) |
| NoCoin Filter List | [link](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt) |
| ZeroDot1 - CoinBlockerLists | [link](https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser) |
| OISD Big List | [link](https://big.oisd.nl) |
| antipopads:re | [link](https://raw.githubusercontent.com/AdroitAdorKhan/antipopads-re/master/formats/domains.txt) |
| HaGeZi's Ultimate Blocklist | [link](https://adguardteam.github.io/HostlistsRegistry/assets/filter_49.txt) |
| 1Hosts Lite | [link](https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/domains.wildcards) |
| Hosts Extras | [link](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) |
| Pop Ads | [link](https://raw.githubusercontent.com/AdroitAdorKhan/antipopads-re/master/formats/domains.txt) |
| Goodbye Ads | [link](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt) |
| AdAway Default Blocklist | [link](https://adaway.org/hosts.txt) |
| Dan Pollock's List | [link](https://someonewhocares.org/hosts/zero/hosts) |
| WindowsSpyBlocker - Hosts spy rules | [link](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt) |
| Scam Blocklist by DurableNapkin | [link](https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/adguard.txt) |
| The Big List of Hacked Malware Web Sites | [link](https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hosts) |
| Online Malicious URL Blocklist (AdGuard Home) | [link](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh.txt) |
| GoodbyeAds-Spotify | [link](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Extension/GoodbyeAds-Spotify-AdBlock.txt) |
| Porn List (NL) | [link](https://blocklistproject.github.io/Lists/alt-version/porn-nl.txt) |

## Transformations

The following transformations are applied to each list to ensure quality and consistency:
- **RemoveComments**: Strips out any comment lines.
- **Compress**: Reduces file size for optimal performance.
- **Validate**: Ensures each entry meets DNS block list requirements.
- **Deduplicate**: Removes duplicate entries.
- **TrimLines**: Cleans up leading and trailing whitespace.
- **InsertFinalNewLine**: Ensures the file ends with a newline.
- **RemoveEmptyLines**: Eliminates any blank lines.

## License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

## Contribution

Contributions are welcome! Please make sure to follow the guidelines in the repository for contributing to ensure all lists remain consistent and effective.

## Contact

For more information, visit the [homepage](https://github.com/khi-ai/khi-ai).
