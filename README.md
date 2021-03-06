# Version Bumper

Demonstrates how to inject a modules version into the compiled code, and how to
automate bumping versions via a `pre-push` git hook.

![bumping-versions](https://user-images.githubusercontent.com/344140/30776115-a6ed470e-a055-11e7-9d6e-e62b4ce60b0c.gif)

---

## Installation

```sh
npm i
```

---

## Notes

- If you're working on a large project (with multiple contributors) you'd rename
  the `prepush` script to `prepublishOnly` in `package.json`. This way devs can
  go through the PR process and a manual publish can occur once the code's been
  merged in.
