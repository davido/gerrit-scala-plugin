Gerrit Scala Plugin
===================

This repository contains Gerrit plugins written in Scala.

To deploy, drop a file in `$gerrit_site/plugins` directory, done.

Review Plugin
-------------

List existing commands:

```
ssh gerrit review

ssh gerrit review
Available commands of review are:

   approve
   dislike
   recommend
   reject

See 'review COMMAND --help' for more information.
```

Approve change:

```
ssh gerrit review approve I59302cbb
Approve change: I59302cbb
```

