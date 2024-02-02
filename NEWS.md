# resmush 0.1.0

-   Now **resmush** uses **httr2** instead of **httr**.
-   Add DOI: <https://doi.org/10.5281/zenodo.10556679>.
-   `resmush_file()`, `resmush_dir()` and `resmush_url()` gain an new argument
    `overwrite`.
-   Changes in the API: New messages and use of progress bars with
    `cli::cli_progress_bar()`. These changes also affects the following:
    -   New arguments `progress` and `report`.
    -   Deprecated the `verbose` argument.
    -   `resmush_clean_dir()` shows messages with the summary of the process.
-   New packages on `Suggests` for examples: **png**, **grid**.

# resmush 0.0.1

-   Initial version