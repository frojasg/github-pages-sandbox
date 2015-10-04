# Things I've learned so far about with jekyllrb

* More blog-aware tool
* oriented to serve a collection of resouces

# How to use

Run a development server to see how your documentation is looking

``` rake server ```

Generate documentation so we can push them to gh-pages

``` rake build ```

## Deploying the documentation

1. Generate documentation ``` rake build ```
2. Change branch to gh-pages ``` git checkout gh-pages ```
3. Deploy your changes ``` git add -A && git commit && git push ```
