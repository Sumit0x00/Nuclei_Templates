## Requirements

- Nuclei installed on your system.
- Nuclei [nuclei-templates](https://github.com/projectdiscovery/nuclei-templates) should be on your system.
- Wordlists for usernames and passwords:
- helpers/wordlists/wp-users.txt: A list of potential WordPress usernames.
- helpers/wordlists/wp-passwords.txt: A list of common passwords.


## Usage

To use these templates, ensure you have [Nuclei](https://nuclei.projectdiscovery.io/) installed. You can run the templates using the following command:

```bash
nuclei -u <TARGET_URL> -t <TEMPLATE_PATH> -v
