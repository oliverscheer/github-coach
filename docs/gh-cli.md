# GitHub CLI

[Back](../README.md)

The GitHub CLI (Command Line Interface) provides a convenient way for developers
to interact with GitHub directly from the command line. Here are some of its top features:

1. **Repository Management**: Easily create, clone, fork, and manage repositories from the command line.

2. **Issue Management**: View, create, close, and manage issues associated with repositories.

3. **Pull Request Management**: Create, review, merge, and close pull requests without leaving the command line interface.

4. **GitHub Actions**: Trigger and manage GitHub Actions workflows directly from the command line.

5. **Gist Creation and Management**: Create, list, edit, and delete Gists (short snippets of code or text) from the command line.

6. **Workflow Automation**: Automate common tasks and workflows using scripts and shell commands with GitHub CLI.

7. **Status Checks**: View the status of checks and workflows associated with pull requests or commits.

8. **Interactivity**: Benefit from an interactive command-line experience with prompts and menus for selecting options and providing input.

9. **Authentication and Authorization**: Authenticate to GitHub and authorize access to repositories securely from the command line.

10. **Customization**: Customize GitHub CLI with aliases and configuration settings to streamline workflows and improve efficiency.

These features allow developers to efficiently manage their GitHub workflows, repositories, issues, and pull requests directly from the command line, enhancing productivity and facilitating seamless integration with their development workflows.

```cmd
gh issue list

gh issue create --label documentation
```

## 🔨 Exercises

1. Clone a repository

    <details><summary>Solution</summary>
    You get this command directly online from GitHub -> Prroject -> Code -> Button -> Code -> GitHub Cli

    ```cmd
    gh repo clone oliverscheer/github-coach
    ```

    </details>

1. Create a pull request as draft

    <details><summary>Solution</summary>
    You get this command directly online from GitHub -> Prroject -> Code -> Button -> Code -> GitHub Cli

    ```cmd
    gh repo clone oliverscheer/github-coach
    ```

    </details>

1. Checkout a pr

    <details><summary>Solution</summary>

    ```cmd
    gh pr list
    gh pr checkout 7
    ```

    </details>

1. Run a Workflow

    <details><summary>Solution</summary>

    ```cmd
    gh workflow run triage.yml -f name=scully -f greeting=hello
    ```

    </details>

[Back](../README.md)
