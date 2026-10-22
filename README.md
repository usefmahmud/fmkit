# fmkit

> still in progress, a small developer tools powered by the Apple Foundation Model.

## why?

macOS 27 exposes Apple's Foundation Models to developers outside of apps. It ships with a built-in `fm` command line tool that can talk to the on-device model, and `fm serve` starts a local OpenAI-compatible chat completions server on Mac.

the catch is the size of the model xD <br>
its context window is only about 8K tokens, which is too small for long agent prompts and tool lists but plenty for small focused jobs.

**fmkit** is a set of CLI tools built around exactly those jobs.

## planned tools

- `fmk commit`: draft a commit message from `git diff --staged` (plus an optional git hook)
- `fmk explain`: explain a compiler or runtime error in plain language
- `fmk cmd`: turn a description into a shell command and show it for confirmation
- `fmk name`: suggest names for variables, functions and branches
- `fmk doc`: write short docstrings
- 
