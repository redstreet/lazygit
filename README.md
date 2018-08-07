# lazygit [![Go Report Card](https://goreportcard.com/badge/github.com/jesseduffield/lazygit)](https://goreportcard.com/report/github.com/jesseduffield/lazygit)

A simple terminal UI for git commands, written in Go with the [gocui](https://github.com/jroimartin/gocui "gocui") library.

Are YOU tired of typing every git command directly into the terminal, but you're too stubborn to use Sourcetree because you'll never forgive Atlassian for making Jira? This is the app for you!

[Tutorial](https://www.youtube.com/watch?v=VDXvbHZYeKY)

![Gif](https://image.ibb.co/mmeXho/optimisedgif.gif)

## Installation
In a terminal call this command:
`go get github.com/jesseduffield/lazygit`
(if you don't have Go installed, you can follow the installation guide [here](https://golang.org/doc/install).

Then just call `lazygit` in your terminal inside a git repository.

If you want, you can also add an alias for this with `echo "alias lg='lazygit'" >> ~/.zshrc` (or whichever rc file you're using).

Please note:
If you get an error claiming that lazygit cannot be found or is not defined, you may need to add `~/go/bin` to your $PATH (MacOS/Linux), or `%HOME%\go\bin` (Windows)

### Ubuntu
Packages for Ubuntu 14.04 and up are available via Launchpad PPA.

They are built daily, straight from master branch.

```sh
sudo add-apt-repository ppa:lazygit-team/daily
sudo apt-get update
sudo apt-get install lazygit
```

## Cool features
- Adding files easily
- Resolving merge conflicts
- Easily check out recent branches
- Scroll through logs/diffs of branches/commits/stash
- Quick pushing/pulling
- Squash down and rename commits

### Resolving merge conflicts
![Gif](https://image.ibb.co/iyxUTT/shortermerging.gif)

### Viewing commit diffs
![Viewing Commit Diffs](https://image.ibb.co/gPD02o/capture.png)

## Docs
[Keybindings](https://github.com/jesseduffield/lazygit/blob/master/docs/Keybindings.md)

## Milestones
- [ ] Easy Installation (homebrew, release binaries)
- [ ] Configurable Keybindings
- [ ] Configurable Color Themes
- [ ] Spawning Subprocesses (help needed - have a look at https://github.com/jesseduffield/lazygit/pull/18)
- [ ] Performance
- [ ] i18n

## Contributing
I'll find a good template for contributing and then add it to the repo (or if somebody has a suggestion please put up a PR)

## Work in progress
This is still a work in progress so there's still bugs to iron out and as this is my first project in Go the code could no doubt use an increase in quality, but I'll be improving on it whenever I find the time. If you have any feedback feel free to [raise an issue](https://github.com/jesseduffield/lazygit/issues)/[submit a PR](https://github.com/jesseduffield/lazygit/pulls).
