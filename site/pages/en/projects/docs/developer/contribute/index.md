---
page_ref: "@ARK_PROJECT__VARIANT@/termux/termux-exec-package/docs/@ARK_DOC__VERSION@/developer/contribute/index.md"
---

# termux-exec-package Contribute Docs

<!-- @ARK_DOCS__HEADER_PLACEHOLDER@ -->

These docs are meant for you if you want to contribute to the [`termux/termux-exec-package`](https://github.com/termux/termux-exec-package) repository.

### Contents

- [Commit Messages Guidelines](#commit-messages-guidelines)

---

&nbsp;





## Commit Messages Guidelines

Commit messages **must** use the [Conventional Commits](https://www.conventionalcommits.org) spec so that changelogs can be automatically generated when [releases](../../../releases/index.md) are made as per the [Keep a Changelog](https://github.com/olivierlacan/keep-a-changelog) spec by the [`create-conventional-changelog`](https://github.com/termux/create-conventional-changelog) script, check its repository for further details on the spec.

**The first letter for `type` and `description` must be capital and description should be in the present tense.** The space after the colon `:` is necessary. For a breaking change, add an exclamation mark `!` before the colon `:` as an indicator, and it will also cause the change to be automatically highlighted in the changelog.

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Only the `types` listed below must be used exactly as they are used in the changelog headings.** For example, `Added: Add foo`, `Added|Fixed: Add foo and fix bar`, `Changed!: Change baz as a breaking change`, etc. You can optionally add a scope as well, like `Fixed(docs): Fix some bug`. **Do not use anything else as type, like `add` instead of `Added`, or `chore`, etc.**

- **Added** for new additions or features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Fixed** for any bug fixes.
- **Removed** for now removed features.
- **Reverted** for changes that were reverted.
- **Patched** for patches done for specific builds.
- **Security** in case of vulnerabilities.
- **Release** for when a new release is made.

---

&nbsp;
