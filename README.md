# FOSSA Custom License Configuration

The purpose of this repository is to demonstrate FOSSA's new custom license and keyword search feature. Details about it can be found [here](https://github.com/fossas/fossa-cli/blob/master/docs/features/custom-license-and-keyword-searches.md).

### Example output

```
➜  fossa-custom-license-configuration git:(main) fossa analyze
Analyzing setuptools project at /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/

Scan Summary
------------
fossa-cli version 3.8.15 (revision 3d44d31c1b09 compiled with ghc-9.0)
fossa endpoint server version: 4.15.13

2 projects scanned;  0 skipped,  2 succeeded,  0 failed,  13 analysis warnings

* setuptools project in "/Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/": succeeded with 1 warning
-
* Keyword Search: succeeded with 12 warnings
  ** Password - /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/exposed.txt (lines 1-1)
* Custom-License Search: succeeded with 12 warnings
  ** chelsea's license - /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/LICENSE (lines 1-1)
  ** Proprietary License - /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/testing.txt (lines 1-2)
  ** Proprietary License - /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/testing.txt (lines 3-4)
  ** Proprietary License - /Users/halmeoni/Desktop/test-portfolio/fossa-custom-license-configuration/testing.txt (lines 5-6)

  Some projects may not appear in the summary if they were filtered during discovery.
  You can run `fossa list-targets` to see all discoverable projects.

You can pass `--debug` option to eagerly show all warning and failure messages.
You can also view analysis summary with warning and error messages at: "/private/var/folders/lg/kd7z57sx28dg539z7fthv8w00000gn/T/fossa-analyze-scan-summary.txt"
------------

Using project name: `https://github.com/cmboling/fossa-custom-license-configuration.git`
Using revision: `58fd64a1d26a5c77ce8e81042f8d904780f58ac5`
Using branch: `main`
============================================================

    View FOSSA Report:
    [FOSSA Report Link]
============================================================

```


