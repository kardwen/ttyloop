# ttyloop

```
┌──────────┤ ttyloop ├──────────┐
│ ┌───────────────────────────┐ │
│ │ ╭──╴  ╭──╴  ╶──╮  ╶──┬──╮ │ │
│ │ ╵  ╶──┴──┬──╮  ├──╮  │  │ │ │
│ │ ╷  ╶──╮  ├──┴──┤  ├──┤  ╵ │ │
│ │ ╰──╮  ├──╯     ├──╯  ╵    │ │
│ │    ├──┴──┬──╮  ╰─────╮  ╷ │ │
│ │    ╰──┬──┼──╯     ╭──┴──┤ │ │
│ │ ╷  ╷  ╰──┤  ╭──┬──┼──╴  ╵ │ │
│ │ │  ╰──┬──┤  │  ╰──┼──╮  ╷ │ │
│ │ ╵     ╰──╯  ╰──╴  ╰──┴──╯ │ │
│ └───────────────────────────┘ │
│ hjkl/arrows: move             │
│ ui: rotate                    │
│ n: new puzzle                 │
│ c: configure                  │
│ ctrl+C: quit                  │
└───────────────────────────────┘
```

A terminal clone of the mobile game Loop.

To win, you must rotate the individual tiles until you have a path of maximum length.

---

I play this in my terminal with the [Iosevka](https://github.com/be5invis/Iosevka) font.
It uses pretty standard box-drawing characters, so it should work with most fonts, but I guess not with whatever font Github uses.
