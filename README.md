[![Auth0 Training](https://user-images.githubusercontent.com/73120/125103885-a2bb5d80-e091-11eb-8084-383003f1e484.png "Auth0 Training")](https://training.auth0.com)

# SCORM Package Adapt ID Basics 1

### Requirements

This project assumes the user is using [Visual Studio Code](https://code.visualstudio.com/download) and [Docker Desktop](https://www.docker.com/products/docker-desktop).

The [Remote - Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) extension needs to be installed in VSCode.

### Snippets

This project is configured with snippets to generate common chunks of code. Type the name of the snippet in the location you would like the chunk of code to go.

| Name       |                        Description                         |
| ---------- | :--------------------------------------------------------: |
| block      |     Creates a new block item for the blocks.json file      |
| video      |   Creates a new video item for the components.json file    |
| graphic    |  Creates a new graphic item for the components.json file   |
| text       |    Creates a new text item for the components.json file    |
| question   |  Creates a new question item for the components.json file  |
| conclusion | Creates a new conclusion item for the components.json file |

### Getting Started - Dev Container

To get started using this lab, ensure you have met the minimum [requirements](#requirements) and then follow these steps.

1. Clone this repository to your local machine.

```bash
git clone https://github.com/auth0-training/scorm-packages-adapt-idbasics-1.git
```

2. Start Docker Desktop.
3. Open the directory containing the source code in VSCode.
4. When prompted to reopen the project in a development container, select **Reopen in Container**.
   ![Devcontainer Prompt](https://cdn.auth0.com/website/a0fun/v2/devcontainer-prompt.gif?raw=true)

This will build an image containing all the tools needed to work on this project. A container will be started and VSCode will connect to it.

### Getting Started - Local

To get started using this lab, ensure you have met the minimum [requirements](#requirements) and then follow these steps.

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/auth0-training/scorm-packages-adapt-idbasics-1.git
   ```
1. Change directories to the cloned repository, `cd scorm-packages-adapt-idbasics-1`.
1. Run the **init** script, `npm run local:init`.
1. Run the **dev** process, `grunt dev`.
1. Run the **serve** process, `grunt server`.

### What is Auth0?

---

Auth0 helps you to:

- Add authentication with [multiple authentication sources](https://auth0.com/docs/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
- Add authentication through more traditional [username/password databases](https://auth0.com/docs/connections/database/custom-db).
- Add support for [linking different user accounts](https://auth0.com/docs/link-accounts) with the same user.
- Support for generating signed [JSON Web Tokens](https://auth0.com/docs/jwt) to call your APIs and **flow the user identity** securely.
- Analytics of how, when, and where users are logging in.
- Pull data from other sources and add it to the user profile, through [JavaScript rules](https://auth0.com/docs/rules/current).

### Issue Reporting

---

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

### Author

---

[Auth0](https://auth0.com)

### License

---

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
