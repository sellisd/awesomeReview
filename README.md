# Automate the review process of awesome lists

Here are the requirements for a successful review. I have classified the requirements as:

- ✔ those that I think could be relatively easy to check with a script
- 👁 those that need a careful look by a human
- ⁇ Could possibly be automated, but I do not know the technology to do it

- ⁇ **Has been around for at least 30 days.**<br>That means 30 days from either the first real commit or when it was open-sourced. Whatever is most recent.
- 👁 It's the result of hard work and the best I could possibly produce.
- ⁇ Non-generated Markdown file in a GitHub repo.
- 👁 **Includes a succinct description of the project/theme at the top of the readme.** [(Example)](https://github.com/willempienaar/awesome-quantified-self)
- 👁 The repo should have `awesome-list` & `awesome` as [GitHub topics](https://help.github.com/articles/about-topics). I encourage you to add more relevant topics.
- ✔ Not a duplicate.
- 👁 Only has awesome items. Awesome lists are curations of the best, not everything.
- ✔ Includes a project logo/illustration whenever possible.
	- ⁇ Either fullwidth or placed at the top-right of the readme. [(Example)](https://github.com/sindresorhus/awesome-electron)
	- ✔ The image should link to the project website or any relevant website.
	- ⁇ The image should be high-DPI. Set it to maximum half the width of the original image.
- ✔ Entries have a description, unless the title is descriptive enough by itself. It rarely is though.
- ✔ Includes the [Awesome badge](https://github.com/sindresorhus/awesome/blob/master/awesome.md#awesome-badge).
	- ⁇ Should be placed on the right side of the readme heading.
	- ✔ Should link back to this list.
- ✔ Has a Table of Contents section.
	- ✔ Should be named `Contents`, not `Table of Contents`.
	- ✔ Should be the first section in the list.
	- ⁇ Should only have one level of sub-lists, preferably none.
- ⁇ Has an [appropriate license](https://github.com/sindresorhus/awesome/blob/master/awesome.md#choose-an-appropriate-license).
	- That means something like CC0, **not a code licence like MIT, BSD, Apache, etc.**
	- [WTFPL](http://www.wtfpl.net) and [Unlicense](http://unlicense.org) are not acceptable licenses.
	- ⁇ If you use a license badge, it should be SVG, not PNG.
- ✔ Has [contribution guidelines](https://github.com/sindresorhus/awesome/blob/master/awesome.md#include-contribution-guidelines).
	- ✔ The file should be named `contributing.md`. Casing is up to you.
- Has consistent formatting and proper spelling/grammar.
	- ✔ The link and description are separated by a dash. <br>Example: `- [AVA](…) - JavaScript test runner.`
	- ✔ The description starts with an uppercase character and ends with a period.
	- 👁 Consistent and correct naming. For example, `Node.js`, not `NodeJS` or `node.js`.
- ⁇ Doesn't include a Travis badge.<br>You can still use Travis for list linting, but the badge has no value in the readme.
