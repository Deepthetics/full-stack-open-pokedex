The hypothetical project is written in Python.

Specific tools for linting, testing and building steps in the CI pipeline:

- linting can be done with Pylint.

- automated testing can be done with Pytest.

- building can be done with pipenv.

Some alternatives to Jenkins and GitHub Actions are Travis CI and CircleCI, both of which support integration with GitHub. GitLab CI/CD is one alternative if GitLab is used for source code management and cooperation. GitLab CI/CD is built-in to GitLab and doesn’t need additional configuration.

The choice between self-hosted and cloud-based environment for the CI/CD setup depends on the scale and specific needs of the project. Cloud-based environment is usually easier to configure and cheaper to set up and is better suited for small projects without special requirements. However, cloud-based CI/CD usually have limited resources and might not be as customizable compared to self-hosted CI/CD. Self-hosted environment might be better suitable for larger projects and organizations when there are potentially multiple teams taking advantage of it. Setting up the environment might need more work but it’s more customizable and even specific resources like GPU can be added to the system more easily.
