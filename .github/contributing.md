# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this
project you agree to abide by its terms.

---

Ensure your pull request adheres to the following guidelines heavily inspired by [kdeldycke/awesome-engineering-team-management](https://github.com/kdeldycke/awesome-engineering-team-management/blob/main/.github/contributing.md):

## Pull-requests and issues

- Search past and current issues and pull-requests for previous suggestions before making a new one, as yours may be a duplicate or a work in progress.
- Only one list item per commit.
- Only one commit per pull-request. Always squash commits after applying changes.
- Check your spelling and grammar.
- Add the reason why the linked resource is awesome. And what it adds to existing content.

## Linting

Have your pull-request pass the [official Awesome List's linter](https://github.com/sindresorhus/awesome-lint).

No extra work is required here as it is [already integrated by the way of GitHub actions](https://github.com/httpoz/awesome-engineering-leadership/tree/main/.github/workflows).

To run the linter locally, do:

```shell-session
$ npm i npx
$ npx awesome-lint
```

## Formatting

Additional rules not covered by `awesome-lint`, to keep the content clean and tidy.

If one of these rule conflict with the linter, the linter's rule should takes precedence. Apply it.

### General content
- Remove any trailing whitespaces.
- Use spaces, no tabs, for indention.
- Apostrophes should be using the single ASCII mark: `'`.
- Try to quote the original content as-is to summarize the point of the linked content.
- If a straight quote doesn't cut it, feel free to paraphrase both the item's title and description.

### Item title

- URL must use HTTPs protocol if available.
- No `“` and `”` curved quotation marks. This is reserved for original content quotation in descriptions.
- To quote, use either the single or double variations: `'` and `"`. Keep them properly balanced.



## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.

Thank you for your suggestions!
