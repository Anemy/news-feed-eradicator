News Feed Eradicator
====================

A browser extension that deletes your Facebook news feed.
Extended from the news feed readicator which displays quotes.

Install: clone the repository and then run:

    make install
    BROWSER=chrome webpack

    (You might have to run make install as an administrator)

Project folder structure:

    src                             # Common code across all browsers
    browsers                        # Browser specific code
    assets                          # Images
    news-feed-eradicator.west.io    # Companion website

    # Build output:
    build                           # The raw extension contents for each browser
    dist                            # Distributable extension package for browsers
