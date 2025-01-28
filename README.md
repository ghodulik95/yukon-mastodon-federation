This repository puts together submodules game-federation, yukon-server, and yukon
together so that a local Yukon server uses Mastodon as a Federation service.

It should be possible to simply install NixOS on a server, install the nixos config,
and then set up the three submodules using their own repos documentation, and then
have this running.

I have not tested this from scratch on this repository yet, so it may not work yet.
In the future, I'd like to simplify this install process as much as possible,
possibly by making this into a docker container, and/or mkaing top-level install
scripts so you do not have to manually install each of the submodules separately.
