This document is to maintain naming conventions and easily refer back to whichever version you are looking for.

(EOS) Slow Slow v0 is the most updated and completed version of the code prior to Nicole's comments.
  - All v0 code files are tested updates to the code such as
      - v0.1 with an added column formatting function (doesn't work) :white_check_mark:
      - v0.2 is unmerging additional rows and resizing the rows to match merged height (mainly for top side of document format) &cross;
        - v0.2.x.y (x varies depending on 0.2 version) remove grey column at the end of the table &cross;
      - v0.3 replaces non capitalized codes with capitalized versions (ie. Tpmt --> TPMT) &cross;
  - v1 implements efficient row sizing :white_check_mark:
  - v2 code will focus on implementing column width changes :white_check_mark:
      - v2.x will be updated row sizing values to better fit with column width changes
  - v3 fixes header rows
      - v3.1 does a lot of things
        - implements efficient row sizing for inserted header columns too
        - removes added header rows
        - replaces them with properly formatted header rows
        - optimized page break search
      -v3.2 fixes initial header row height --> changed CleanUpHeaderMergedRows
  - v4 fixes bolding &cross;
      - v4.x fixes code bolding &cross;
      - v4.x.y fixes bolding in rows following greyed out rows &cross;
  - v5 add periods to the end of comment section &cross; ❎
  - v6 modularize everything into its own set of functions - main macro to be barebones calling on functions &cross;
