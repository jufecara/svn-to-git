# Migration Tool

Script to help migrate code from SVN to GIT without losing commits history, tags and branchs.

## Requirements/Dependencies

```
 sudo apt-get install git-core subversion git-svn
```

## Configuration
Change the variables in the properties file:

* domain.name=company.com
* svn.host=https://svn.company.com
* svn.user=username
* svn.password=
* svn.branches=branches
* svn.tags=tags
* svn.trunk=trunk
* svn.include-paths=
* git.host=git.company.com
* git.protocol=https
* git.user=username
* git.password=

## Execution

```
nohup ./svntogit &
```
