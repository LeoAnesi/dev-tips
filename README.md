# dev-tips

## Generals
- Enable git rerere to not have to handle same conflicts multiple time : `git config --global rerere.enabled true`
- Update dependencies easily with `yarn upgrade-interactive --latest`
- Activate alias + completion for kubernetes in zsh: install `kubectl` plugin in `~/.zshrc`
- Stack overflow discussion to help you create automatically your tmux workspace [here](https://stackoverflow.com/questions/5609192/how-to-set-up-tmux-so-that-it-starts-up-with-specified-windows-opened)
- Push by default to your current branch: `git config --global push.default current`
- Git by default is not case sensitive, so changing file name `Hello.ts` to `hello.ts` will not trigger any change, to avoid that change git config with : `git config core.ignorecase false`
- Dig disk usage `du -a {directory} -cBM --max-depth=1 2>/dev/null | sort -n`
- [Postman crash issue](https://github.com/postmanlabs/postman-app-support/issues/7055)
