# mac-setup
Tools I use on a Mac

- [Iterm2](https://iterm2.com/downloads.html)
- [Oh My Zsh](https://ohmyz.sh/#install) + [powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#getting-started)
- [MeetingBar](https://apps.apple.com/us/app/meetingbar/id1532419400?mt=12) - Calendar dropdown
- [Alfred](https://www.alfredapp.com/)

- Trackpad settings, ‘secondary click - click or tap with two fingers'
- Colima - `brew install colima`, `colima start`
To install buildkit:

```bash

ARCH=arm64
VERSION=v0.10.4
curl -LO https://github.com/docker/buildx/releases/download/${VERSION}/buildx-${VERSION}.darwin-${ARCH}
mkdir -p ~/.docker/cli-plugins
mv buildx-${VERSION}.darwin-${ARCH} ~/.docker/cli-plugins/docker-buildx
chmod +x ~/.docker/cli-plugins/docker-buildx
docker buildx version
```
