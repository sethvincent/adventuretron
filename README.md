# adventuretron

Create self-guided workshops using electron.

## Work in progress

Basically nothing works yet 😬. But check back! I'm not done yet!

## Inspiration

This project is inspired by a number of others:

- The original terminal-based packages for creating [NodeSchool](http://nodeschool.io/#workshoppers) workshops: [adventure](https://github.com/substack/adventure) & [workshopper](https://github.com/workshopper/workshopper).
- [jlord](https://github.com/jlord)'s awesome [git-it-electron](https://github.com/jlord/git-it-electron) workshop.
- [shader school](https://github.com/stackgl/shader-school) & [webgl-workshop](https://github.com/stackgl/webgl-workshop) by [hughsk](https://github.com/hughsk) & [mikolalysenko](https://github.com/mikolalysenko)

## Why make this?

After making [javascripting](https://github.com/sethvincent/javascripting) and running a few nodeschool events, I've found that folks struggle with reading all the instructions in the terminal. In part this can be due to various cross-platform issues with specific versions of node. Additionally, trying to have colorized terminal output that is accessible for everybody seems weirdly difficult.

Electron can help with this. [git-it-electron](https://github.com/jlord/git-it-electron) is a great example of how we can have clear, readable instructions in a cross-platform desktop app that still encourages people to learn using the same tools they'd regularly use doing this kind of work.

## Open Questions

This is still early in development, so there are a few undecided elements of this project that you might be able to help with. Each item below has a corresponding [issue](https://github.com/sethvincent/adventuretron/issues).

### Would a different name be better?

I like imagining a robot named `adventuretron` adventuring around the interwebs teaching technology & advancing digital equity. But it's not really a clear name. It does reasonably portray the origins and prior art of the project: a package based on [adventure](https://github.com/substack/adventure) that depends on [electron](http://electron.atom.io). Your thoughts?
[Issue #1](https://github.com/sethvincent/adventuretron/issues/1)

### Are you trying to make workshops that run as both websites & electron apps?

There are some file system limitations to building apps that work on the web compared to building them as electron apps. But maybe those can be overcome?
[Issue #2](https://github.com/sethvincent/adventuretron/issues/2)


