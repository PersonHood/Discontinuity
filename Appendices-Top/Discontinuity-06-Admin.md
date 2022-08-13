[  this is a comment. ]::

<link href="styles.css" rel="stylesheet"></link>

> [Discontinuity](../Discontinuity.md) | [Appendices](./Discontinuity-00-Appendices.md) | [WTF](./Discontinuity-01-WTF.md) | [Motivate](./Discontinuity-02-Motivate.md) 
> [Overview](./Discontinuity-03-Overview.md) | [Definitions](./Discontinuity-04-Definitions.md) | [Memes](./Discontinuity-05-Memes.md) | [Admin](./Discontinuity-06-Admin.md) 
> [TT4N](./Discontinuity-07-TT4N.md) | [Hosts](./Discontinuity-08-Hosts.md) | [Bibliography](./Discontinuity-99-Bibliography.md) 

# Admin

- Discontinuity-06-Admin.md

Several `bash` scripts are employed
> `./Discontinuity/bash/2b*

A directory structure and files are employed
> `./TEMPLATE/TEMPLATE.md` *et al*

Each `script` addresses a specific need:

- 2bmake PROJDIR ProjectName
  - create the new directory structure
    - `./PROJDIR/` *et al*
  - copy files
  - rename files
    - `TEMPLATE*` -> `ProjectName*`
  - change TEMPLATE contents
    - `TEMPLATE` -> `ProjectName`
- Manage data and files
  - 2bmd2tab
  - 2bmd2csv
  - 2bmd2html
  - 2bmerge
  - 2bsplit
  - 2btouch
  - 2bgone
- Manage Sites
  - 2bhost - upload to GitHub *et al*
  - 2bmove - rename
  - 2bdupe - sub-template
  - 2barch - remove, zip archive
- Manage Server
  - YAML - `Jekyll`
  - CSS
