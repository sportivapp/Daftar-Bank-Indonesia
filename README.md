<p align="center">
    <img src="https://i.imgur.com/j8iwglW.png" alt="Sportiv Logo" width="250px"/>
</p>

# Project name

<!--- These are templatees. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->
![GitHub repo size](https://img.shields.io/github/repo-size/sportivapp/README-template.md)
![GitHub contributors](https://img.shields.io/github/contributors/sportivapp/README-template.md)
![GitHub stars](https://img.shields.io/github/stars/sportivapp/README-template.md?style=social)
![GitHub forks](https://img.shields.io/github/forks/sportivapp/README-template.md?style=social)

Project name is a `<utility/tool/feature>` that allows `<insert_target_audience>` to do `<action/task_it_does>`.

Your introduction should be around 2 or 3 sentences. Don't go overboard, people won't read it.

## Structure

| Codebase             |      Description      |
| :------------------- | :-------------------: |
| Frontend Tournament  |    Nuxt.js Frontend   |
| Backend Tournament   |     Nest.js API       |

## Branches
 - development -> pr this branch for everything else  
 - staging -> It'll connect to as many services as it can without touching the prod environment.
 - main -> don't touch, this is what's running in prod

## Code of Conduct
The code of conduct is described in [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).

## Prerequisites

Before you begin, ensure you have met the following requirements:
<!--- These are just example requirements. Add, duplicate or remove as required --->
* You have installed the latest version of `<coding_language/dependency/requirement_1>`
* You have a `<Windows/Linux/Mac>` machine. State which OS is supported/which is not.
* You have read `<guide/link/documentation_related_to_project>`.

## Installing `<project_name>`

To install <project_name>, follow these steps:

Linux and macOS:
```
<install_command>
```

Windows:
```
<install_command>
```
## Using `<project_name>`

To use `<project_name>`, follow these steps:

```bash
# enter the project directory
cd project_name

# pull from latest staging
git pull main 

# install dependency
npm install

# develop
npm run dev
```

Add run commands and examples you think users will find useful. Provide an options reference for bonus points!

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Advanced

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis
npm run preview -- --report

# code format check
npm run lint

# code format check and auto fix
npm run lint -- --fix
```


## Environment Variables

for running in your machine, please prepare your .env

Development
```bash
BASE_URL_API_TOURNAMENT=
BASE_URL_SPORTIV=
SRC_URL_SPORTIV=
```
Production
```bash
BASE_URL_API_TOURNAMENT=
BASE_URL_SPORTIV=
SRC_URL_SPORTIV=
```
## Contributing to `<project_name>`
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
Hello engineers! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting an issue
- Discussing the current state of the code
- Submitting a fix
- Proposing new updates

To contribute to <project_name>, follow these steps:

1. Clone this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Add Changes: `git add -A`.
4. Make your changes and commit them: `git commit -m -S '<commit_message>'`
5. Push to the original branch: `git push`
6. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).


## Contributors

Thanks to the following people who have contributed to this project:

* [@andikaleonardo](https://github.com/andikaleonardo) 👽

You might want to consider using something like the [All Contributors](https://github.com/all-contributors/all-contributors) specification and its [emoji key](https://allcontributors.org/docs/en/emoji-key).

## Contact

If you want to contact me you can reach me at <your_email@address.com>.

## License
<!--- If you're not sure which open license to use see https://choosealicense.com/--->

This project uses the following license: [<license_name>](<link>).
