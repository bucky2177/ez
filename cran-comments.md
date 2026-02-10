This submission addresses the issues that led to the archival of the package ez.
The package was archived due to failing checks and lack of response from the 
previous maintainer. 

The reported check failures have been fixed (see the CHANGES file), and the 
package now passes R CMD check on current CRAN platforms.

The original maintainer has been contacted via email and GitHub but has not 
responded. Given this, I am submitting this update to restore the package and 
am willing to take over maintenance if appropriate.

No user‑visible changes were introduced; all modifications are maintenance fixes
to ensure compatibility with current R and CRAN policies.

# CHECKS

Duration: 1m 59s

❯ checking CRAN incoming feasibility ... NOTE
  Maintainer: 'Valentin Koob <v.koob@web.de>'
  
  New submission
  
  Package was archived on CRAN
  
  CRAN repository db overrides:
    X-CRAN-Comment: Archived on 2026-01-31 as issues were not corrected
      despite reminders.

❯ checking for future file timestamps ... NOTE
  unable to verify current time

❯ checking for detritus in the temp directory ... NOTE
  Found the following files/directories:
    'lastMiKTeXException'

0 errors ✔ | 0 warnings ✔ | 3 notes ✖