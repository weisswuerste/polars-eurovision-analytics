# Polars (Eurovision) Analytics

Some previous analytics work was done on the Eurovision contest through the Pandas library, and now it has been rewritten using the Polars library. There are probably some sloppy patches that could have been better thought out and written, but both files are practically the same and easy enough to follow to serve as a reference on how to do something in Polars coming from Pandas.
- #### Pandas.
  - The original work covering the results of the Eurovision contest from 1956 to 2019 is all there.
  - Some updates were made to Matplotlib charts.
- #### Polars.
  - An update work covering the same material now using solely the Polars library.
  - Biggest conceptual differences? The usage of joins in favour of splicing columns and the lack of indexing.

This migration was also made possible thanks to this [cheat sheet](https://www.rhosignal.com/posts/polars-pandas-cheatsheet/), so this site deserves credit as well.
