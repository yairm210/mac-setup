# mac-setup
Tools I use on a Mac

- [Iterm2](https://iterm2.com/downloads.html)
- [Oh My Zsh](https://ohmyz.sh/#install)
  - [powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#getting-started)
  - in ~/.zshrc, to option+arrow navigate like normal, add
    - `bindkey "\e\e[D" backward-word`
    - `bindkey "\e\e[C" forward-word`
- [MeetingBar](https://apps.apple.com/us/app/meetingbar/id1532419400?mt=12) - Calendar dropdown
- [Alfred](https://www.alfredapp.com/) - better search
- [Rectangle](https://rectangleapp.com/) - Windows-style 'move app to part of screen'

- Trackpad settings, ‘secondary click - click or tap with two fingers'
- To run dockers, Colima - `brew install colima`, `colima start`. 
Also requires installing buildkit:

```bash
ARCH=arm64
VERSION=v0.10.4
curl -LO https://github.com/docker/buildx/releases/download/${VERSION}/buildx-${VERSION}.darwin-${ARCH}
mkdir -p ~/.docker/cli-plugins
mv buildx-${VERSION}.darwin-${ARCH} ~/.docker/cli-plugins/docker-buildx
chmod +x ~/.docker/cli-plugins/docker-buildx
docker buildx version
```


- PyCharm / IntelliJ IDEA plugins:
  - Makefile language
  - Rainbow Brackets (freemium)

- Vscode extentions:
  - Git Graph
  - indent-rainbow
  - Rainbow Brackets  
