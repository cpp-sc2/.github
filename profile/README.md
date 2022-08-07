# cpp-sc2
Hi, this organization is dedicated to the StarCraft II C++ API.

- **[cpp-sc2](https://github.com/cpp-sc2/cpp-sc2)** - implemnetation of the C++ API, forked from Blizzard's [s2client-api](https://github.com/Blizzard/s2client-api).
- **[blank-bot](https://github.com/cpp-sc2/blank-bot)** - starter bot for StarCraft II with integrated cpp-sc2;
- **[commandcenter](https://github.com/cpp-sc2/commandcenter)** - original version of CommandCenter bot with integrated cpp-sc2;
- **[docker-sc2](https://github.com/cpp-sc2/docker-sc2)** - dockerized StarCraft II Linux client.

There are many more [useful resources](https://github.com/aiarena/awesome-sc2-ai) related to the game and frameworks.

## Contributing
### How can I help?

- [ ] Search for other issues tagged [with `good first issue` or `help wanted` tag](https://github.com/cpp-sc2/cpp-sc2/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).
- [ ] Suggest new features.
- [ ] Vote for existing issues (issues with highest number of reactions are likely to be fixed first).
- [ ] Improve the documentation of the API.
- [ ] Fix spelling :)
- [ ] Add/Fix/Improve tutorials, bot examples and tests.
- [ ] Help to test latest changes.
- [ ] Support this project on [Boosty](https://boosty.to/cpp-sc2) (preferred) or [Patreon](https://www.patreon.com/cppsc2). Support of the project allows to make releases more often and implement nice new features for developers.

If you have any suggestions, feel free to message me over [Discord](https://discordapp.com/invite/Emm5Ztz) (the `#cpp` channel).

### What should I know before the start?

**Code guidelines**
We do our best to conform to [the Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) with the exception that we use four space tabs instead of two space tabs.

**Commit guidelines**
We follow the semantic versioning approach, this is important so your PR will appear on the Changelog 🎉 ! I guess you expect recognition and we will give it to you.
See [standard-version](https://github.com/conventional-changelog/standard-version#commit-message-convention-at-a-glance) for commit guidelines.

The list of supported commit message prefixes:

- `feat` - a new feature or API improvements;
- `fix` - a bugfix;
- `perf` - performance improvements;
- `refactor` - code refactoring;
- `test` - functional or unit tests;
- `build` - build system improvements,  also includes CI improvements;
- `docs` - documentation improvements;
- `chore` - routine task, e.g. create new release (doesn't appear in the changelog);
- `style` - fix code style, no functional changes (doesn't appear in the changelog.

### Before PR

* Keep the PR small as possible and one single topic for each.
* Write good commit message: describe what was the problem and why the changes required.
* Consider implementing a test.
