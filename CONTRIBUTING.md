# Contribution Guidelines

## Issues

This repository contains issue templates for [bugs] and [feature requests].  
Unclear documentation or error messages are considered bugs.

For anything else, please use the ["Custom issue"] template.

[bugs]: https://github.com/Tamschi/TODO_CRATE_NAME/issues/new?assignees=&labels=bug&template=bug_report.md&title=
[feature requests]: https://github.com/Tamschi/TODO_CRATE_NAME/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=
["Custom issue"]: https://github.com/Tamschi/TODO_CRATE_NAME/issues/new?assignees=&labels=&template=custom_issue.md&title=

## Pull Requests

### Code Style

Please keep your code human-readable.

While there are no formal style requirements, here are some suggestions that might help new code fit in with with the existing:

* Don't use abbreviations unless they are established terms.

  They usually make it harder for me to read the code fluently. You also don't need to worry about alignment; I use a proportional font and likely wouldn't notice.

* Try to keep it simple.

  I can't properly review code I don't understand, so straightforward implementations are usually preferred.

  It's usually fine to use a library to avoid boilerplate, if there's enough documentation so I could replicate it from scratch.

  If you do something custom that's tricky, a link to an explanation of the technique would be nice. I'll just ask if this becomes an issue, though.
