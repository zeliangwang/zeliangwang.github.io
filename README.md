## Data for personal webpage 
`zeliangwang.github.io`
***
### How to build and run static website using `Jekyll`
1. Create a new `Gemfile` in your project root directory to list your project's dependencies
    ```bash
    bundle init
    ```
2. Edit the `Gemfile` and add jekyll as a dependency
3. Run `bundle` to install jelyll 
    ```bash
    # prefix jekyll command with "bundle exec" to make sure you use the jekyll version defined in your Gemfile
    bundle exec jekyll serve

    ```
***
### Reference
[Jekyll documentation](https://jekyllrb.com/docs/step-by-step/01-setup/)