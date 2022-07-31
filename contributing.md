# Contributing 💕

We welcome contributions of any kind and deeply appreciate the amazing people who have spent their time and energy to contribute to what we're working for.  The things we're working for can make a difference in the world and every contribution, big or small, helps us move closer towards realizing our goals and ultimately our vision.

If you'd like to contribute there are some guidelines we have set in place to ensure we're all on the same page, moving towards the same goals and that there are standards in place for some consistency.  If you aren't sure about anything you can feel free to ask, we're happy to help!

We recommend that you have a look at our [code of conduct](https://github.com/matriarx/.github/blob/main/code_of_conduct.md) and that you understand our purpose and mission, our goals and objectives and that the contribution you make is in alignment with what we're working for.  You can also have a look at our policy and misconduct to ensure you don't violate it, we are strict with our policy and misconduct in order to keep our community healthy and a safe space for everyone.

## Contribution

✔️ If you have any issues with the software you can report it by creating a new [issue](https://github.com/matriarx/.github/issues).
✔️ You can have a look at the [project](https://github.com/matriarx/.github/projects) page to see the current roadmap and things we're working on and you're welcome to make a [pull request](https://github.com/matriarx/.github/pulls).  If you do then fork the repository and create a pull request from the fork, don't push directly to the repository.  If you intend to create a feature or make a large change then get in [contact](https://github.com/matriarx/.github/blob/main/support.md) and let's discuss it first.
✔️ If you'd like to contribute in any other way beyond software you're welcome to get in [contact](https://github.com/matriarx/.github/blob/main/support.md) and let us know what you can help with.
✔️ You can also help by [funding](https://github.com/matriarx/.github/blob/main/readme.md) us.

## DCO

Developer Certificate of Origin ([DCO](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin)) is enforced on all repositories in order to verify that you made that commit and that you have agreed to our terms which state that your contribution falls under MIT and that you void all claims to any intellectual property or copyright without any exceptions.  This is a simpler alternative and less invasive to your privacy than using a Contributor License Agreement (CLA).  If you have any questions or concerns you're welcome to ask.

✔️ [Create a new GPG key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key).\
✔️ [Add the GPG key to your github account](https://docs.github.com/en/authentication/managing-commit-signature-verification/adding-a-gpg-key-to-your-github-account).\
✔️ Have a look at [how to sign your commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits) using your GPG key.\
✔️ After you've set it up you can use `git commit -S -am "message"` in order to create a signed and verified commit.

## Semantic Versioning & Conventional Commits

We use semantic versioning with conventional commits which are used to automatically generate the version, changelog and release notes.  If you contribute code make sure you follow our convention, otherwise it will be rejected.  If you aren't sure about anything or would like some help feel free to reach out, we're happy to help!

### Semantic Versioning

The version will be automatically generated from commits and tags, don't update it manually.

### Conventional Commits

We use conventional commits in order to automatically generate the changelog and release notes and to make it easier to debug in case we need to.

#### Commit

✔️ When making a commit do so using `type(scope): description` as the format in order to specifcy the type of commit, the scope, whether or not it's a breaking change and the description.\
✔️ Use the directory that is the primary focus of your update as the scope.
✔️ If the commit includes a breaking change then include `!` using `type(scope)!: description` as the format to specify that it changes existing code in a backwards incompatible way.\
✔️ Only use lowercase for the description.

#### Example

`git commit -S -am "feature(module)!: a new module feature"`

✔️ This shows that the commit is a new feature.\
✔️ It shows that the update is primarily scoped to the module directory.\
✔️ It shows that it contains a breaking change.\
✔️ It has a clean lowercase description.

#### Types

✔️ feature - A completely new feature.\
✔️ update - An update to an existing feature.\
✔️ patch - A relatively small update to a module or component.\
✔️ security - An update specifically related to security.\
✔️ performance - An update specifically related to performance.\
✔️ config - An update that changes any configurations.\
✔️ build - An update that changes the build.\
✔️ ci - An update related to continuous integration.\
✔️ platform - A platform specific update.\
✔️ fix - A bug or hot fix.\
✔️ deprecate - A feature is being deprecated.\
✔️ remove - A feature has been removed.\
✔️ revert - A rollback.\
✔️ task - A relatively insignificant yet necessary chore.\
✔️ refactor - Code refactoring.\
✔️ polish - Code formatting or styling.\
✔️ documentation - An update to the documentation.

#### Commit History

We use a strict linear commit history in order to properly generate the changelogs and release notes and to make it easier to debug in case we need to, so rebase or squash the merge in order to keep the history clean.  For almost every use case you should be using rebase instead of squashing in order to preserve the commit history and to properly reflect changes in the generated changelog.  However there are two exceptions to that rule.

✔️ Only use rebase if the commits on your local branch have never been pushed to remote.  If at any point you pushed those commits to remote, rebasing it can be a potentially destructive action and you should then squash it instead.\
✔️ Each commit should have a meaningful and tangible update or change, if you've made a bunch of commits and some of them have silly messages like i.e. "fix typo" then you should squash it, don't include meaningless commits into the commit history.  However you should avoid doing that altogether in order to preserve the commit history.

## Legal

✔️ All software created by Mia Matriarx or by the Matriarx brand are free and open source software ([FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)) under the [MIT](https://github.com/matriarx/.github/blob/main/license.md) license unless otherwise specified.\
✔️ Any contribution made to software owned by Mia Matriarx or the Matriarx brand, or to any Matriarx community, falls under [MIT](https://github.com/matriarx/.github/blob/main/license.md) and in doing so you void all claims to any intellectual property or copyright without any exceptions.
✔️ Developer Certificate of Origin ([DCO](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin)) is enforced on all repositories in order to verify that you made that commit and that you have agreed to our terms.
✔️ Any unverified or unsigned commit will be rejected.
