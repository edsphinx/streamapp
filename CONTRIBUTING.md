# How to contribute

Any help is welcome to add features or enhance the Style, Code or
anything that will improve any feature, I started this project as
a custom stream project for some online video training but is becoming 
an option for someone looking for a private and fast streaming solution.


## Making Changes

  * Create a topic branch from where you want to base your work.
  * This is usually the master branch.
  * Only target release branches if you are certain your fix must be on that
    branch.
  * To quickly create a topic branch based on master, run `git checkout -b
    fix/master/my_contribution master`. Please avoid working directly on the
    `master` branch.
  * Make commits of logical and atomic units.
  * Check for unnecessary whitespace with `git diff --check` before committing.
  * Make sure your commit messages are in the proper format. If the commit
    addresses an issue filed in the
    [STREAMAPP Jira project](https://tickets.luminode.com/browse/STREAMAPP), start
    the first line of the commit with the issue number in parentheses.

    ```
        (STA-1234) Make the example in CONTRIBUTING imperative and concrete

        Without this patch applied the example commit message in the CONTRIBUTING
        document is not a concrete example. This is a problem because the
        contributor is left to imagine what the commit message should look like
        based on a description rather than an example. This patch fixes the
        problem by making the example concrete and imperative.

        The first line is a real-life imperative statement with a ticket number
        from our issue tracker. The body describes the behavior without the patch,
        why this is a problem, and how the patch fixes the problem when applied.
    ```
  * Make sure you have added the necessary tests for your changes.
  * For details on how to run tests, please see [the quickstart guide](https://github.com/edsphinx/streamapp/blob/master/docs/quickstart.md)
