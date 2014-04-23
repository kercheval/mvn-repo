View http://kercheval.org/mvn-repo/ for details on this project.

After publication of new files to the repository, run the following to update index pages (required for nexus proxy operations).

```
> recursive_index.bat
```

Or run the following perl script explicitly

```
> perl recursive_index.pl -d releases -r
```
