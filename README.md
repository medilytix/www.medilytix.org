This is the source directory for the Medilytix website.

## PREREQUISITES

1. Download [Hugo](https://gohugo.io/) if not already present in directory.
2. [Git](https://git-scm.com/downloads) 2.5 or geater installed on your machine.
3. A member of the medilytix GitHub organization with appropriate privileges.


## EDITING

1. The site structure (i.e. the pages in the site) is defined in `config.yaml`.
2. The content for each page is in the `content/page` files.
2. Preview the site by running `./hugo server` from the Terminal and open your browser at the location it tells you too. That command will stay running and automatically update the site on every save.


## PUBLISHING

```bash
./publish.sh
```
