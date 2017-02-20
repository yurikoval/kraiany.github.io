# kraiany.github.io
Home for the Kraiany projects



## Contributing

1. Fork the repo on GitHub
2. Clone the project to your own machine
3. Commit changes to your own branch
4. Push your work back up to your fork
5. Submit a Pull request so that we can review your changes

*Please note*: All Pull Requests should be submitted against `develop`
branch, not `master`. Please see explanation below.

## Github pages and Branches

This project uses [GihubPages](https://pages.github.com/) for hosting
final, parsed site. The way Github pages work sets how branches are used
in this project.

- `master` branch -- generated HTML, CSS, JS code.

- `develop` branch -- main branch to submit PR's, testing and source of
the deployment.

Merge of the PR to `develop` branch triggers automated testing and
deploy of the master branch.

Workflow of the deployment is as follows:


```
                              Travis      Final
              PR              deploy      site
[USER BRANCH] --> [`develop`] -------> [`master`]


```
