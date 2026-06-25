# Contributing to Think-Zone

Thanks for your interest in contributing! Think-Zone is built in public and we genuinely value input from the builder community.

## How to Contribute

### Reporting Bugs

- Check [existing issues](https://github.com/think-zone/creator-os/issues) before opening a new one
- - Use the bug report template and include steps to reproduce
  - - For security vulnerabilities, see [SECURITY.md](./SECURITY.md) — do not open a public issue
   
    - ### Suggesting Features
   
    - - Open a [Discussion](https://github.com/think-zone/creator-os/discussions) first for large ideas
      - - For small improvements, open an issue with the `enhancement` label
       
        - ### Submitting Pull Requests
       
        - 1. **Fork** the repository and create a feature branch (`feat/my-feature`)
          2. 2. **Follow the coding standards** defined in `AGENTS.md` / `.claude/` in each repo
             3. 3. **Write tests** for any new functionality where applicable
                4. 4. **Keep PRs focused** — one logical change per PR makes review easier
                   5. 5. **Open a draft PR early** if you want feedback before finishing
                      6. 6. **CI must pass** before merge — the `CI` workflow is required
                        
                         7. ### Commit Style
                        
                         8. We use [Conventional Commits](https://www.conventionalcommits.org/):
                        
                         9. ```
                            feat(scope): add new feature
                            fix(scope): fix a bug
                            docs(scope): update documentation
                            chore(scope): maintenance tasks
                            ```

                            ## Project Structure

                            | Repo | What it is |
                            |------|-----------|
                            | [`creator-os`](https://github.com/think-zone/creator-os) | Main monorepo — services, apps, SDKs |
                            | [`cognitive-mcp`](https://github.com/think-zone/cognitive-mcp) | Standalone MCP server package |

                            ## Code of Conduct

                            Be excellent to each other. We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

                            ## Questions?

                            Open a [Discussion](https://github.com/think-zone/creator-os/discussions) or reach out via issues.
