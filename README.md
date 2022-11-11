## Prerequisites

1. We have a link shortcuts at the end of a file:

```md
[link1]: any
[link2]: any
```

2. After running remark:

```sh
remark --output -- .
```

3. Newlines are added between shortcuts:

```md
[link1]: any

[link2]: any

```

diff: https://github.com/muravjev/repro_remark_shortcuts/compare/e6a60c6...2cf76bd

## Question

Is it possible to prevent such behavior?

## Reproduction

repo: https://github.com/muravjev/repro_remark_shortcuts

```sh
git clone https://github.com/muravjev/repro_remark_shortcuts.git
cd repro_remark_shortcuts
pnpm install
pnpm repro
```
