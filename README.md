#TMPTOOLS
\
\
\
build
\
\
\
nix build -f pkgs.nix -I nixpkgs=channel:nixpkgs-unstable -o tmptools
\
\
\
use
\
\
\
nix-shell pkg.nix -I nixpkgs=channel:nixpkgs-unstable
