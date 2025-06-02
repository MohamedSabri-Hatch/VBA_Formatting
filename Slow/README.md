This document is to maintain naming conventions and easily refer back to whichever version you are looking for.

(EOS) Slow Slow v0 is the most updated and completed version of the code prior to Nicole's comments.
  - All v0 code files are tested updates to the code such as
      - v0.1 with an added column formatting function (doesn't work)
      - v0.2 is unmerging additional rows and resizing the rows to match merged height (mainly for top side of document format)
        - v0.2.x.1 (x varies depending on 0.2 version) remove grey column at the end of the table
      - v0.3 replaces non capitalized codes with capitalized versions (ie. Tpmt --> TPMT)
  - v1 implements efficient row sizing
  - v2 code will focus on implementing column width changes
  - v3 fixes bolding
      - v3.x fixes code bolding
      - v3.1.x fixes bolding in rows following greyed out rows
  - v4 add periods to the end of comment section
  - v5 modularize everything into its own set of functions - main macro to be barebones calling on functions
