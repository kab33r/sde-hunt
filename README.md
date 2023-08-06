# Sensitive Data Discovery (SDE Hunting)

This automation script is designed for security researchers and bug bounty hunters. It identifies subdomains with `403 Forbidden` and `401 Unauthorized` status codes and then performs content discovery on them using various wordlists from the SecLists repository.

## Usage

```bash
./sde_hunting.sh <subdomains_file>
```

## Prerequisites

Before running the script, ensure you have the required tools installed:
Also, download the [SecLists repository](https://github.com/danielmiessler/SecLists) for wordlists.

## Permissions and Execution

After cloning or downloading the script, navigate to its directory and set the appropriate permissions:

\```bash
chmod +x sde_hunting.sh
\```

Now, you can run the script as mentioned in the usage section.

## Credits

Special thanks to the developers of the tools used in this script:

- [httpx](https://github.com/projectdiscovery/httpx)
- [ffuf](https://github.com/ffuf/ffuf)
- [SecLists](https://github.com/danielmiessler/SecLists)

## Contribution

Feel free to raise issues, suggest improvements, or submit pull requests. Every contribution is appreciated!
