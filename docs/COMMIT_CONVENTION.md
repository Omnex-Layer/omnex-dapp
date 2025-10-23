# Commit Convention

This project follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification to maintain a clean, structured, and consistent commit history across the Omnex ecosystem.

## Format

Each commit message should include a **header**, and may also contain a **body** and a **footer**.


### Type

The **type** describes the purpose of the change. Choose one of the following:

* **feat**: Introduces a new feature or DApp submission.  
* **fix**: Resolves a bug or issue.  
* **docs**: Documentation-only updates.  
* **style**: Code formatting or style changes that don’t affect functionality.  
* **refactor**: Code restructuring that doesn’t add features or fix bugs.  
* **perf**: Performance-related improvements.  
* **test**: Adds or updates tests.  
* **build**: Changes to the build system or dependencies.  
* **ci**: CI/CD configuration or automation updates.  
* **chore**: General maintenance or non-code updates.

### Scope

The **scope** provides context about the area affected by the change. Common scopes include:

* **dapp**: DApp-related changes (e.g., modifying a `dapp.json` file).  
* **workflow**: GitHub Actions or workflow updates.  
* **docs**: Documentation or markdown file changes.  
* **repo**: Repository-wide or configuration updates.  
* **ci**: Continuous integration or deployment pipeline updates.

### Subject

The **subject** offers a concise summary of the change. Follow these rules:

* Use **imperative, present tense** (e.g., “add” not “added” or “adds”).  
* Don’t capitalize the first letter.  
* Don’t end with a period.

### Body (optional)

Use the **body** to explain the motivation, reasoning, or technical details behind your change. Keep it clear and concise.

Example:  
feat(dapp): add new staking DApp configuration '  

This adds the configuration file for the Omnex Staking DApp, including metadata, verified contract addresses, and logo URLs. '

### Footer (optional)

Use the **footer** to reference issues, PRs, or note breaking changes.

Examples:  
BREAKING CHANGE: renamed "tokenAddress" field to "contractAddress" '  
  
' Fixes #142 '

---

Following this convention ensures the Omnex repository maintains a professional, transparent, and developer-friendly commit history.
