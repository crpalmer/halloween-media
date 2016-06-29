Halloween Audio

To keep all my audio files archived I am putting them here.  However,
cloning this whole repository onto my controllers doesn't scale.  We
can, however, keep it all sync'ed on real servers.

Each year's audio is to be a separate branch for that year's audio.
To create a new branch (on a real server) do:

git checkout -b <year> bbb59a13ceac435f046c3f3c5543d7b62d948b1a

To clone a specific year on a machine do:

rm -rf halloween-audio
git clone --single-branch --branch <year> git@github.com:crpalmer/halloween-audio.git
